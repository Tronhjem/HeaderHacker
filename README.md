#Header Hacker

Hack the header of a wave file, to change the interpreted sample rate.  
The script does not do sample rate conversion or time stretch, but change sample rate in the header of the file.
This means a file of 88.2Hz, changed with the script to be played as 44.1kHz, would play at half the speed.

Usage

* make sure Python3 is installed. 
* open commandline of your choice and cd to folder with main.py
* Drag and drop a folder of .wav files, or a single file into the commandline to get get path.
* Input the sample rates you want to change to, seperate with comma. e.g. 44100,22050,11000
* Wait for processing and folder will open.