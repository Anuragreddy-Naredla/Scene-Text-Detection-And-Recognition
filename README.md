# Scene-Text-Detection-And-Recognition
![image](https://user-images.githubusercontent.com/69776971/124375846-c6615b00-dcc1-11eb-854b-1cc3f6c3fb2d.png)

## Implementing the research paper from scratch:
https://arxiv.org/pdf/1811.04256.pdf
## Buiness Problem
The main objective of this Problem Statement is to detect the text from image and drawing a bounding box to that text and then recognize that text from bounding box we can also convert the text into another language. It mainly consists of three parts,
1. Text Detector:Text Detector says that the which detects the text from images by drawing the bounding box.
2. Text Recognizer:Text Recognizer says that the which recognize the text from bounding box.
3. Text Language Translation:Text Language Translation says that the recognized text can be translated into any other language.
## Data
Syntext data:
https://www.robots.ox.ac.uk/~vgg/data/scenetext/

ICDAR2015:
https://rrc.cvc.uab.es/?ch=4&com=downloads
## Text Detection:
for text detection i used EAST architecture.
![image](https://user-images.githubusercontent.com/69776971/124375987-6c14ca00-dcc2-11eb-991b-d6b578394419.png)
## Text Recognition:
implemented the CRNN(Convolutional Recurrent Neural Network) architecture.

## architectures

I tried with 3 architectures
a.VGG16
b.VGG19
c.Resnet50

i found that resnet50 model is performing very well compared to vgg16 and vgg19 

Deployment:

1.Deployed used streamlit and ngrok.

Demo results youtube :https://www.youtube.com/watch?v=YqE7WiIMx2k

Please check my blog:
https://anuragreddy1241.medium.com/scene-text-detection-and-recognition-197297ab368f
