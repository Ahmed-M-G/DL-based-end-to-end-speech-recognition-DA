# Deep_learning_based-end-to-end-speech-recognition
 
 The goal of this assignment is to get familiar with applications that require speech data as input.

We would be using the torchaudio library (pip install torchaudio==0.11.0), please carefull read this tutorial https://pytorch.org/tutorials/intermediate/speech_recognition_pipeline_tutorial.html

Next, we would ask you to perform similar analysis on a speech dataset, i.e., speechdata.zip. Unzip this folder, you would see a folder named wavs, and a file called "labels.csv", containing annotated transcripts, including the files in the wavs folder (you have more labels in labels.csv). This dataset is selected from https://keithito.com/LJ-Speech-Dataset/, a famous speech-based application benchmark.

General torchaudio tutorials: https://pytorch.org/tutorials/index.html

## Task 1: Basic data exploration
 Select one randomly sampled wav file in the given folder, perform the following analysis:

  - Print the shape of the picked waveform

  - Print the sample rate of the waveform.

  - Visualize the waveform using matplotlib

  - Create the spectrogram representation of the picked waveform and visualize it.

  - Create the MFCC representation of the picked waveform and visualize it.

 Reference: https://www.kaggle.com/code/davids1992/speech-representation-and-data-exploration/notebook
