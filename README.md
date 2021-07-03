# AudioClassification
## Dataset
For this project we intend to use the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) dataset. This dataset published by Livingstone and Russo (2018) on the PLOS ONE magazine, consists of 7354 audio-visual recordings of actors expressing multiple emotions. The recordings were independently rated 10 times by 247 individuals for emotion validity and they include emotions such as: calmness, happiness, sadness, anger, fear, surprise and disgust. In the context of this work, we will exclusively make use of the emotional speech audio data, discarding the songs and video footage.
## Work motivation
Using the described dataset, we will make use of two Neural Network models to try to predict the emotions expressed by the actors in each audio file. More specifically, we will make use of a Convolutional Neural Network, typically used to tackle this kind of problem (as seen on https://www.kaggle.com/uwrfkaggler/ ravdess-emotional-speech-audio/code) and compare its effectiveness on this task with that of a Recurrent Neural Network, namely a Long Short-Term Memory network.

Since sound classification tasks can be compared to image classification ones, due to the fact that the features of sound data are usually extracted into spectrograms in order to be classified, it is a common practice to use CNNs to try to predict categories from audio data, such as musical genres or animal sounds. However, in recent articles like Lezhenin et al. (2019) the authors have found good success using LSTM networks to classify sound data with an important temporal dimension, such as heartbeat patterns, environmental sounds or in this case, human speech, where there is a great, but sequential, variation in sound patterns across the spectrogram representations.
## Goals
Given this information, we have defined 5 goals for our project. Three of them being central to our work proposal and the other two of them optional, depending on the amount of time time required to perform the mandatory tasks. We divide or goals as follows:
### Main goals
- Processing audio data into suitable inputs for NN learning: during the first part of the work we aim to explore and process the audio data in order to clean it, normalize it and transform it into a suitable input format for both types of Neural Network models.
- Applying base model configurations based on bibliography: we will then make a basic network configu- ration based on bibliography analysis of classifications tasks similar to our own.
- Comparing the performance of CNN and RNN: using the defined configurations, we will proceed to com- pare the prediction performance metrics for both types of Neural Networks (CNN vs RNN), while maintaining as many parameters as possible in order to perform an unbiased comparison.

### Authors
Duarte Balata
Miguel Oliveira
