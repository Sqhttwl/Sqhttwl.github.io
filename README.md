
## 图像复原


gan本质还是decode encode 结构捏

cnn做一个自编码器就可以是gan了


🚡
cnn做一个自编码器就可以是gan了，自编码器就是训练集是加入噪点的图 真值图是原图

☑️
除了Dropout之外，还有DropConnect。两者原理上类似，后者只隐藏神经元之间的连接。DropConnect也被称作Weight dropout。
总的来说，Dropout类似于机器学习中的L1、L2规则化等增加稀疏性的算法，也类似于随机森林、模拟退火之类的增加随机性的算法。
对drop方法的改进有两种明显的趋势:
           
           随机drop-> 自适应drop

           像素级drop -> 区域级drop




图信号 用拉普拉斯表示 图节点与周围的差值 来定义图信号 映射到频域之后 
（其实就是矩乘个U）中间做了一个一阶近似，然后用低通滤波器，过滤图的信号，在反映射回去


对于离散的连续型数据，其数据场景和文本分类可以说是非常类似的，
我们完全可以把离散的序列数据当作一个有顺序的句子然后基于文本分
类的方式来构建更加复杂的子模型，
例如textcnn、textrnn、textrcnn、han、attention-based modes、transformer、bert等等；
