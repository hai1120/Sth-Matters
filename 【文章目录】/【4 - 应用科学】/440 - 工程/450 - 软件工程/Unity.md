# Unity
[在UE里的模型，在边缘处会有这种高亮，请问是咋实现的？在Unity里用什么方法可以实现？](https://www.zhihu.com/question/467883161/answer/1962634796)

> Author: #0-Anonymity
> Last update: [编辑于 2021-06-26]
> Link: [[高管写代码]]
> Tag: #4-世界史/4E-科学技术/2-科技 #合集/合集2-一些推荐
> 评论区:
> 泛讨论:

这个一般用的是程序烘培出来的一种bump map或者normal map。

也有的是shader直接写的。

具体到这一个，全是方块，估计是shader直接写的。

否则这贴图资源用得太浪费了。
