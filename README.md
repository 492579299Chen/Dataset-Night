# Dataset-Night

## 描述

这是一个用于武器和刀具检测的数据集，包含137,000张图像。该数据集基于Kaggle上的公开数据集，用于训练和测试计算机视觉模型，特别是目标检测任务。

## 数据集来源

原始数据集来自于：[Kaggle - Weapon and Knife Detection (137k Images)](https://www.kaggle.com/datasets/zinkzsa/weapon-and-knife-detection-137k-images)

## 数据集内容

- **图像数量**：约137,000张
- **类别**：武器和刀具
- **格式**：图像文件（JPEG/PNG等）
- **用途**：用于机器学习模型训练，特别是武器检测应用

## 使用方法

1. 下载数据集文件。
2. 解压到本地目录。
3. 使用Python库如OpenCV、TensorFlow或PyTorch加载图像进行训练。

## 示例代码

```python
import os
import cv2

# 加载图像示例
image_path = 'dataset_night/images/sample.jpg'
image = cv2.imread(image_path)
```

## 许可证

请参考原始Kaggle数据集的许可证条款。

## 贡献

欢迎提交问题和改进建议。