# Sky - A powershell theme 


![SKY PREVIEW](https://github.com/fgalmeida/sky/blob/main/github/screenshot.png)
![SKY PREVIEW](https://github.com/fgalmeida/sky/blob/main/github/screenshot-2.png)
 
![badge](https://img.shields.io/github/issues-raw/fgalmeida/sky?style=flat-square)
![badge](https://img.shields.io/github/forks/fgalmeida/sky?style=social)
![badge](https://img.shields.io/github/stars/fgalmeida/sky?style=social)<space><space>
 
## Steps

1. Install `oh-my-posh` - `Install-Module posh-git -Scope CurrentUser` and `Install-Module oh-my-posh -Scope CurrentUser`

2. Open up the file `$profile` in your text editor of choice (VScode: `code $profile`, Notepad: `notepad $profile`)

3. Add these lines: 

```powershell
Import-Module posh-git
Import-Module oh-my-posh
Set-PoshPrompt ~/sky.omp.json
```

5. Run `curl https://raw.githubusercontent.com/fgalmeida/sky/master/sky.omp.json --output sky.omp.json` (assuming `curl` is installed on your system)

6. Run `Copy-Item -Path sky.omp.json -Destination $HOME`

7. Restart terminal and you should see a pretty prompt!

## Customize my theme

Edit `sky.omp.json` (Notepad: `notepad ~/sky.omp.json`, VScode: `code ~/sky.omp.json`) and change as you see fit ([how to configure a theme?](https://ohmyposh.dev/docs/config-overview))
