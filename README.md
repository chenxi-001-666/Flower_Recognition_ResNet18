# Flower Recognition System based on ResNet-18
# 基于 ResNet-18 的花卉识别系统

## 1. Project Overview | 项目简介
This project is a deep learning image classification system based on **PyTorch**. It utilizes the **ResNet-18** architecture and **Transfer Learning** to recognize 102 different species of flowers from the Oxford Flowers 102 dataset.
本项目是一个基于 **PyTorch** 的深度学习图像分类系统。它利用 **ResNet-18** 架构和**迁移学习**技术，识别来自 Oxford Flowers 102 数据集的 102 种不同花卉。

## 2. Key Features | 核心功能
* **Transfer Learning**: Fine-tuned a pre-trained ResNet-18 model for high accuracy in a short time.
    **迁移学习**：微调预训练的 ResNet-18 模型，在短时间内实现高准确率。
* **Data Augmentation**: Used random cropping, flipping, and normalization to improve model generalization.
    **数据增强**：使用随机裁剪、翻转和归一化技术提高模型的泛化能力。
* **Visualization**: Includes training loss/accuracy curves and real-time prediction visualization.
    **可视化**：包含训练损失/准确率曲线以及实时预测结果展示。
* **Custom Inference**: Supports predicting custom flower images uploaded by the user.
    **自定义推理**：支持识别用户上传的本地花卉图片。

## 3. Performance | 训练表现
* **Epochs**: 10
* **Final Accuracy**: ~95%+ (Training Set)
* **Training Time**: ~5 mins per epoch (on local CPU)
* **训练轮数**：10 轮
* **最终准确率**：训练集约 95% 以上
* **训练耗时**：每轮约 5 分钟

## 4. How to Run | 如何运行

### Prerequisites | 环境依赖
* Python 3.10+
* PyTorch, Torchvision
* Matplotlib, Pillow, Scipy

### Installation | 安装步骤
1. Clone the repository | 克隆仓库:
   ```bash
   git clone [https://github.com/你的用户名/Flower_Recognition_ResNet18.git](https://github.com/你的用户名/Flower_Recognition_ResNet18.git)
   cd Flower_Recognition_ResNet18\

2. Install dependencies | 安装依赖:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the training script | 运行训练脚本:
    run the jupyter notebook file

4. Directory Structure | 目录结构
```
.
├── data/               # Dataset folder (Git ignored) | 数据集文件夹
├── notebook.ipynb      # Main training & inference code | 主程序代码
├── flower_to_name.json # Flower name mapping | 花名映射表
├── README.md           # Project documentation | 项目文档
└── requirements.txt    # Library dependencies | 依赖清单
```

5. Conclusion | 结论
This project demonstrates the effectiveness of transfer learning with ResNet-18 for flower classification. It achieves high accuracy while being computationally efficient, making it suitable for real-world applications.
该项目展示了使用 ResNet-18 进行迁移学习在花卉分类中的有效性。它在保持计算效率的同时实现了高准确率，适合实际应用场景。