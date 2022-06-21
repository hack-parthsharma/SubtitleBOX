# SBOX - Subtitle Box

SBOX is a python script to download subtitles for your movies from [SubDB](http://thesubdb.com/) database using their API. SubDB is a free, centralized subtitle database intended to be used only by opensource and non-commercial softwares. 

Please Note: Subtitle file will be downloaded in to the same folder as the correspondent video file.

## Features
- [x] Download subtitle files of different languages.
- [x] Download subtitles for multiple movies at once.
- [x] Command line mode for terminal users.

## Git Installation
```
# clone the repo

# Change the working directory to SubtitleBOX

# install the requirements
$ pip3 install -r requirements.txt
```

## (OSX/Linux only) Install tkinter
If you are running python 3.7 or later, nothing has to be done. Earlier python3 versions require installation.
```
# Debian/Ubuntu
$ sudo apt install python3-tk

# macOS
# Follow the instructions on https://tkdocs.com/tutorial/install.html
```

## Usage

```
python sbox.py
```

```
usage: sbox.py [-h] [-f FILE_PATH] [-lang LANGUAGE_CODE]

SubtitleBOX CLI

optional arguments:
  -h, --help            show this help message and exit
  -f FILE_PATH, --file_path FILE_PATH
                        Path of the video file for which subtitles should be
                        looked for
  -lang LANGUAGE_CODE, --language_code LANGUAGE_CODE
                        Language code for subtitles. Can be en, es, fr, it,
                        nl, pl, pt, ro, sv, tr
```
