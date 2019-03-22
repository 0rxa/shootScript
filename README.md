# Wrapper for scrot
The script provides a simple way to save your scrot outputs with different filenames or at different locations.

I bind this script in i3config so it either works normally like just running scrot or asks you for input. Depending on your input the script will save the file with the given name or at the given path.

The script depends on dmenu and notify-send. It has simple error catching but nothing fancy, so it will notify you when an error has happened but will do nothing to stop it because scrot handles that very well.
