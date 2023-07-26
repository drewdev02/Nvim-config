# Neovim Configuration Initialization 

# Install Neovim
```
winget install neovim
```
## or 
```
choco install neovim
```



# Set XDG_CONFIG_HOME environment variable

## Run in PowerShell as administrator
```
[Environment]::SetEnvironmentVariable('XDG_CONFIG_HOME', '$env:USERPROFILE\.config', 'Machine')
```
# Move into that path
```
cd $env:USERPROFILE\.config
```

# Clone repo
```
git clone https://github.com/drewdev02/Nvim-config.git
```


# Rename folder to nvim
```
Rename-Item -Path "$env:USERPROFILE\.config\Nvim-config" -NewName "nvim"
```
