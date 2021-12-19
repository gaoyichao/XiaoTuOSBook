# 目录

* [引言](README.md)
    * [一个嵌入式操作系统的实现过程](/Introduction/README.md)
    * [读者对象](/Introduction/)
    * [内容安排](/Introduction/)
    * [致谢](/Introduction/)

* [第一部分：构建内核](/Part1.md)
    * [搭建工作环境：选择内核、处理器与工具链](/Chapter1.md)
        * 认识嵌入式操作系统内核
            * 操作系统是什么
            * 嵌入式操作系统的特点
            * 内核要完成的工作
            * 内核的选择：微内核
        * 选择硬件平台
            * 计算机组成简介
            * ARM Cortex-M4处理器与STM32微控制器
            * 探索者STM32F407开发板
        * 搭建开发工具链
            * Linux系统环境及基本操作
            * 文本编辑器：VS Code
            * 交叉编译器：gcc-arm
            * 代码烧录器：OpenOCD
            * 在线调试器：GDB
        * 小结
    * [让处理器跑起来：编写boot引导程序](/Chapter2.md)
        * 处理器的工作原理
            * ARM Cortex-M4的内核结构
            * ARM指令集与汇编语言简介
            * STM32的上电过程
        * 编写引导程序
            * 用汇编实现的启动文件: boot.s
            * 从汇编程序跳转到C程序的main()函数
            * 通过编译链接脚本生成二进制文件
            * 烧录并运行程序
        * 小结




