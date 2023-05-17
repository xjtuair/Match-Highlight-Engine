
<h1 align="center">:football: Match Highlight Engine :cricket:</h1>

<div align="center">

<br>

[![made-with-python](https://forthebadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

<br>

</div>

Whether it's cricket or football, wouldn't you love the ability to generate your own highlights for missed matches or favorite past games? That's exactly what this tool can do for you! :smile:

This project harnesses simple concepts of energy threshold in audio waves to produce basic highlights packages. All this, without the need for complex *computer vision and NLP!*

In addition to providing an interesting application for match enthusiasts, this project also serves as a practice ground for those wanting to get acquainted with audio and video processing libraries in Python3.6.

### TODOs:

* [ ] Develop a GUI for easy video uploads and highlights downloads.
* [ ] Implement auto-generation of audio files for uploaded videos.
* [ ] Provide a way for users to set variable parameters like sample rate, filename, chunk size, threshold, etc, via Terminal/GUI.
* [ ] Work on reducing latency time by splitting the video and then parallelizing the highlights extraction process.
* [x] Auto-delete the subclips generated during the highlight creation process.

Additional Resources: For sample video and audio, kindly click [here](https://drive.google.com/open?id=1bWfQat17fmmpBo92w698C2sxRxBEztnk). It contains match video, audio files and also the script generated highlights:

1. India vs Australia 2007 World Cup Indian Powerplay.
2. KKR vs RCB (RCB 49 All out).

## To run this project:
* [Fork](https://github.com/xjtuair/Match-Highlight-Engine) this Repository.
* Open Terminal and enter the folder 'Match-Highlight-Engine'.
* `pip3 install -r requirements.txt`
* Download the full match video and its related audio file in the present working directory.
* Set variables for input audio and video filenames and desired output filename in code. This will soon be changed to allow setting from terminal arguments.
* Run `python3 generator.py`
* Be patient as the highlights are being created! :alarm_clock: