<<<<<<< HEAD
# VidTranscribe
=======
# VidTranscribe

![Logo of VidTranscribe](images/01.png)

VidTranscribe is cross-platform tool that desigened to transcribe video or audio files into text effortlessly.
VidTranscribe utilizes [whisper.cpp](https://github.com/ggerganov/whisper.cpp), a library primarily written in C/C++ that enables blazing fast🔥🔥🔥 text transcription. 

## Features

- All the necessary packages and libraries are downloaded automatically
- User is provided a GUI to select the audio or video file for transcription
- Faster transcription for Apple machine with ARM architecture
- After transcription the Video file is played automatically along with subtitles
- User will be provided transcribed and summarized text which can be used as short notes

## Tech

VidTranscribe uses a number of open source projects to work properly:

- whisper.cpp - Transcribes Video and Audio
- tkinter - Provides simple and smooth GUI
- ffmpeg - Helps in extracting audio from video in wav format
- VLC - Plays video files with subtitles

## Installation

VidTranscribe requires Git ,G++ and Python (3.9 - 3.11 are recommended versions) to be installed
If you are on Windows you have to manually install ffmpeg and VLC

- Clone this repository
```bash
git clone https://github.com/AdityaPacharne/VidTranscribe.git
```

- Move inside the new directory
```bash
cd VidTranscribe
```

- Create a python virtual environment
```bash
python3 -m venv env
source ./env/bin/activate
```

- Execute the python program
```bash
python vidtranscribe.py
```

Once the required libraries and packages are succesfully installed you will see the GUI of our application
![Screenshot of our GUI](images/02.jpg)
Here you can select your preferred model from the given options

## Demonstration

https://github.com/user-attachments/assets/c5d8744e-d3cd-4862-aaa5-e2b8da71e173

## Available Models

|  Size  | Parameters | Required VRAM | Relative speed |
|:------:|:----------:|:-------------:|:--------------:|
|  tiny  |    39 M    |     ~1 GB     |      ~32x      |
|  base  |    74 M    |     ~1 GB     |      ~16x      |
| small  |   244 M    |     ~2 GB     |      ~6x       |
| medium |   769 M    |     ~5 GB     |      ~2x       |
| large  |   1550 M   |    ~10 GB     |       1x       |

They vary on the basis of size, speed and accuracy.
Larger the model, Lower the Speed, Higher the Accuracy.

Then you can click on the Browse button and browse your directories and select the video file that you want to transcribe.

Once you have submitted your desired video file, you can sit back and relax.

VLC media player will open automatically with your selected video along with subtitles

Then, your file manager will pop up with transcription.txt and summary.txt files appearing on it.
>>>>>>> 60e9561 (Initial commit)
