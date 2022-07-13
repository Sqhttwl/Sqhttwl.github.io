
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
