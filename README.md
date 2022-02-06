# personal-scripts-repo

This repository is meant to host my own scripts for personal use, but interested users should feel free to use them or contribute.

To do: Check for bashisms and make scripts more POSIX compliant.

## List of scripts:

### battctl
Meant to control batteries, mainly from ThinkPads.

### sscpbrd
Take screenshots and copy them to the clipboard.

Dependencies: xclip and one of: imagemagick, scrot

### startdslr
Start DSLR cameras using gphoto2.

Dependencies: gphoto2, ffmpeg

### statusbar
Statusbar for toolbars or window managers using WM_NAME.

Dependencies: iwd or wirtools, awk, xsetroot

### update-ytdl
Update ytdl for distributions where the package management is not regularly maintained up to date.

Dependencies: wget, lynx, awk

### viewwebcam-mpv
View webcam footage on mpv.

Dependencies: mpv


### limittablet
Limit wacom tablet to one monitor.

Dependencies: xsetwacom, awk

### xvirtdisp
Create a virtual display to be connected via a VNC client.

Dependencies: xrandr, cvt, awk
Note: Does not work on Wayland


### weather2img
Convert data from webpage wttr.io to an image using imagemagick.  Might be interesting to use as a dynamic wallpaper, widget, or something alike.

Dependencies: lynx, imagemagick, gnu free fonts
