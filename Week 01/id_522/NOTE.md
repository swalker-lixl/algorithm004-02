# NOTE
本周先看了，LRU 的JAVA 版本，参考着写了python 版本的；

感觉就是再写一个2维 的算法，不仅要注意hash 里面的实现，还要实现双向链表。

我用了字典，一开始吧头节点和尾节点放到了hash 里面，后来发现可以放到外边，不进入hash

这样，字典的长度，就是LRU 的长度了。


而后开始做第26 题，发现如果在遍历中，改变数组的长度，就有问题，

如果用while 循环来，就需要try 来处理；

所以，想到了双指针方法，因为是已经排好序的数组，这个很重要
  

