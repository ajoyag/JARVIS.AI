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

Certainly! If you want to add a prerequisite section to the README file, you can provide instructions on what users need to have installed on their systems before running the Jarvis AI. Here's how you can modify the README:

## Prerequisites

Before using JARVIS.AI, make sure you have the following prerequisites installed on your system:

other python modules in the code will be downloaded automatically when the code is running first time in ur laptop or desktop

### For Windows:

1. [Python](https://www.python.org/downloads/): Ensure that Python is installed on your system. You can download it from the official Python website.

2. [Git](https://git-scm.com/download/win): If you plan to clone the repository, you'll need Git. Download and install it from the official Git website.

### For Linux:

1. [Python](https://www.python.org/downloads/): Ensure that Python is installed on your system. You can install it using your package manager. For example, on Ubuntu, run:
    ```bash
    sudo apt-get update
    sudo apt-get install python3
    ```

2. [Git](https://git-scm.com/download/linux): If you plan to clone the repository, you'll need Git. Install it using your package manager. For example, on Ubuntu, run:
    ```bash
    sudo apt-get update
    sudo apt-get install git
    ```

3. [Pip](https://pip.pypa.io/en/stable/installation/): Ensure you have `pip` installed, Python's package installer. You can install it using your package manager.


## Installation

To manually install the required modules, you can use the following commands:

```bash
$pip install pyttsx3
$pip install SpeechRecognition
$pip install pyaudio
$pip install wikipedia
```

For the standard modules (datetime, webbrowser, os), no separate installation is needed.

## Usage

### Windows

1.Clone this repository to your local machine.
  OR
  Download the Repository as zip file.

2.Extract the Zip File and Open the jarvis.py file in your desired code space application.

Modify the code to include your pre-programmed sentences.

3.Run the script and u are good to go

### Linux

1.Clone this repository to your local machine.

5.Locate to the folder

```bash
cd JARVIS.AI
```

4.If you encounter issues in auto-installing, it might be due to missing dependencies.In that case,

```bash
pip install pyttsx3
pip install SpeechRecognition
pip install pyaudio
pip install wikipedia
```

6.Run the script using the command:

```bash
python jarvis.py
```
