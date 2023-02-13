# 基础作业
使用MMSegmentation，在自己的数据集上，训练语义分割模型。

使用Labelme、LabelU等数据标注工具，标注多类别语义分割数据集，并保存为指定的格式。

数据集整理
划分训练集、测试集

使用MMSegmentation训练语义分割模型
在MMSegmentation中，指定预训练模型，配置config文件，修改类别数、学习率。

用训练得到的模型预测
获得测试集图片或新图片的语义分割预测结果，对结果进行可视化和后处理。

在测试集上评估算法的速度和精度性能
# 数据集
组织病理切片小鼠肾小球：https://zihao-openmmlab.obs.cn-east-3.myhuaweicloud.com/20230130-mmseg/dataset/Glomeruli-dataset.zip
# 实验设备
NVIDIA GTX 3090
# 混淆矩阵

[混淆矩阵.pdf](https://github.com/linxin1998/openmmlabAI-3/files/10721941/default.pdf)
# 预测结果图
![image](https://user-images.githubusercontent.com/83444163/218452730-9807f631-688d-4d05-b374-2425eb6c4c03.png)
