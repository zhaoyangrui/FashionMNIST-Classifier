FashionMNIST 服装分类器 (FashionMNIST Classifier)

这是我的深度学习入门项目！
基于 PyTorch 框架，实现了一个全连接神经网络，能够识别 10 种不同类别的服装图像。
但必须是和MNIST差不多格式的图像。

📂 项目结构

train.ipynb: 模型训练代码（包含数据加载、模型构建、训练循环）。

predict.ipynb: 加载训练好的模型，对真实图片进行预测。

fashion_model.pth: 训练好的模型权重文件。

test_image.png: 用于测试的真实图片。

🛠️ 环境依赖

Python 3.x

PyTorch

Torchvision

Matplotlib

📊 实验结果

训练轮数 (Epochs): 5

测试集准确率 (Accuracy): 约 85%

能够成功识别真实世界中的鞋子图片。

📝 学习心得

通过这个项目，我掌握了深度学习的“五步法”：

数据准备：1.定义超参数 2.定义数据转换标准 3.下载数据

模型构建：初始化模型

损失函数与优化器

训练循环：1.前向传播 2.计算损失3.清空梯度 4.反向传播 5.更新

测试与应用

Created by [zhaoyangrui] - 2025
