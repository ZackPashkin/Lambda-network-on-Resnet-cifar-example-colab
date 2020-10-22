# Lambda-network-on-Resnet-cifar-example-colab

Author applied lambda layer to Resnet bottleneck part

+ Add comparison with default resnet18

Reference:

author LambdaResnet: [PistonY](https://github.com/PistonY) https://gist.github.com/PistonY/ad33ab9e3d5f9a6a38345eb184e68cb4 

lambda layers implementation here https://github.com/lucidrains/lambda-networks


paper:
https://openreview.net/forum?id=xTJEN-ggl1b

review on Youtube: 
https://www.youtube.com/watch?v=3qxJ2WD8p4w&t=71s





Notes:
einsum explained here: https://www.youtube.com/watch?v=pkVwUVEHmfI


Some observations:

Network summary comparison with vanilla ResNet18.Input size 3,224,224:

LambdaResnet18:

================================================================
Total params: 8,054,538
Trainable params: 8,054,538
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.57
Forward/backward pass size (MB): 247.53
Params size (MB): 30.73
Estimated Total Size (MB): 278.83
----------------------------------------------------------------

Vanilla Resnet18

================================================================
Total params: 11,181,642
Trainable params: 12,938
Non-trainable params: 11,168,704
----------------------------------------------------------------
Input size (MB): 0.57
Forward/backward pass size (MB): 62.79
Params size (MB): 42.65
Estimated Total Size (MB): 106.01
----------------------------------------------------------------
