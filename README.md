# Trigger word detection using GRU in RNN
Trigger word detection is the technology that allows devices like Amazon Alexa, Google Home, Apple Siri, and Baidu DuerOS to wake up
upon hearing a certain word.

In this project,Trigger word will be "Activate." Every time it hears "activate," it will make a "chiming" sound.
The dataset includes audio recordings which are synthesized and processed to create train/dev datasets. The RNN employed here uses a Gated Recurrent Unit(GRU) which aims to solve the vanishing gradient problem which comes with a standard recurrent neural network. GRU can also be considered as a variation on the LSTM because both are designed similarly and, in some cases, produce equally excellent results.
(This mini-project is a part of Deep Learning specialization course, dataset or any pre-trained weights/models used were provided by Coursera.)
