

# **Voice Recognition and Summarization**  

This project transcribes audio files using **Vosk** and **Google Speech Recognition**, then summarizes the extracted text using **Hugging Face Transformers**.  

## **Features**  
- **Converts MP3 audio to WAV format using ffmpeg**  
- **Uses Vosk for offline speech-to-text transcription**  
- **Uses Google Speech Recognition for an alternative transcription method**  
- **Summarizes large transcriptions using a Transformer-based model**  

## **Usage**  

1. **Transcribe audio with Vosk.**  
2. **Convert MP3 to WAV**  
   If using **Google Speech Recognition**, convert the file to WAV format first:  
   ```bash
   ffmpeg -i marketplace.mp3 marketplace.wav
3. **Transcribe with Google Speech Recognition.**
4. **Summarize Transcription.**


## **Dependencies**

- pydub: For audio processing
- vosk: For offline speech recognition
- SpeechRecognition: For online speech recognition using Google's API
- transformers: For text summarization
- ffmpeg: Required for converting MP3 files to WAV

## **Notes**

Ensure you have ffmpeg installed on your system for audio conversion.
The Vosk model requires downloading an appropriate language model for transcription.

## **License**
This project is open-source under the MIT License.

