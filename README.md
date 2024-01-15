# JARVIS.AI

## Overview

Jarvis is a Python-based AI assistant that utilizes various modules to perform tasks such as text-to-speech, speech recognition, retrieving information from Wikipedia, opening web browsers, handling operating system commands, and sending emails through SMTP. This AI is designed to respond to pre-programmed sentences injected directly into the code.

## Dependencies

Jarvis relies on the following Python modules:

[pyttsx3](): A text-to-speech conversion library.
[speech_recognition](): Library for speech recognition.
[pyaudio](): Module for working with audio.
[wikipedia](): A library for accessing and parsing Wikipedia content.
datetime: Module to work with dates and times.
webbrowser: Module for displaying web-based documents.
os: Module for interacting with the operating system.
smtplib: Module for sending emails using SMTP.

## Installation
To manually install the required modules, you can use the following commands:

'''bash
$pip install pyttsx3
$pip install SpeechRecognition
$pip install pyaudio
$pip install wikipedia
'''

For the standard modules (datetime, webbrowser, os), no separate installation is needed.

## Usage

### Windows

1.Clone this repository to your local machine.
2.Open the jarvis.py file in a text editor.
3.Modify the code to include your desired pre-programmed sentences.
4.If you encounter issues installing, it might be due to missing dependencies.In that case,

'''bash
pip install pyttsx3
pip install SpeechRecognition
pip install pyaudio
pip install wikipedia
'''

5.Locate to the folder

'''bash
cd JARVIS.AI
'''

6.Run the script using the command:

'''bash
python jarvis.py
'''
