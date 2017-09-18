# Video-Smoke-Detector

This program analyzes video frames to look for smoke.
It gives a confidence level score between 0% and 100%.
To speed up the analysis, the program only analyzes every 10th frame in the source video stream.
Thus for example, for a 30 fps video, the video is analyzed 3 times per second.
The program is based on the tensorflow retraining tutorial for flower recognition.
www.tensorflow.org/tutorials/image_retraining


Usage:
SOURCE_FILES is a list of videos need to be analyzed.
DESTINATION_FILES is a list of the desired output video file names.
The program overlays the analysis results at the bottom of the screen.
The original videos' audio tracks will be stripped from the output videos.




Author: Chen-Yi Liu

Date: September 3, 2017
