# entrello-gate

desktop application to connect to entrello services an printers

## windows

- download the .exe file
- copy the `views` and `VERSION` file of this repo into the same folder, where
  you store the .exe file

## mac

- just double click the dmg and move the app to your applications

### adding a printer

cups:

```
cupsctl WebInterface=yes
```

## debugging

mac: $HOME/Library/ApplicationSupport/e7
win: $HOME/AppData/Roaming/e7

find an `entrello.log` file with debug information there
