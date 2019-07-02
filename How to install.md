## How to Install Platinum9

## Icons:
Place the folder NineIcons in ~/.icons
Then goto your settings in xfce. Then apperance, goto icons and select NineIcons.

## Fonts:
!!YOU NEED A ROOT ENABLED FILE MANAGER WINDOW OPENED!!
Place them in /root/.fonts/ and update your font cache and you should be good to go.
Here is my font setup.
Default: Charcoal Italic.
Default Monospace: Monaco Italic.
Under Window Manager I Changed the Title font to Charcoal Italic.

## Window Themes:
Copy ClassicPlatinumStreamlined & Copland to ~/.themes
Goto Settings, Appearance, Select ClassicPlatinumStreamlined, Back out and enter Window Manager, Select copland.

## Plymouth Theme:
!!YOU NEED A ROOT ENABLED FILE MANAGER WINDOW OPENED!!
If you need to know how then enter the terminal and type 
`$ sudo *replace with your file manager*`
Common File Managers:
Gnome:nautilus
XFCE:thunar
Copy the System8 folder to /usr/share/plymouth/themes/
then enter the terminal and type 
`$ sudo update-alternatives --config default.plymouth`
Look for System8 and enter the number then press enter.
Afterwards type
`$ sudo update-initramfs -u`

## Panel:
First open terminal and type
`$ sudo apt-get install xfce4-appmenu-plugin`
Then goto Settings, XFCE Panel Switch, Press the open folder button and navigate to the Panel folder, Select OS9.
Your Panel Has now been Changed to mine!

Finally sit back and play your games or whatever you do with a wonderful nostalgic feel!
Your welcome!
