# ML-Project----Facial-Emotion-Recognition
### ABSTRACT :
###### An image gradient based approach is used for recognizing facial emotions corresponding
###### to each of the six basic human emotions. Each pixel of an image has been taken and their
###### corresponding image gradient value and the angle between their vertical and horizontal
###### component are calculated, using the Sobel operator. Then histogram stretching has been
###### done based on the intervals of the angle and image gradient magnitudes. The extracted
###### histogram has been used as a feature for our Machine Learning models. Further, standard
###### ML classifiers has been applied and their training and test accuracy are checked. Each
###### image is then divided into 4 parts to capture the local information and the same process
###### is repeated. Similarly, local information and global information are combined to form one
###### single concatenated histogram which is again treated as a feature. All the accuracy are
###### compared and references are drawn as to which model classifies the human emotions the
###### best, for each of the three cases. Furthermore, CNN has been used for image classification
###### and its accuracy has been compared with the standard ML classifiers.To test the efficiency
###### of the proposed approach, we have experimented on FER 2013 data set.
