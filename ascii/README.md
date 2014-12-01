ASCII
=========

Only tested on PNG and JPG

I'm not the first person to come up with this, but I did write it from scratch. Requires the Python Image Library (PIL), which has been adapted to python 3 under the name "Pillow"

    pip install pillow

For best results, put the pictures in the same folder as the script. Then double-click to start. 

1. The filename. If you don't put the extension, it is assumed PNG.

2. The characterpixel resolution. That is, every individual character will represent `x`x`y` pixels from the image. Enter "x y" exactly. ("3 5", "9 15", "8 12"). If left blank, it defaults to 8 12

3. The Smoothing. At `1`, the script will have access to all 95 characters. At `2`, it will use every other character, for 42 possible, and so on. Low values can be very messy and hard to look at. If left blank, defaults to 8.



To-do:

Make tkinter GUI.