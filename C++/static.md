# static

static 关键词修饰变量会延长变量生存周期到整个程序运行期间。

##局部静态变量
在函数中定义一个局部静态变量，在多次调用该函数时，局部静态变量只会被初始化一次（在第一次调用时被初始化），之后遇到定义语句都会跳过。从而能够满足单例模式的要求。