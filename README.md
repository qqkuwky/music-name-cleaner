# music-name-cleaner
Simple python script to remove album and artist name from music files name

**An example of script work:** Radiohead - No Surprises - 01-01 No Surprises.mp3 ---> 01-01 No Surprises.mp3

**After running the code:**
1. You need to specify the directory containing the files you want to rename
2. You choose the mode — automatic or manual. *In automatic mode (the renaming is done according to your choice): everything before the first dash (" - ") in the file name is removed (if the name contains only the artist or album), or before the second dash (if the name contains both the artist and album). In manual mode, you enter the text that needs to be removed from the file names*

Support mp3, flac, wav, aac, ogg
