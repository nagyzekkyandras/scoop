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

# Install apps
scoop install main/nvm
```

### My workstation apps
```ps1
scoop install 7zip git nvm
```
