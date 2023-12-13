### Using my ideavimrc (Run as Administrator)
```pwsh
New-Item -ItemType SymbolicLink -Path $HOME\.ideavimrc -Target $HOME\dotfiles\.ideavimrc
```

### Importing Webstorm config
```
- Menu
  |--- File
        |--- Manage IDE Settings
              |--- Import Settings # and select settings.zip to use my webstorm config
```

to update .ideavimrc just pull from master branch using `git pull` command 
