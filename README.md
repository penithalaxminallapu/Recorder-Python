## Audio Recorder

This Python script creates a simple graphical user interface (GUI) application for recording audio using a microphone and saving it with associated speaker name and emotion category.

### Features:

- **Recording Audio**: Allows the user to record audio through the microphone.
- **Speech Recognition**: Transcribes the recorded audio using Google Speech Recognition API and displays the text in the GUI.
- **Saving Audio**: Saves the recorded audio as a WAV file with the associated speaker's name and selected emotion category.
- **Playback**: Allows the user to play the recorded audio.
- **Emotion Selection**: Provides a dropdown menu to select the emotion category of the recorded audio.

### Requirements:

- Python 3.x
- tkinter
- speech_recognition
- pygame

### Installation:

1. **Python**: If you haven't already, [install Python](https://www.python.org/downloads/) on your system. Make sure to add Python to your system's PATH during installation.

2. **Install Required Modules**: Open your terminal or command prompt and run the following command to install the required Python modules:

    ```
    pip install tkinter speech_recognition pygame
    ```

### Emotion Categories:

- Angry
- Disgust
- Joy
- Fear
- Suspense
- Neutral
- Sad

### Notes:

- Ensure that the necessary audio files (`microphone-results.wav`, `chime1.mp3`, `chime2.mp3`, `microphone.png`, `mic.ico`) are present in the same directory as the script.
- This script utilizes Google Speech Recognition API for transcribing audio. Ensure an active internet connection for the speech recognition functionality to work properly.
- Adjustments to audio parameters such as pause threshold and energy threshold can be made within the script (`r.pause_threshold`, `r.energy_threshold`).
- The GUI is built using the tkinter library for Python.
