# Deep Convolutional Generative Adversarial Networks for Image Generation and Classification
This is a final Project for UCSD ECE285 Intro to Visual Learning. 

This work is our attempt at the implementation of https://arxiv.org/pdf/1511.06434.pdf

In this work we train a Deep Convolutional Generative Adversarial Network (DCGAN) using PyTorch to produce high quality images using unsupervised datasets. The datasets used to train the GAN are the Flickr Faces Dataset and the Oxford Pet Dataset. Then we show this DCGAN can be used as a feature extractor by using the extracted features as weights to pre-train an L2-SVM model for image classification on the COCO dataset.

This repo holds my contribution to this project code as well as the report.
