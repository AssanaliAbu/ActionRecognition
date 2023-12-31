# Skeleton-based Human Action Recognition
Training and evaluating **DD-Net (1D CNN)** and **Transformer** models on 2 different video datasets KTH and JHMDB. 

Used pose recognition tools : **Mediapipe, HRNet**.

Accieved accuracy: **93%** (KTH), **85%**(JHMDB). 

Also testing the Flower federated learning framework which allows to concurrently train a model using more than 1 device and share  weights between devices.

Below is the **Mediapipe** pose estimation of a boxing video sample in the KTH dataset. The pose keypoints (coordinates) are then used as a training data.

![](https://github.com/AssanaliAbu/ActionRecognition/blob/main/ezgif.com-crop.gif)
