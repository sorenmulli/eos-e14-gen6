# EndeavourOS on E14 Gen6

Installed EndeavourOS with XFCE desktop environment, systemd-boot.

## 1. Display
### 2.1 Displaylink
- Installed `evdi` and `displaylink` and enabled connected screens in display settings.
- Had to set laptop screen as primary and move panel.

## 2. Audio
### 2.1 Microphone
I currently cannot get the microphone to work! I tried a number of different distros and kernel versions but the internal microphone is always disconnected.

## 3. Connectivity
### 3.1 Bluetooth
- `sudo systemctl enable bluetooth.service`
- `sudo systemctl start bluetooth.service`

## 4. i3 and CLI environment
Followed my dotfiles: https://github.com/sorenmulli/dotfiles
