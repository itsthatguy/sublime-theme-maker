# sublime theme maker

* setup with `bundle`

* run with `bundle exec guard`

* Create a symbolic link to use with your Sublime text packages folder

```
# Sublime Text 2:
export PATH_TO_REPO="${HOME}/git/sublime-theme-maker"; ln -s ${PATH_TO_REPO}/themes/ $HOME/Library/Application\ Support/Sublime\ Text\ 2/Packages/Theme\ -\ itg.flat

# Sublime Text 3:
export PATH_TO_REPO="${HOME}/git/sublime-theme-maker"; ln -s ${PATH_TO_REPO}/themes/ $HOME/Library/Application\ Support/Sublime\ Text\ 3/Packages/Theme\ -\ itg.flat
```

## Explain-a-nator

Using guard and mustache you are able to edit yaml files to automatically generate sublime-theme files.
