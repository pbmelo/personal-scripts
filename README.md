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


## LICENSE

Copyright (C) 2022 pbmelo

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program. If not, see <https://www.gnu.org/licenses/>.
