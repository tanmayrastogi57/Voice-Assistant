# Speech-to-Text and AI Response Generator

This project integrates speech recognition, text-to-speech, and a generative AI model to create an interactive voice assistant. The assistant listens to user questions, generates AI-based responses, and speaks the answers back to the user.

## Features

- **Speech Recognition**: Converts spoken language into text using Google Web Speech API.
- **Generative AI**: Generates responses to user queries using Google's Generative AI model.
- **Text-to-Speech**: Converts the AI-generated text responses back into speech.

## Prerequisites

- Python 3.x
- [google-generativeai](https://pypi.org/project/google-generativeai/)
- [pyttsx3](https://pypi.org/project/pyttsx3/)
- [speech_recognition](https://pypi.org/project/SpeechRecognition/)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/speech-to-text-ai.git
    cd speech-to-text-ai
    ```

2. Install the required packages:
    ```bash
    pip install google-generativeai pyttsx3 SpeechRecognition
    ```

3. Configure the Google API key:
   Replace the placeholder `GOOGLE_API_KEY` in the script with your actual Google API key.

## Usage

1. Run the main script:
    ```bash
    python main.py
    ```

2. Speak your question into the microphone when prompted. The AI will process your question and respond audibly.

## Code Overview

- `generate_response(question)`: Generates a response for the given question using the generative AI model.
- `speech_to_text()`: Captures and converts speech to text using the microphone and Google Web Speech API.
- `AI(response)`: Converts text responses to speech using pyttsx3.
- `main()`: The main loop that continuously listens for user input, generates responses, and speaks them back to the user.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Google Generative AI](https://developers.google.com/generative-ai)
- [pyttsx3](https://github.com/nateshmbhat/pyttsx3)
- [SpeechRecognition](https://github.com/Uberi/speech_recognition)

Feel free to contribute to this project by submitting issues or pull requests!
