# Text-to-Speech-Converter
* This is a python GUI program for converting text into AI speech.
* you can enter the text into message box and click the play button for listening the text.
* you can also reset the text via reset button and also exit the window using exit button.
## Libraries Used
* I have used the basic concepts of Python, Tkinter, gTTS, playsound and os libraries to implement this.
* **_`Tkinter`_**  is a standard GUI Python library that is one of the fastest and easiest ways to build GUI applications using Tkinter.
* **_`gTTS (Google Text-to-Speech)`_**  a Python library to interface with Google Translate’s text-to-speech API. It is a very easy library that converts the text into audio.
* **_`playsound`_**  This module is used to play audio files created using gTTS.
* **_`os`_**  This module is used for using operating system dependent functionality. I have used it's "remove" method to delete the audio file after playing so that we can use the program again and again without rerunning it.
