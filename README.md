# Fer 2013 : Emotion Detection models
## Facial Expression Recognition based on Convolutional Neural Networks



Dataset : [FER2013](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data/)


There are 3 models in this project:
- [Xception](https://arxiv.org/pdf/1610.02357.pdf)

 ![](https://www.researchgate.net/publication/342580102/figure/fig3/AS:908305815830530@1593568390179/Schematic-diagram-of-the-Xception-model.png)

- [DeXpression](https://arxiv.org/pdf/1509.05371.pdf)

![](https://qph.fs.quoracdn.net/main-qimg-252e5047af30f8ea18def43bb35dbf41.webp)
- [CNN model inspired by Goodfellow, I.J., et.al. (2013).](https://arxiv.org/pdf/1307.0414.pdf)

![](https://raw.githubusercontent.com/NJNischal/Facial-Expression-Recognition-with-CNNs/9999cbdaa55542e86e11a9e129bafcfb96bd0e60/model.png)


## Evaluation
The models were trained for 50 epochs each.

![](https://github.com/Anis-Bouaziz/FER2013-Emotion-Recognition/blob/master/Images/plots.png)

| Model | Accuracy | Number of Parameters |
| ---------- | ---------- | ---------- |
| Xception |0.6505 |3,989,975 |
| DeXpression | 0.5687 |693,991 |
| Simple CNN | 0.6619 |4,049,671 |

Kaggle Notebook : [kaggle](https://www.kaggle.com/anisbouaziz/emotion-recognition/notebook)