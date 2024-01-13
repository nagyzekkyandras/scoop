# scoop
The Windows package manager.

### Install
```ps1
# Set the "Execution Policy"
# https:/go.microsoft.com/fwlink/?LinkID=135170
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

# Install the application
iwr -useb get.scoop.sh | iex

# Add the git to use buckets
scoop install git
```

### Usage
```ps1
# add a bukcet
scoop bucket add main
scoop bucket add extras
scoop bucket add games

# Install apps
scoop install main/nvm
```

### My workstation apps
```ps1
# general tools
scoop install 7zip git googlechrome vscode

# developer tools
scoop install nvm@1.1.11

# games stuff
scoop install steam
```
> nvm@1.1.12 got some issue so needed to rollback, more info: https://github.com/coreybutler/nvm-windows/issues/1069
