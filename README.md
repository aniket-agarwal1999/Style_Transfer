<h1> Neural Style Transfer </h1>

Here I have implemented the paper by Gatys et al. [here](https://arxiv.org/abs/1508.06576) in pytorch.

This is done as a part of the CS231n course assignments.

Blog for further understanding [here](https://medium.com/artists-and-machine-intelligence/neural-artistic-style-transfer-a-comprehensive-look-f54d8649c199)

<h2> Sample image: </h2> 
<p float="left">
  <img src="sample_images/simple.png" width="300" />
  <img src="sample_images/styled.png" width="300" /> 
</p>

<h3>General Information</h3>
This project has been performed using SqueezeNet rather than the normal norm of using VGG16. I experimented on both of them and found VGG to be way more heavier than SqueezeNet and also not converging 5 times more iterations than this. Also when viewed the texture(basically, style) from both the nets using a different net, it was found that VGG showed much arbitrary textures as compared to SqueezeNet, which may be due to the fact of VGG recognizing more intricate features of the style image which is of the rather lesser importance in case of style transfer, but of much more importance in the case of DeepDream.:smile:
