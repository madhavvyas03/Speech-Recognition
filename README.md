<h1 align = "center"> Speech Recognition in Python </h1>


Python-Speech-Recognition
---------------------------
Created by Madhav Vyas 
This repository of basic examples on performing Speech Recognitionin Python using Google Speech Recognition Engine.

## Dependancies

You would need to Install all the Dependecies to begin running
playing the Examples 

For Window users
-----------

```bash 
$ pip install pydub
$ pip install PyAudio
$ pip install SpeechRecognition
```
Recognition From Microphone 
----------------------------


The first Example *app.py* consist of python code to perform speech recognition 
on sound that is directly fed from Microphone 

To run the Example do the following

```bash 
$ python app.py 
    Adjusting noise 
    Recording for 4 seconds
    Done recording
    Recognizing the text
    Decoded Text : Python is awesome
```

Recognition From Audio File 
-----------------------------

The second Example *app_audio.py* consist of a python code to perform speech recognition from 
sound loaded from local audio file 

To run the Example do the following 

```bash
$ python3 app_audio.py 
    Done recording
    Recognizing the text
    Decoded Text : python programming is the best of all by Jordan
```

Recognizing From Long Audio File 
-----------------------------------

Incase you have a long audio File, loading plus processing it, It takes a quite a while therefore 
the best way is to break the long audio source from file into small chunks and then performing 
speech Recognition on those chunks 

The script *long_audio.py* consist of Python demo code just to that 

To run the example do the Following 

```bash 
$ python3 app_audio.py 
    Done recording
    Recognizing the text
    Decoded Text : python programming is the best of all by Jordan
```
