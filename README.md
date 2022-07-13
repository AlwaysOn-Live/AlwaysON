![AlwaysON](src/AlwaysON.png "AlwaysON")

# AlwaysON
a MAX/MSP patch listener from the sound card input sources which start recording automatically when ever a db threshold is being reached.


#  Table of Contents

- [Download](#Download)
- [Features](#Features)

# Download


## Mac OS Download

The latest stable release is available via the url below:
https://www.dropbox.com/s/m028zud6bye5sy8/AlwaysON.zip?dl=0

# Features
- Supports recording of audio and midi
- Recording will start automatically only if threshold (which can be determined) will be above X db for Y seconds. 
- Recording will continue as long as threshold is still above X, but with a time-window of Z secs- where even if the threshold is below X, it will continue (so it won’t just stop immediately on each pause)
- Once recording is completed (meaning threshold X has not reached for Z seconds) - the recording will be saved as a file
- The File is named automatically with date and time, and a prefix which can be modified
- The app will continue listening to the audio input for the next recording.
- You can set a few different input sources from the sound card, for each listener (mono or stereo) and define different values of X,Y,Z values.

