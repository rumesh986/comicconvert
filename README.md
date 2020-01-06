# comicconvert
comicconvert is a simple script that converts any cbr or cbz files to an easy to read pdf.

All you have to do is run `chmod +x ./comicconvert` from the directory containing the file and then move it to `/usr/local/bin/` to be able to run it from anywhere.

This program was used on a computer running Ubuntu 16.04 and on a windows computers with the windows subsystem for linux.

Reading comics in PDF format is useful when trying to read on devices without the special software for reading cbr or cbz files. This makes it much easier to read comics from various devices

TIP: If you are using the nautilus file manager, place a copy of the script in `~/.local/share/nautilus/scripts` to be able to run comicconvert without using the command line.

This program requires  `img2pdf`. you can install it on ubuntu and bash on windows by running `sudo apt install img2pdf`.
