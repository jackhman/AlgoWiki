# 二分查找算法

作者：liweiwei1419；OneDirection9；审核：

二分查找是计算机科学中最基本、最有用的算法之一，在基础算法的学习中是非常重要的。

二分查找的最基本问题是在有序数组里查找一个特定的元素（「力扣」第 704 题：二分查找）。

## 二分查找的应用

二分查找法还可以应用在：

1、在半有序（旋转有序或者是山脉）数组里查找元素；

2、确定一个有范围的整数；

3、需要查找的目标元素满足某个特定的性质。

## 学习建议

这里写成模板只是为了方便大家学习，但是学习算法更重要的是掌握思想，这需要通过大量的练习。希望大家能够在练习的过程中，不断体会二分查找法的「减治思想」。熟悉以后，这些模板都无需且不应该记忆，编码应该是十分自然的事情。

## 二分查找的三个模板

说明：这里提供了三个模板，它们的关系是这样的：

+ 模板一：最好理解的版本，但是在刷题的过程中，需要处理一些边界的问题，一不小心容易出错；
+ 模板二：强烈推荐掌握的版本，应先理解思想，再通过实际应用去体会这个模板的细节，熟练使用以后就会觉得非常自然；
+ 模板三：可以认为是模板二的避免踩坑版本，只要深刻理解了模板二，模板三就不在话下。

实际应用中，选择最好理解的版本即可。

这里有一个提示：模板二考虑的细节最少，可以用于解决一些相对复杂的问题。缺点是：学习成本较高，初学的时候比较容易陷入死循环，建议大家通过多多使用，并且尝试 debug，找到死循环的原因，进而掌握。