# Operation-Mental_Moron

Operation Mental Moron is a simple application that "converts" audio files to text using OpenAI's Whisper speech recognition model.
# 🛠️ **Requirements**
- Python 3.8+
- ffmpeg
- Whisper

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
2. Place Raw audio file in raw_audio/
3. Navigate to scripts/
4. Run process_audio.sh 
``process_audio.sh``
5. Once audio clip has been processed, run TransribeAudio.py
``python3 TransribeAudio.py``


