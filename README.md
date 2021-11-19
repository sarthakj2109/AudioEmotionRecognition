# Audio Emotion Recognition
This is a Machine Learning project developed to recognize the emotion of the speaker from the audio file received. Various ML models and algorithms were trained on an audio database to solve the multi-class classification problem at hand and compared to check for best accuracy.

## Various classifiers trained
1) **Convolutional Neural Network (CNN)** [[Code1]](Audio_CNN.ipynb) [[Code2]](SpeechEmotionRecognition(Completed).ipynb)
2) **Support Vector Machines (SVM) for multi-class classification** [[Code]](SVM(Final).ipynb)
3) **Multi-layer perceptron classifer (MLP)** [[Code]](MLPClassifier(Final).ipynb)
4) **Decision Tree Classifier** [[Code]](Decision_Tree_Audio.ipynb)

### Database used
The database used is prepared by combining two of "The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)" by Livingstone & Russo licensed under CC BY-NA-SC 4.0. audio databases. [^1]

One portion consisting of emotional speech audio contains 1440 files: 60 trials per actor x 24 actors = 1440. The RAVDESS contains 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent. Speech emotions includes calm, happy, sad, angry, fearful, surprise, and disgust expressions. Each expression is produced at two levels of emotional intensity (normal, strong), with an additional neutral expression.
Similarly, the song database contains 1012 files: 44 trials per actor x 23 actors = 1012. 
More about the naming conventions and database can be found [here](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio) and [here](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-song-audio)

#### NOTE 
The best test accuracy achieved (_subject to our academic constraints and trials conducted_) was about 76% in case of CNN model. 

[^1]:https://doi.org/10.1371/journal.pone.0196391
