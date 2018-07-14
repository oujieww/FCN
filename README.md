# FCN for semantic segmentation

This is a simple FCN[1] implementation in Pytorch. There are some differences from the original FCN:

* VGG, DenseNet, ResNet features are used
* SegNet and FCN

I haven't test the performance. 

## requirement
pytorch, [tensorboard-pytorch](https://github.com/lanpa/tensorboard-pytorch), tensorboard (for visulization)

If you don't need visulization, then delete the lines about visulization in "main.py".

## Usage
download code: ```git clone https://github.com/zengxianyu/FCN.git --recursive```

run ```main_*.py``` for training and validation

## Reference
[1] Long, Jonathan, Evan Shelhamer, and Trevor Darrell. "Fully convolutional networks for semantic segmentation." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2015.


