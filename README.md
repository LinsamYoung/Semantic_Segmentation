# Semantic Segmentation 基于改进的ResNet-U-Net

大学牲的CV课程实验🥲，基于ResNet改进U-Net，深度监督、融合注意力机制和ASPP模块，实现多类别语义分割。

*As a student,it's my CV course experiment 🥲, based on ResNet to improve U-Net, in-depth supervision, integration of attention mechanism and ASPP module, to achieve multi-category semantic segmentation.*

## 特点 *feature*

- 基于ResNet的编码器，增强特征提取能力

*ResNet-based encoder enhances feature extraction ability*
- 引入注意力机制，聚焦重要特征区域

*Introduce attention mechanisms and focus on important feature areas*
- 集成ASPP模块，提升多尺度目标处理能力

*Integrate ASPP modules to improve multi-scale target processing ability*
- 深度监督，学习多层次特征

*In-depth supervision, learning multi-level characteristics*
- 图像增强
*Image enhancement*


## 文件结构 *Files*
```
├── ResNet_Semantic_Segmentation.ipynb   # 主代码文件，包含模型构建与训练流程
├── voc-pascal-2012-segmentation         # 数据集文件夹
│     ├── JPEGImages                     # 数据集图片文件夹
      ├── mask                           # mask图片文件夹
      ├── train.txt                      # 训练集索引
      ├── valid.txt                      # 验证集索引
├── README.md                            # 项目说明文档
└── best.pth                             # 模型                           
```

## 大致网络结构 *Rough network structure*
![](nn.png)


## 成果demo
*训练50次*
!['训练50次'loss和dice sorce'](graph.png)

*训练100次*
!['训练100次loss和dice sorce'](graph100.png)

![demo](valid.png)




## 环境依赖 *Environment*

- Python 3.x
- Jupyter Notebook
- PyTorch >= 1.7
- torchvision
- numpy
- matplotlib
- ...


