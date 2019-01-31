# PiHole-Panel
![](https://raw.githubusercontent.com/daleosm/PiHole-Panel/master/mainwindow.png)


PiHole-Panel 1.8
- Now works with package manager
- Fixed handling of when Pi-hole host is down
- Fixed update notification

PiHole-Panel 1.7
- More helpful error messages

PiHole-Panel 1.6
- Update notification

PiHole-Panel < 1.5
- Truncated URLs over 36 characters
- Implemented validation for setup
- Now works with admin console password
- Updated icon

## Install

Install/Update:
```
sudo apt install python3-gi
```
```
cd ~/Downloads
sudo dpkg -i PiHole-Panel-1.8.deb
```

Uninstall:
```
sudo apt remove pihole-panel
```

Troubleshoot:
```
rm ~/.config/pihole_panel_configs.xml
```
