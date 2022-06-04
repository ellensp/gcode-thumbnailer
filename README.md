# gcode-thumbnailer

A simple thumbnail generator for Gnome.
This extracts the encoded thumbnail data from within a gcode file and turns it into OS useable thumbnail, such as in nautilus.

Only tested on Ubuntu 20.04.4 LTS.

Consists of two files:

Gcode-with-thumbnail-thumbnailer.py
The python script that extracts and generates the required png file.

gcode-with-thumbnail.thumbnailer
Configuration file to associate *.gcode with the thumbnailer application.

Instiltion is manual:

Copy gcode-with-thumbnail.thumbnailer to /usr/share/thumbnails/
Copy gcode-with-thumbnail-thumbnailer.py to somewhere in you path. For eg /usr/local/bin/

How to add thumbnail to gcode:

I used the method mentioned here https://github.com/mriscoc/Ender3V2S1/wiki/How-to-generate-a-gcode-preview

This is also compatable with PrusaSlicer 2.4.2 inbult thumbnail generator.

Examples:

![Example at 2 * Zoom](https://github.com/ellensp/gcode-thumbnailer/blob/main/examples%20(2xZoom).png?raw=true)