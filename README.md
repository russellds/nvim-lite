# nvim-lite

[A suckless NeoVim Config](https://www.youtube.com/watch?v=skW3clVG5Fo)

Requires NeoVim 0.11.2 or later.

## Original Source

Copy and enjoy it with:

```bash
mkdir -p ~/.config/nvim && curl -fsSL https://raw.githubusercontent.com/radleylewis/nvim-lite/master/init.lua -o ~/.config/nvim/init.lua
```

## My Version

### Windows

```powershell
$env:NVIM_APPNAME = 'nvim/min'
if (-not (Test-Path -Path "${env:LOCALAPPDATA}\${env:NVIM_APPNAME}")) { New-Item -Path "${env:LOCALAPPDATA}\${env:NVIM_APPNAME}" -ItemType 'Directory' -Force }
git clone https://github.com/russellds/nvim-lite.git "${env:LOCALAPPDATA}\${env:NVIM_APPNAME}"
```
