# ML-Fusion

Project realised with Francesca Stefano for the 3D perception and learning based data fusion course for the second year of the master's degree programme.

Pytorch implementation of the paper for ML sensor fusion of different sensor for classication map.
Single-stream CNNs are commonly used in multi-source remote sensing data fusion. In this project we
propose a strategy that enables single-stream CNNs to approximate multi-stream models using group
convolution. The proposed method is applied to ResNetv18, ResNetv50 and tb CNN, and evaluated
on MUUFL data sets, obtaining good results. On a practical level, data from LiDAR and HS were
merged thanks to the Neural Network to obtain classification maps based on the different predefined
categories of the dataset.
