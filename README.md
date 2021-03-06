## Energy Conservation in WSN Using Deep Learning (Sparse Autoencoder)

The energy in wireless sensor networks is considered a scarce commodity, especially in scenarios where it is difficult or impossible to provide supplementary energy sources once the initially available energy is used up. Even in cases where energy harvesting is feasible, effective energy utilization is still a crucial step for prolonging the network lifetime. Enhancement of life-time through efficient energy management is one of the essential ingredients underlining the design of any credible wireless sensor network.

I have used in-depth learning to manage energy consumption in wireless sensor networks. In this work, I used AutoEncodr to reduce the size of the recorded data from the environment. The data is then encrypted by the encoder and then decoded at the sink by the decoder.

## The Dataset
This dataset contains tree observations from four areas of the Roosevelt National Forest in Colorado. All observations are cartographic variables (no remote sensing) from 30 meter x 30 meter sections of forest. There are over half a million measurements total!
This dataset includes information on tree type, shadow coverage, distance to nearby landmarks (roads etcetera), soil type, and local topography. The dataset that can be downloaded from this [Kaggle link](https://www.kaggle.com/uciml/forest-cover-type-dataset)

## Deep learning model for power management in wireless sensor networks

![GitHub Logo](https://github.com/khaniamir/Energy-Conservation-in-WSN-Using-Deep-Learning-Sparse-Autoencoder-/blob/master/model.png)

## Test and Train Accuracy
![GitHub Logo](https://github.com/khaniamir/Energy-Conservation-in-WSN-Using-Deep-Learning-Sparse-Autoencoder-/blob/master/test%20acc.png)

I trained the model 800 epoch. And we got the rebuilding accuracy of 71.1. You can do 10,000 training epoch and achieve 95 reconstruction accuracy.

I used colab for training. You can use [link](https://colab.research.google.com/drive/1ZJY8UhbpFyvnxvGz3-2X6XSspCaQHHBH#scrollTo=rPmgir8isi5b) to access the code at colab. And make the model stronger.
