# linux_setup
Various Configurations for Linux Setup

## i3 - Tiling Window Manager   
### config
i3 config   
**path:**  `~/.config/i3/config `
### i3status.conf
i3 status bar customizations.   
**path:** `/etc/i3status.conf` or `~/.config/i3/i3status.conf`
	
## xmodmap 
Keyboard customisations for Emacs/and hence for linux. 
1. CapsLock --> Ctrl 
2. Shift+CapsLock --> CapsLock   
**path** - `./Xmodmap`  
Run `xmodmap ~/.Xmodmap` in terminal for immediate effect. 
	
## gtk3.0
Emacs like keybindings for Google Chrome.   
**path:**  `~/.config/gtk-3.0/settings.init`  

## xrandr - 
### Multi monitor setup
`xrandr --output HDMI-0 --auto --left-of eDP-1`

### brightness 
`xrandr --output DP-4 --brightness 0.8`

## xinput 
### disable keyboard/input device
1. Find slave id of the keyboard `xinput list`
2. Disable keyboard. `xinput --disable <slave-id>`
3. Enable keyboard. `xinput --enable <slave-id>`

## TODOs
- [ ] Github ssh setup for multiple account - [Link](https://www.freecodecamp.org/news/manage-multiple-github-accounts-the-ssh-way-2dadc30ccaca/)
	- Create a readme for ssh setup using the above link.
