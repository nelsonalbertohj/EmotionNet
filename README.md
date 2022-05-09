# EmotionNet: Emotion Recognition Based on Multimodal Physiological Signals Through Deep Learning

![alt text](https://github.com/nelsonalbertohj/EmotionNet/blob/main/Project%20Images/Project_diagram.png?raw=true)

# Abstract
The field of emotion recognition aims to automatically quantify human emotional states based on behavioural and physiological data. Interesting applications of this area of study include the early detection and relieve of strong negative emotions, and the diagnosis of neurological disorders that affect people's emotional well being. Much of the current emotion recognition research aims to differentiate from 3 emotional states, positive, negative, or neutral, and further work is needed to classify more nuanced emotional states. In addition, there is growing interest for classifying emotions based on wearable devices that are available beyond laboratory settings. My research develops a convolutional neural network algorithm that is able to estimates participants' ratings of 9 distinct emotions based on EEG, EDA, and BVP data collected with commercial-grade devices. My algorithm performs a regression estimate that is within 0.30 of participants' self-reported emotions on a 0 to 4 scale.

# Research Report
The following research report was submitted as part of the final project in 18.065 Matrix Methods in Data Analysis, Signal Processing, and Machine Learning. [EmotionNet Research Report](https://github.com/nelsonalbertohj/EmotionNet/blob/main/EmotionNet_final_report.pdf).

Please, if using the algorithms developed in this repository, please cite me as:

```
@inproceedings
{nhemotionnet,
    author = {Hidalgo, Nelson},
    year = {2022},
    title = {Emotion Recognition Based on Multimodal Physiological Signals Through Deep Learning},
    booktitle = {Preprint}
}
```

# Environment Configuration
The following dependencies versions were used in this project:

```
tensorflow                         2.8.0
Python                             3.9.12
```