# comicconvert
comicconvert is a simple script that converts any cbr or cbz files to an easy to read pdf.

All you have to do is run `chmod +x ./comicconvert` from the directory containing the file and then move it to `/usr/local/bin/` to be able to run it from anywhere.

This program was used on a computer running Ubuntu 16.04 and on a windows computers with the windows subsystem for linux. 

Reading comics in PDF format is useful when trying to read on devices without the special software for reading cbr or cbz files. This makes it much easier to read comics from various devices

TIP: If you are using the nautilus file manager, place a copy of the script in `~/.local/share/nautilus/scripts` to be able to run comicconvert without using the command line.

NOTE: This program requires  `imagemagick`. you can install it on ubuntu and bash on windows by running `sudo apt-get install imagemagick`.

While converting large comics, you may get some errors associated with low RAM. This is a problem with `imagemagick`. If you have this problem, you can use `img2pdf` from https://github.com/josch/img2pdf instead. 
