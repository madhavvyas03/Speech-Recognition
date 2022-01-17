<h1 align = "center"> Speech Recognition in Python </h1>


Python-Speech-Recognition
---------------------------

This repository of basic examples on performing Speech Recognitionin Python using Google Speech Recognition Engine.

## Dependancies

Now you would need to Install all the Dependecies to begin running
playing the Examples 

Linux users  
----------

```bash
 
$ pip3 install pydub
$ pip3 install PyAudio
$ pip3 install SpeechRecognition
```

Window users
-----------

```bash 
$ pip install pydub
$ pip install PyAudio
$ pip install SpeechRecognition
```

Once everything is cleary installed , you're now ready to run the above examples 

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
Madhav 2020310