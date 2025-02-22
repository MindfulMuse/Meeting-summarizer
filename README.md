Voice Recognition and Summarization

This project transcribes speech from an audio file and summarizes the extracted text using machine learning models.

Features

Converts MP3 audio to text using the Vosk speech recognition model

Alternative transcription using Google's SpeechRecognition API

Summarizes transcribed text using the transformers library

Usage

1. Convert MP3 audio to WAV format (if needed):
ffmpeg -i marketplace.mp3 marketplace.wav
2. Run the script to transcribe and summarize the audio file:

Dependencies

pydub: For audio processing

vosk: For offline speech recognition

SpeechRecognition: For online speech recognition using Google's API

transformers: For text summarization

ffmpeg: Required for converting MP3 files to WAV

Notes

Ensure you have ffmpeg installed on your system for audio conversion.

The Vosk model requires downloading an appropriate language model for transcription.


License

This project is open-source and available for use under the MIT License.

