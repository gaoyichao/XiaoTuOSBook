# 2. 让处理器跑起来：编写boot引导程序

测试一些插件$$ \varepsilon $$,这样好吗

$$
\begin{matrix}
   a & b \\
   c & d
\end{matrix}
$$

通过ace渲染代码

{%ace edit=false, lang='c_cpp', check=false, theme="monokai" %} 
#include <stdio.h>

int main()
{
    return 0;
}
{%endace%} 

[import, lang:"c_cpp"](douniwan.cpp)


## 2.1. 处理器的工作原理
### 2.1.1. ARM Cortex-M4的内核结构
### 2.1.2. ARM指令集与汇编语言简介
### 2.1.3. STM32的上电过程
## 2.2. 编写引导程序
### 2.2.1. 用汇编实现的启动文件: boot.s
### 2.2.2. 从汇编程序跳转到C程序的main()函数
### 2.2.3. 通过编译链接脚本生成二进制文件
### 2.2.4. 烧录并运行程序
## 2.3. 小结




