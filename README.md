# Python script to batch create Feh captions from imagefilenames
The idea and much of the code came from radar's answer to this question: https://gis.stackexchange.com/questions/60730/create-text-files-from-a-loop-with-python/60738
Requirements - glob, os, and unidecode.
User must replace the path with the path of the directory containing Feh image files.
The script iterates over the files in the directory, creating text files from the filename to be used a Feh captions.
To display the captions in Feh slideshow mode, move the text files to a subdirectory in the image directory, and add --caption-path to the Feh command line.
Example Feh command, where "/home/pi/art" is the path containing the image files, and "/captions" is the path containing the caption files
is:
feh -ZzFxY /home/pi/art --caption-path /captions 
