## Programming Language
- jieba分词中的generator:
  - [Python yield 使用浅析](https://www.runoob.com/w3cnote/python-yield-used-analysis.html)
- TorchText中新的API
  - [Experimental datasets in torchtext 0.5.0 release](https://github.com/pytorch/text/issues/664)
- python中的@：
  - [谈谈python修饰器](https://www.jianshu.com/p/ab702e4d4ba7)
- PyTorch中的ganter()
  - [Stackoverflow](https://stackoverflow.com/questions/50999977/what-does-the-gather-function-do-in-pytorch-in-layman-terms)
- PyTorch内存够用但是显示out of memory：
  - 尝试一下清空缓存：torch.cuda.empty_cache()

## 待整理文章
- [Batch Normalization 与Dropout 的冲突](https://www.cnblogs.com/cbattle/p/9475361.html)
- [BN和Dropout在训练和测试时的差别](https://zhuanlan.zhihu.com/p/61725100)

## 推荐系统
- 现在的推荐系统一直推荐已经购买的商品也不是完全不可以，还是要看商品的种类，如果是零食，还是要推荐零食的，如果是汽车，就应该推荐汽车的周边了

## 系列文章(TBC)
- 机器学习中的优化方法：[ref](https://blog.csdn.net/sunflower_sara/article/details/100558156)
- 从EM到CRF
- Boost系列
- github使用
- Leetcode系列
- 推荐系统handbook

## 杂感
- word embedding很多还只是“语义相近”，一些从属信息怎么解决呢？怎么知道自动知道“水果”和“苹果”的关系呢？生成对抗？多种任务自编码？那么编码完又如何把特定的信息提取出来呢？
- CR中的mention还是非常低效的枚举，更应该让神经网络进行自动分辨，但是mention的嵌套问题如何解决呢？NER中的模型都发展到什么程度了？
- 10 * 10 的全连接，要100个参数，10 * 2+2 * 10的全连接，要40个参数，这两个网络的表达能力一样么？
- 突发奇想，然后发现，晚了两年。[LINK](https://openreview.net/forum?id=B1Yy1BxCZ)
- 能否将电流/水流模型的一些特征融入到网络呢？
- 啊！音乐！音乐！音乐响起来，烦躁的心就静了下来，就能安心学习了（2020/04/23）
- 为什么不弄一个中国版本的piazza呢
- 一段神奇的代码：window.videojs.getPlayers().html5player.children_.filter(ele => ele.getAttribute && ele.getAttribute('id') === 'html5player_html5_api')[0].playbackRate=2

## 《深度学习》要点备忘
- 平方L2范数容易求导，但是在原点附近增长缓慢；当机器学习问题中零和非零元素之间的差异非常重要时，通常会使用L1范数；L1范数经常作为表示非零元素数目的替代函数。
- 并非所有的对角矩阵都是方阵。长方形的矩阵也有可能是对角矩阵。
- 当某些不依赖参数顺序的双参数函数生成元素时，对称矩阵经常会出现。
- 正交矩阵受到关注是因为求逆计算代价小。我们需要注意正交矩阵的定义。违反直觉的是，正交矩阵的行向量不仅是正交的，还是标准正交的。对于行向量或列向量互相正交但不是标准正交的矩阵，没有对应的专有术语。
- 特征分解可以帮助我们分析矩阵的特定性质，就像质因数分解有助于我们理解整数。


-----------------------------------------------------------------------------------------

<div style="text-align:center;">
This page maintained by @ <a href="https://dasepeng.github.io/">DaSEPeng</a>, 	
<a href="https://github.com/DaSEPeng/Miscellaneous-Notes/">View on GitHub</a>
</div>
