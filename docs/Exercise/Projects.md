# 综合编程题
1. 编写一个程序，输入一个三位数，分别输出该数的百位、十位和个位。

2. 在100～200中找出同时满足用3除余2，用5除余3和用7除余2的所有整数。

3. 编一程序显示如下图案：
```
      A
    A B C
  A B C D E
A B C D E F G 
```
4.猴子吃桃问题。猴子第一天摘下若干个桃子，当即吃了一半，还不过瘾，又多吃了一个。第二天早上又将剩下的桃子吃掉一半，又多吃了一个。以后每天早上都吃了前一天剩下的一半零一个。到第10天早上想再吃时，发现只剩一个桃子了，求猴子第一天究竟摘了多少个桃子？

5. 输入一个4×4矩阵各元素的值，求解该矩阵中的马鞍点（即该点的值在它所在的行中最大，在它所在的列中最小）。窗体顶端窗体底端

6. 写统计输入的正文中有多少单词的程序，这里的单词指的是用空白符分隔开的字符串。

7. 有17个人围成一个圈(编号0-16)，从第0号的人开始从1报数，凡报到3的倍数的人离开圈子，然后再继续数下去。直到最后只剩下一个人为止。问此人原来的位置是多少号？

8. 给定一个升序数组，该数组的元素值为1，3，5，7，9，11，13，任意输入一个数判断该数在数组中是否存在。若存在，给出它在数组中的位置，否则显示该数不存在。

9. 使用递归函数求解并输出Fibonacci数列的前十项。

10. 使用引用参数编制程序，实现两个字符串变量的交换。例如开始时：
```c++
char  *ap=”hello”；
char  *bp=”how are you”；
// 交换后使ap和bp指向的内容别是：
ap：”how are you”
bp：”hello”
```

11. 插入排序算法的主要思想是：每次从未排序序列中取出一个数据，插入到已排序序列中的正确位置，InsertSort类的成员函数sort()实现了插入排序算法，请将画线处缺失的部分补充完整。
```c++
#include <iostream>
using namepspace std;
class InsertSort{
public:
	InsertSort(int*a0,int n0):a(a0),n(n0){}//a是数组首地址，n是数组元素个数
	void sort()
	{//此函数假设已排序序列初始化状态只包含a[0]，未排序序列初始为a[1]…a[n-1]
		for (int i=1;i<n;++i)
		{
			int j,t;
			for(_______________;j>0;--j)
			{
				if(t>a[j-1])break;
				a[j]=a[j-1];
			}
			a[j]=t;
		}
	}
protected:
	int*a,n;//指针a用于存放数组首地址，n用于存放数组元素个数
};
```
