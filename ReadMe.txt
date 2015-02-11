ConkyBar V1.0 forked by gmhafiz
===============================

This ConkyBar is a modified version of N00by4Ever's at 
http://n00by4ever.deviantart.com/art/conky-conkyBar-launchpad-V2-0-401254455

I replaced banshee support with modified weather config obtained from Conky Manager's .conkyrc-dark 
I also added local ip address to the network config.

Screenshot: http://i.imgur.com/ecG9cdr.jpg

Useful info:

Colors (for color0 + lua files)
===============================
Arch 		1793d0	(blue)
Mint 		77B753	(green)
Ubuntu		dd4814	(orange)
Debian 		d70a53	(red)


Installation steps:
====================
1) Put the folder .conkyconfig in your home folder.
2) Make sure your conky version stupport lua and nvidia (arch: conky-lua-nv)
3) Make sure you've got all the dependencies (hddtemp, iostat, ...) and they are running (also on startup)
4) Make conky_start (and all files in /lua and /scripts) executable.
5) Add conky_start to your startup programs
6) Make sure you've installed the fonts in /fonts
7) Edit the system specific setting, for example in conky_network change it to your wifi/eth interface


Known bugs
====================
- Pauze banshee -> wrong current position value -> bug in banshee --query-position -> I can't solve it
- The hdd graph (ring) does have a blank space in the beginning
- The outlinement is not perfect
- Seconds uptime are 1sec off


Credits
====================
N00by4Ever's - http://n00by4ever.deviantart.com/art/conky-conkyBar-launchpad-V2-0-401254455
Look based on: Conky Launchpad - http://freeazy.deviantart.com/art/Conky-Launchpad-186251285
Thanks to crunchbang forums - http://crunchbang.org/forums/viewtopic.php?id=16909
Icons - forgot sorry
Banshee implementation - kaivalagi  - http://ubuntuforums.org/showthread.php?t=1223883
Weather config - https://launchpad.net/conky-manager

Feel free to fork/improve

