# Point_CNN

## 深度学习基础
        语义鸿沟 Semantic Gap：
        图像的底层视觉特性和高层语义概念之间的鸿沟
        相似的视觉特性，不同的语义概念 && 不相似的视觉特性，相同的语义概念
### 图像识别基本框架
        测量空间——特征空间——类别空间
                |                        |
        特征设计/学习特征   特征匹配
    全局特征提取：例如颜色，形状，纹理——>向量空间映射——>向量表示
### CNN
```
DNN全连接网络不够灵活，参数量太大 ——>CNN：局部连接—权重共享—下采样——>减少网络参数
局部连接：人眼观察的时候也是关注局部，局部移动，
权重共享：卷积层的某一个
下采样：减小分辨率
  input image——  kernel:卷积核—需要学习的对象——feature map(w*h*channel)
  
 目标检测相对于图像分类而言多了一个画框，所以损失函数要采用回归类的

```

## Ai Studio（百度）

```
wor1: Paddle架构，pyecharts图表库，python爬虫（json , re, requests）
DNN：可以认为是线性网络，对于层的节点数的设置需要满足矩阵乘法规则：MN NJ = MJ
深度网络：随着深度的增加，可以达到不同程度信息特征的学习和表达；虽然深度网络类似于黑箱操作，但在设计深度网络时应当遵循可解释的/可理解的思路

```
