# Create-Feh-captions-from-image-filenames
# Python
# Requirements - glob, os, and unidecode
# User must replace the path with the path of the directory containing Feh image files.
# The script iterates over the files in the directory, creating text files from the filename to be used a Feh captions
# To display the captions, move the text files to a subdirectory in the image directory, and add --caption-path to the Feh command line'
# Example Feh command, where "/home/pi/art" is the path containing the image files, and "/captions" is the path containing the caption files
# feh -ZzFxY /home/pi/art --caption-path /captions &
