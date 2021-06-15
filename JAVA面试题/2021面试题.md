# 2021面试题

## java面积对象有哪些特征

​	1、封装，继承，多态。

​		封装：将具有相同属性的个体封闭成一个类。增强代码的复用性，比如：猫，狗，鸡，鸭它们可以属于动物，那么我们就可以封装一个动物类

​		继承：就是继承父类公有的东西，然后自己可以去扩展自己的东西、比如，猫，有它特殊的功能，抓老鼠，那么我们就可以继承动物类，派生出一个猫类，然后再扩展抓老鼠这个特别的功能

​		多态:  包含封装，继承，重写，增强代码的复用性，和健壮性 ，大家功能 一样，但是实现不一样，比如，家里有两只猫，猫A抓老鼠是先用爪子把老鼠按着再用嘴给老鼠咬死，而猫B呢，则是直接追上去就一嘴把老鼠给咬死了，但是呢它们都实现了抓老鼠的这个动作

##   ArrayList和LinkedList的区别

1、数据结构不同，ArrayList是数组形式存储的数据，LinkedList是链表结构存储的数据

2、线程安全不同，ArrayList非线程安全，LinkedList线程非安全

3、执行效率不同，ArrayList 查询快，LinkedList，插入和删除快

4、内存占用不同，ArrayList,只需要存储一个下标即可，而LinkedList却不光要存储数据，它还要存储下一个节点和上一节点的指针                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              

## 高并发中的集合有哪些

第一代：Vector,HashTable  线程安全

第二代：ArrayList,HashMap    Collections.synchronizedList(list),Collections.synchronizedMap(map) 底层用synchronize去实现的

第三代：ConcurrenHashMap,

## JAVA8的新特性

