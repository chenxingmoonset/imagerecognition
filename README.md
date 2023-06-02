# image recognition
图片识别分类毕业设计
基于ResNet50网络结构、类AlexNet网络结构训练。
图像分类、标注、灰度化、数据增强、信息统计、尺寸归一，划分测试集与验证集。
ResNet50网络为在ImageNet上预训练的，Batch size=4，初始lr=0.003，采用Adam优化器自适应调整（衰减）学习率，损失函数采用交叉熵损失函数（Cross Entropy Loss），数据集使用继承的方法

环境配置：系统Windows10专业版，处理器Intel(R) Core(TM) i7-10510U @1.8GHz 2.30GHz，内存(RAM)8GB，显卡NVIDIA GeForce MX250，Python 3.9.13，深度学习框架Pytorch 1.10.0、torchvision 0.11.0，运行平台Jupyter Notebook。
