* MyCompiler 是根据给定的类`Pascal`文法编写的编译程序。
* 源语言为类`Pascal`语言，目标语言为`MIPS`语言
* 文法原文可以参见`文法.txt`文件，其中文法的主要特点如下：
	* 支持`if`、`for`、`case`等分支、循环语句
	* 支持数组，但数组的元素类型仅限于`interger`和`char`
	* 支持写字符串的功能
	* 支持`read`、`write`语句，即在标准输入输出上进行读写
	* 支持`procedure`、`function`，其中`procedure`相当于没有返回值的`function`
	* 支持递归调用，即可以在函数中递归调用自身
	* 支持传参的两种方式，即传值和传地址，当参数前有`var`时，说明传的是地址
	* 对于分层次的程序，支持变量的局部性
* 整个程序的调用结构，可以参看`系统整体结构.bmp`图片