# Neovim Configuration Initialization 

### Install Neovim
```
winget install neovim
```
or 
```
choco install neovim
```

### Set XDG_CONFIG_HOME environment variable
run in PowerShell as administrator
```
[Environment]::SetEnvironmentVariable('XDG_CONFIG_HOME', '$env:USERPROFILE\.config', 'Machine')
```

### Clone repo
```
git clone https://github.com/drewdev02/Nvim-config.git $env:USERPROFILE\.config\nvim
```

### Move into that path
```
cd $env:USERPROFILE\.config\nvim
```