# Sky - A powershell theme 


![SKY PREVIEW](https://github.com/fgalmeida/sky/blob/main/github/screenshot.png)
![SKY PREVIEW](https://github.com/fgalmeida/sky/blob/main/github/screenshot-2.png)
 
![badge](https://img.shields.io/github/issues-raw/fgalmeida/sky?style=flat-square)
![badge](https://img.shields.io/github/forks/fgalmeida/sky?style=social)
![badge](https://img.shields.io/github/stars/fgalmeida/sky?style=social)<space><space>
 
## Steps

1. Install `oh-my-posh` - `Set-ExecutionPolicy Bypass -Scope Process -Force; Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://ohmyposh.dev/install.ps1'))`

2. Run `curl https://raw.githubusercontent.com/fgalmeida/sky/master/sky.omp.json --output sky.omp.json` (assuming `curl` is installed on your system)

3. Run `Copy-Item -Path sky.omp.json -Destination $HOME`

4. Open up the file `$profile` in your text editor of choice (VScode: `code $profile`, Notepad: `notepad $profile`)

5. Add these lines: 

```powershell
oh-my-posh init pwsh --config ~/sky.omp.json | Invoke-Expression
```

7. Restart terminal and you should see a pretty prompt!

## Customize my theme

Edit `sky.omp.json` (Notepad: `notepad ~/sky.omp.json`, VScode: `code ~/sky.omp.json`) and change as you see fit ([how to configure a theme?](https://ohmyposh.dev/docs/config-overview))
