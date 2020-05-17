# Ball Action Recognition

A multi-model pipeline that aims to recognize Pass, OutofBounds and Possession Ball States in long-shot match footage.

Implementation of the DeepBall ball detector in Keras and Tensorflow.
DeepBall paper is found here - https://arxiv.org/pdf/1902.07304.pdf

The dataset used to train is the same as the paper above - https://pspagnolo.jimdofree.com/download/

A pre-trained Mask-RCNN model is used to detect players.
Port used is found here - https://github.com/matterport/Mask_RCNN


### Demo of DeepBall ball-tracking
![ball-trackingdemo](DeepBall/demo/S6ball.gif)


### Demo of Pass, Possession and OutofBounds Ball State Recognition
![pass-trackingdemo](DeepBall/demo/S6pass.gif)
