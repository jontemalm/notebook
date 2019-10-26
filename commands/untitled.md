#  Mac Commands

#### Flush DNS

```bash
sudo killall -HUP mDNSResponder
```

#### Dock Spacer

```bash
defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'; killall Dock
```





