# 环境搭建
## Step1: 搭建python环境
1. 创建 conda 环境
```pyhton
conda create -n qml python=3.9
conda activate qml
```

2. 安装 python 环境依赖包
```
git clone XXX
cd quantumML
pip install -r requirements.txt
```

## Step2: 运行代码样例
`qcnn.ipynb` 样例代码实现了一个最简单CNN卷积核，主要涉及：1）如何将经典数据映射到量子态；2）如何构建一个Model类；3）对其进行训练


# 夏令营任务
## 任务介绍
### 1. 初级版（必做）
实现一个简单的 Quantum CNN 或者 Quantum SVM任务。下面以Quantum CNN进行任务描述：
- 搭建一个简单的经典CNN，实现Minist手写识别数据集图片分类；
- 将卷积计算过程使用量子进行表示，数据可任选2个数字即可；
- 撰写实验报告，包含：量子算法构建流程、核心模块定义、代码贴片、结果展示等。



### 2. 进阶版（可选）
可自选一个经典神经网络，对照一个经典神经网络的核心组件，自行设计完成对应的量子模块表示。
- 撰写实验报告，量子算法构建流程、核心模块定义、代码贴片、结果展示等
