# Facial Expression Recognition Model
This repository contains all the relevant code for the facial expression recognition model used for my 4th year honours project for the award of BSc Computing(G401). The project itself revolves around using facial expression recognition in a further application alongside mental health questionnaires and therapy sessions. The model was developed with the user of the TensorFlow deep learning framework within Jupyter notebooks.
## The Dataset
The facial expression recognition model was created with the FER-2013 dataset. The FER-2013 can be found on the Kaggle.com and is open-source for the purposes of research. The dataset consists of 35,887 images made up of facial expressions. The seven categories of expressions within the dataset are: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.
## Model Architecture 
The convolutional neural network architecture is based on a 5-layer model devised by Kim et al. This specific model architecture was chosen due to its good performance on the FER-2013 itself whilst also being a relatively shallow model with a low number of paramaters, making it suitable for use in a further application with its faster prediction times. 

The work of Kim et al can be found here: https://openaccess.thecvf.com/content_cvpr_2016_workshops/w28/papers/Kim_Fusing_Aligned_and_CVPR_2016_paper.pdf

It should also be noted that a work by Khanzada et al. was also followed as a guideline for the project model architecture. The study used the 5-layer model described by Kim et al, however the work presented their training process in a clear fashion and was thus used as a general guideline to hopefully emulate their well performing results of around 66% accuracy on the FER-2013 dataset.

The work of Khanzada et al. can be found at the following link:
https://arxiv.org/abs/2004.11823
## Model Results
The final accuracy obtained by the model within this repository was 65% on the testing dataset. 