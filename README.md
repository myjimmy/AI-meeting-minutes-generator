# AI-meeting-minutes-generator
This app generates automatically the meeting minutes from an audio file with Whisper and GPT-4.

## What is this?
In this app, we'll harness the power of **[OpenAI](https://openai.com/)**'s **Whisper** and **GPT-4** models to develop an automated meeting minutes generator.<br/>
This application transcribes audio from a meeting, provides a summary of the discussion, extracts key points and action items, and performs a sentiment analysis.

## Where is this app from?
This app iis from the tutorial **["Creating an automated meeting minutes generator with Whisper and GPT-4"](https://platform.openai.com/docs/tutorials/meeting-minutes/creating-an-automated-meeting-minutes-generator-with-whisper-and-gpt-4)** at the [OpenAI document](https://platform.openai.com/docs/) site.

## Sample Audio Clip
The sample audio clip used in this app is downloaded from the following URL provided in the tutorial:
https://cdn.openai.com/API/docs/images/tutorials/meeting-minutes/EarningsCall.wav

## How To Run
It should set up the Python following the instructions given at https://platform.openai.com/docs/quickstart/quickstart-language-selection.
Also, please run the following commands to install the necessasry 3d party libraries:
```
$ pip install openai
$ pip install python-docx
```

And then, please run the following command to execute this app:
```
$ cd source
$ python generator.py
```
