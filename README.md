# DeepLabV3Plus_different_encoders_pytorch
DeepLabV3Plus is a state-of-the-art semantic segmentation model that excels in accurately segmenting objects at multiple scales. <br>
[(paper link)]((https://arxiv.org/abs/1802.02611)) <br>
<br> 
It has an encoder-decoder structure where any Deep CNN can be used as an intermediate encoder. Here, I have tried adding deep CNNs like ResNet50 and EfficientNet B6 (i will add more in future). <br>
<a href="url"><img src="https://github.com/iN8mare/DeepLabV3Plus_different_encoders_pytorch/assets/120567183/52ba97d2-f68b-4685-851a-2aae946eb1a9" align="centre" height="256" width="720" ></a> <br>
source : [Medium article]([url](https://sh-tsang.medium.com/review-deeplabv3-atrous-separable-convolution-semantic-segmentation-a625f6e83b90))
<br><br>
As shown in figure, high level features extracted from Deep CNN were fed to the remaining layers of encoder and low level features were fed to the decoder. <br>
The output from the model is a binary image but the model hasn't been trained so the output will not give segmented image of input. <br>
The goal of project is to show how different encoders can be added and the entire network can be modified easily for research purposes. <br>

Connect with me : [LinkedIn]([url](https://www.linkedin.com/in/rishabh-sabharwal-a129b41ba/)https://www.linkedin.com/in/rishabh-sabharwal-a129b41ba/)
