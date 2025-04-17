# Project name: 

This project was inspired after watching a podcast on YouTube in which a guest discussed their experience with bipolar disorder. 
Unfortunately, both the guest and the host approached the topic with insensitivity—laughing, spreading misinformation, and minimizing the seriousness of the condition. 
This naturally upset me. 
However, before jumping to conclusions, I wanted to ensure I had accurately understood what was said. 
To verify and analyze the conversation objectively, I built this transcription tool to convert spoken words into readable text.

# Purpose:
**Operation_MentalMoron** is a simple utility that converts audio files into text using OpenAI's Whisper speech recognition model.



# 🛠️ **Requirements**
- Python 3.8+
- ffmpeg
- Whisper
- Python Virual Enviroment

**# 📁 File Structure**

```
/home/$USER/Operation-MentalMoron/
├── preprocessed_audio/
├── raw_audio/
├── scripts/
├── transcripts/
└── whisper-env/
```

# 📂 Directory Purpose
## **raw_audio**
This folder contains the original, unprocessed audio files (e.g., .mp3, .wav).
Files placed here are not yet converted or split for transcription.
## **preprocessed_audio**
Contains audio files converted to 16kHz mono .wav format, ready for transcription by Whisper.
## **transcripts**
Stores the generated transcripts as .txt files.
## **scripts**
Custom scripts related to audio preprocessing, transcription, or automation.
## **whisper-env**
Python virtual environment containing dependencies, including Whisper and any other required libraries.

---------------------------------------------------------------------------------------------------

# 🚀 Getting Started
1. Clone the repo:
2. Uncompress the tar file
``tar -xvf Operation-MentalMoron.tar.xz``
3. Place Raw audio file in raw_audio/
4. Navigate to scripts/
5. Run process_audio.sh 
``process_audio.sh``
6. Once audio clip has been processed, run TransribeAudio.py
``python3 TransribeAudio.py``


