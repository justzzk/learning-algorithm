
**对角线遍历**

题目：

给定一个含有 M x N 个元素的矩阵（M 行，N 列），请以对角线遍历的顺序返回这个矩阵中的所有元素，对角线遍历如下图所示:

输入:
[
 [ 1, 2, 3 ],
 [ 4, 5, 6 ],
 [ 7, 8, 9 ]
]

输出:  [1,2,4,7,5,3,6,8,9]

说明:
给定矩阵中的元素总数不会超过 100000 。

实现语言：java

题目分析：

1、M 和 N不确定是否相等，但是对以对角线遍历矩阵没有影响
2、沿对角线的有序遍历
3、输出结果要求是一个有序的数组
4、附上手写手写分析
5、learn_1实现的复杂度为：
   当M或者N任意一个为1时，算法复杂度为O(n);
   当M=N即该矩阵为一个N阶方阵时，算法复杂度为O(n^2);
6、learn_2的实现还有问题，后期补充


