# 神经机器翻译

## 任务

简单的神经机器翻译(利用Seq2Seq with Luong Attention)

英文 -> 中文

项目地址: [stfromnjust/nlp-task (github.com)](https://github.com/stfromnjust/nlp-task)

## 环境

| 语言     | **Python  3.7**                    |
| -------- | ---------------------------------- |
| 平台     | Google Colab Pro(Jupyter NoteBook) |
| 操作系统 | Linux Ubuntu(Colab)                |
| GPU      | Tesla P100 PCIe 16GB               |
| 主要框架 | PyTorch                            |

## 目录

* cmn-eng.zip    数据集, 前21622条为训练集, 后3196条为测试集

* Seq2SeqForTranslation_dot.ipynb    使用dot计算注意力 notebook

* Seq2SeqForTranslation_general.ipynb    使用general计算注意力 notebook

* Seq2SeqForTranslation_concat.ipynb    使用concat计算注意力 notebook

  (Open in Colab可直接运行代码)
* simheittf.zip    matplotlib使用中文字体

## 效果展示

<img src="https://i.loli.net/2021/06/08/wJhdrZpbMYFRmPH.png" alt="120.png" style="zoom:67%;" />
