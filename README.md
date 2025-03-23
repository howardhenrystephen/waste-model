# 基于深度学习的智能垃圾分拣研究及系统设计

**概述:**

+ **模型设计:** 基于 `CNN` 和 `Transformer` 的双分支垃圾分类模型
+ **技术框架:** 基于 `PyTorch` 深度学习框架
+ **训练环境:** 基于 `Apple M2 Pro` 芯片
+ **评估测试:** todo))
+ **后期设计:** 基于 `Vue3` 前端框架

## CNN 部分

todo)) 可能基于残差网络 `ResNet`

对数据集进行前期训练 - 双层CNN模型训练

## Transformer 部分

todo)) 对 CNN 处理后的数据再处理

## 训练数据集

**数据集链接:** [Click Me](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)

```shell
# cURL 方式下载数据集
curl -L -o ~/Downloads/garbage-classification.zip https://www.kaggle.com/api/v1/datasets/download/mostafaabla/garbage-classification
```

**数据集优势:**

This dataset has 15,150 images from 12 different classes of household garbage; paper, cardboard, biological, metal, plastic, green-glass, brown-glass, white-glass, clothes, shoes, batteries, and trash.

Garbage Recycling is a key aspect of preserving our environment. To make the recycling process possible/easier, the garbage must be sorted to groups that have similar recycling process. I found that most available data sets classify garbage into a few classes (2 to 6 classes at most). Having the ability to sort the household garbage into more classes can result in dramatically increasing the percentage of the recycled garbage.
