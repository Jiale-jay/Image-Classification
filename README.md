# Image-Classification
VGG/ResNet/GoogLeNet

An Image Classification task using 3 classical convolutional neural networks.
These three classical neural networks have been integrated into Tensorflow 2.0 Core - Keras applications, and can be called directly with a single function. Therefore, it is not too difficult to use these basic algorithms to understand them in principle.

Data
https://www.kaggle.com/datasets/bahadoreizadkhah/face-mask-types-dataset
This dataset contains images of several different types of masks as well as images without masks, categorised directly by folder.
This dataset can be used to assist the Visual Security System in detecting and classifying pedestrians wearing masks.

VGG16, resnet, and Inception v3 are used as base networks to construct classifiers and evaluate their classification performance (accuracy) and inference performance (consumption of computer resources).

Improvement: for image pre-processing and data enhancement, more methods can be considered, such as random cropping, adjusting brightness or contrast, etc.
For the results of the classification model, the visualisation of the confusion matrix can be used to see more intuitively the classification effect of the model, the
One can try to fine-tune the model by unfreezing some convolutional layers for retraining, which may give better results.


# Image-Classification
VGG/ResNet/GoogLeNet

使用3个经典的卷积神经网络完成一个Image Classification的任务。
这三个经典神经网络都已经被集成在Tensorflow 2.0 Core - Keras applications中，能够通过一行function直接调用。因而使用上不会有太大难度，要从原理上理解这些基础算法。

Data
https://www.kaggle.com/datasets/bahadoreizadkhah/face-mask-types-dataset
该数据集包含几种不同类型的口罩以及未佩戴口罩的图片，直接按照文件夹进行分类。
该数据集能够辅助“视觉安防系统”对行人进行口罩佩戴的侦测和分类。

分别使用VGG16、resnet、Inception v3作为基网络，构建分类器，评估其分类性能（准确度）推理性能（对计算机资源的消耗）。

改进：对于图像的预处理和数据增强，可以考虑用更多的方法，比如随机剪裁、调整亮度或对比度等
对于分类模型的结果，可以通过可视化混淆矩阵来更直观地看出模型的分类效果，
可以尝试对模型进行微调，解冻一些卷积层进行再训练，可能会得到更好的结果。

