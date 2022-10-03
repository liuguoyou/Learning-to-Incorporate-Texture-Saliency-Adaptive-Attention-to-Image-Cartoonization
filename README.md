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
## 1. VGG19 model file ##
This model requires VGG19 model file for both training and inference (testing). The link to download VGG19 file is: <br> <https://drive.google.com/drive/folders/1LrQi-oJMqmE1--VjU8r03OEJd6XM4thc> <br>
Put the downloaded vgg19.npy file into **vgg19_weight** directory for training or inference.
## 2. Pretrained models ##
The pretrained models of different cartoon styles including "The Wind Rises" (TWR), "Dragon Ball" (DB), and "Crayon Shin-chan" (CSC) can be downloaded from <https://drive.google.com/drive/folders/1xtMNvpk7OonNbK-ZjINRSXyq0wYiAF40>. The checkpoint folders corresponding to different cartoon styles are: <br>
|  Styles   | Checkpoint folder names  |
|  -------------  | -------------  |
| TWR  | AnimeStyle_TWR_g300.0_d300.0_con1.5_color15.0_tv1.0 |
| DB  | AnimeStyle_DB_g300.0_d300.0_con2.5_color15.0_tv1.5 |
| CSC  | AnimeStyle_CSC_g300.0_d300.0_con1.5_color15.0_tv1.0 |

To use these pretrained models for direct inference (testing), put these checkpoint folders into **checkpoint** directory.