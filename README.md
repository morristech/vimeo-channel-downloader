# vimeo-channel-downloader
You want to download many videos from vimeo ? 
Oh man too many clicks and hassle why not sit back, relax and use 
this awseome Python3 script. It will download all videos in a vimeo
channel, just give it a vimeourl nothing else. Plus it can resume 
from where it stopped when things get frisky well i mean if something
bad happens.


Ι hope(/think) it works with Python2 haven't tested it yet good luck.


# Installation
Before running you need to install some python libraries
pip install requests bs4 vimeo_dl

# Usage
ptyhon vimeodl.py [-h] [-o SAVE_PATH] [-r] url

* -h help message
* -o video save directory if not specified then it saves to the current working directory
* -r resume from the last downloaded video if not used download all videos from start
* url a vimeo url
