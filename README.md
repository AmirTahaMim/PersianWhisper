# Persian Whisper Speech Recognition

This project utilizes the Whisper model for automatic speech recognition (ASR) of Persian language audio files. By leveraging state-of-the-art natural language processing techniques, this application transcribes spoken Persian into text, providing a valuable tool for various applications, such as language learning, transcription services, and more.

## Project Overview

The **Persian Whisper Speech Recognition** application allows users to upload audio files and receive transcriptions in real-time. Built using the Whisper model from Hugging Face's Transformers library, it offers a user-friendly interface powered by Gradio.

## Challenges Solved

1. **Tokenization**: Implemented a tokenizer that efficiently converts audio inputs into text format suitable for processing by the Whisper model.
2. **Audio Format Support**: Enabled support for various audio formats, including .ogg, .wav, and .mp3, to ensure a wide range of usability.
3. **Real-time Transcription**: Developed an interactive web app that transcribes audio in real-time, allowing users to see immediate results.
4. **User Interface**: Created an intuitive user interface using Gradio, making it accessible for users without technical backgrounds.

## Features

- Upload audio files in various formats (e.g., .ogg, .wav, .mp3).
- Transcribe Persian speech into text.
- Download the transcription as a .txt file.

## Requirements

To run this project, you'll need the following dependencies:

- Python 3.7+
- torch
- transformers
- gradio

You can install the required libraries using the following command:
```bash
pip install torch transformers gradio
```
## Usage

1. Clone this repository:

   git clone https://github.com/yourusername/persian-whisper-speech-recognition.git
   cd persian-whisper-speech-recognition

2. Run the Jupyter Notebook:

   jupyter notebook persian_whisper_speech_recognition.ipynb

3. Upload your audio file using the Gradio interface.
4. View the transcription and download it as a .txt file.

## Contributing

Contributions are welcome! If you have suggestions for improvements or features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- Hugging Face for providing the Whisper model and Transformers library.
- Gradio for the user-friendly interface framework.
