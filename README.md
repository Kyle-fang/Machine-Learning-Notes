# Machine-Learning-Notes
# 李宏毅机器学习
![]()
# Supervised Learning（监督学习）
## 1.Regression(回归)
   - The output of the target function F is "scalar(数值)"
   - 应用：
      - Stock market forecast（股市预测）
      - Self-driving Car（自动驾驶）
      - Recommendation（推荐）
   - 例：根据受教育水平，年龄和居住地来预测一个人的年收入
### &emsp;Example Application(应用范例)
   - step1·Model：A set of function
      - Linear model
      - Nonlinear model
   - step2·Goodness of Function（好的功能）
      - Training Data
      - Loss function(损失函数): input:a function,output:how bad it is
![](loss_function.jpg)
   - step3·Best Function: Pick the "Best" function
      - Dradient Descent(梯度下降)：找出使L(f)最小的function
         - （Randomly）Pick 按initial value
         - 计算损失函数在某点的微分（偏微分），判断往哪边能使L(f)减小
         - Learning rate（学习速率）：移动的步长
      - Local minima(局部最小值)
      - Global minima(全局最小值)
   - generalization(一般化)
      - Testing Data（测试function）
## 2.Classification(分类)
### &emsp;(1)Binary(二元)Classification
   - &emsp;&emsp;如垃圾邮件分类
### &emsp;(2)Multi-class(多元) Classification
   - &emsp;&emsp;新闻文章类型的分类
### &emsp;Linear Model
### &emsp;Non-linear Model
#### &emsp;&emsp;Deep Learning
#### &emsp;&emsp;SVM, decision tre, K-NN
## Structured Learning（结构化学习）
# Semi-supervised Learning（半监督学习）
# Unsupervised Learning（无监督学习）
# Transfer Learning（迁移学习）
