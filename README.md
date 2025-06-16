# 编译原理相关实验的仓颉语言实现
正规式转NFA转DFA，消除左递归，消除左公共因子，求FIRTST集和FOLLOW集

RegExp_NFA_DFA文件中

输入正规式，将正规式转化为NFA再转化为DFA，输出NFA，DFA的五元组

测试结果为
![image.png](D:\AAAAdvpgm\compilation-experiment-with-cangjie-main\assets\image.jpeg 'image.png')
![image.png](D:\AAAAdvpgm\compilation-experiment-with-cangjie-main\assets\image-1750044166437-3.jpeg 'image.png')

Task3文件中

3.1提取间接左递归，提取直接左递归

3.2提取左公共因子

3.3计算FIRST集和FOLLOW集

测试结果为

测试用例1：消除左递归，发现没有间接左递归，消除了直接左递归，打印算法后的文法![image.png](D:\AAAAdvpgm\compilation-experiment-with-cangjie-main\assets\image-1750044174103-6.jpeg 'image.png')

测试用例2：消除间接左递归后消除直接左递归，再进行文法的化简，打印文法![image.png](D:\AAAAdvpgm\compilation-experiment-with-cangjie-main\assets\image-1750044179066-9.jpeg 'image.png')

测试用例3：提取左公共因子后发现文法还存在左公共因子，再次进行提取左公共因子计算，打印文法![image.png](D:\AAAAdvpgm\compilation-experiment-with-cangjie-main\assets\image-1750044184230-12.jpeg 'image.png')

测试用例4：求FIRST集，FOLLOW集

![image.png](D:\AAAAdvpgm\compilation-experiment-with-cangjie-main\assets\image-1750044188303-15.jpeg 'image.png')

测试用例5：求FIRST集，FOLLOW集

![image.png](D:\AAAAdvpgm\compilation-experiment-with-cangjie-main\assets\image-1750044192238-18.jpeg 'image.png')
