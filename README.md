# BG-Changer
Background Changer for i3 (might work with other stuff too)

# Usage
On BGchangers initial launch, it will make a folder in your accounts home folder called Wallpapers close the program and move your background images into the folder.

on its sencond launch it will detect the images and start scrolling through, one per minute (by default, this can be changed)

# Options

`--time, -t`: this will let you change the ammount of time an image is displayed for.
*E.G. -t=5 or -t:5 = 5 mins/image.*

`--help, -h`: displays help page. (A little lacking rn)

`--single, -s`: Single image mode, if you just want to display one image. this arument will let you choose a file from a list, *e.g. `bgmanager -s`* , if you know the number already you can simply append it as an argument *e.g. bgmanager -s:1 or bgmanager -s=1*
**(Warning: Numbers can change with folder changes, always check after adding or removing a file)**

`--list, -l`: Lists all the images in the wallpapers folder

`--random, -r`: default randomiser for all images in wallpaper folder

`--init, --initialise, -i`: will rin the initialise section if you want to just make the folder without doing it manually.

# Requirements
Only Feh, Nim too if you want to compile it yourself.

Have fun <('-'<)
