# RockTheBoar
Code written as part of the (Kaggle Carvana Image Masking Challenge)[https://www.kaggle.com/c/carvana-image-masking-challenge)]. The overal goal of this competition was to design an algorithm to accurately mask cars in images. Our final submission (in /tensorflow_gan) used a 12 layer autoencoder-style fully convolutional neural network - 6 convolutional layers followed by 6 deconvolutional layers. This provided a pixel-wise "probability of car" estimate. The network architecture, written in tensorflow, is given in convnet_architecture_12l.py. The training framework is in train_network.py, and the image loading functions are in input_pipeline.py. 

Authors: Donald Lee-Brown(@dleebrown)[https://github.com/dleebrown], Sinan Deger(@sinandeger)[https://github.com/sinandeger] and Nesar Ramachandra (@nesar)[https://github.com/sinandeger]
