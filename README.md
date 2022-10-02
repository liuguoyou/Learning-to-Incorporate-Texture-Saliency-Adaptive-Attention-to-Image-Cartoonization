# Learning-to-Incorporate-Texture-Saliency-Adaptive-Attention-to-Image-Cartoonization
Code of paper "Learning to Incorporate Texture Saliency Adaptive Attention to Image Cartoonization", ICML 2022.

# Introduction
This is the code of the image cartoonization method proposed in paper "Learning to Incorporate Texture Saliency Adaptive Attention to Image Cartoonization" <https://proceedings.mlr.press/v162/gao22k/gao22k.pdf>. Below is the overall model architecture, please refer to the paper for more technical details.
<image src="images/architecture.jpg">

# Required environment
Tensorflow 1.X <br>
Numpy <br>
Opencv-python <br>
Pillow (PIL) <br>
# Required files and pretrained models
This model requires VGG19 model file for both training and inference. The link to download VGG19 file is: <br> <https://drive.google.com/drive/folders/1LrQi-oJMqmE1--VjU8r03OEJd6XM4thc> <br>
Put the downloaded vgg19.npy file into **vgg19_weight** directory for training or inference.
