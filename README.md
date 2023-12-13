### Using my ideavimrc
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