# Nova Voice Assistant

Nova Voice Assistant is a simple Python-based virtual assistant that can perform various tasks through voice commands. It utilizes speech recognition and text-to-speech capabilities to interact with users.

## Features

- **Voice Recognition**: Nova can understand and interpret voice commands spoken by the user.
- **Text-to-Speech**: Nova can respond to users with synthesized speech using the pyttsx3 library.
- **Web Search**: Nova can perform web searches using the default web browser.
- **System Commands**: Nova can execute system commands, open applications, and perform basic tasks such as shutting down the computer.
- **Jokes**: Nova can tell jokes using the pyjokes library to lighten the mood.
- **Time and Date**: Nova can provide current time and date information using the datetime module.

## Installation

1. Clone the repository:

    ```bash
    git clone <repository_url>
    ```

## Usage

1. Run the `nova.py` script:

    ```bash
    python nova.py
    ```

2. Once the Nova Voice Assistant is running, wait for the prompt "How can I assist you?" and then speak your command.

## Dependencies

- [pyttsx3](https://pypi.org/project/pyttsx3/): Library for text-to-speech conversion.
- [speech_recognition](https://pypi.org/project/SpeechRecognition/): Library for speech recognition.
- [pyautogui](https://pypi.org/project/PyAutoGUI/): Library for GUI automation.
- [pyjokes](https://pypi.org/project/pyjokes/): Library for fetching random jokes.
- [requests](https://pypi.org/project/requests/): Library for making HTTP requests.

## Contributing

Contributions to this project are welcome. If you encounter any bugs or have suggestions for new features, feel free to open an issue or submit a pull request.
