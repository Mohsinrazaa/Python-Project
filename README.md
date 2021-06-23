# Python-Project
This is mini project for class library code in python

* Create a library class
* display book
* lend book - (who owns the book if not present)
* add book
* return book

# Python-AI-Virtual-Assistant
## Project description

* **pyttsx3**

pyttsx3 is a text-to-speech conversion library in Python. Unlike alternative libraries, it works offline, and is compatible with both Python 2 and 3

* Installation

`pip install pyttsx3`

If you recieve errors such as No module named win32com.client, No module named `win32`, or No module named `win32api`, you will need to additionally install `pypiwin32`.

* **Usage :**

`import pyttsx3
engine = pyttsx3.init()
engine.say("I will speak this text")
engine.runAndWait()`

* **speech_recognition**
 
8 Library for performing speech recognition, with support for several engines and APIs, online and offline.

* Installation
 
`pip install SpeechRecognition`

* **Usage :**

`import speech_recognition as sr`
`engine = pyttsx3.init('sapi5')`
`voices = engine.getProperty('voices')`
`engine.setProperty('voice', voices[0].id)`
`Recognize speech input from the microphone`
