# 第一章 计算机中的最基本部件

* CPU 中央处理器
* PC 程序计数器
* MAR 存储器地址寄存器
* ALU 算术逻辑部件
* IR 指令寄存器
* MDR 存储器数据寄存器
* GPRs 通用寄存器组（由若干个通用寄存器组成，早期就是累加器）

“存储程序”的工作方式 <br>

指令都是按序存放


1. 根据PC取指令
2. 指令译码
3. 取操作数
4. 执行指令
5. 回写结果
6. 修改PC的值
7. 继续执行下一个PC的值

**指令中需给出的信息:**
操作性质（操作码）
源操作数1 或/和 源操作数2 （立即数、寄存器编号、存储地址）
目的操作数地址 （寄存器编号、存储地址）

存储地址的描述与操作数的数据结构有关

机器语言编写的程序，就是 0和1 组成的序列

指令是什么呢？

    - 指令包括操作码和操作数或其他地址码
        机器指令用二进制表示，汇编指令用符号表示
    - 只能描述： 取（或存一个数）
                两个数相加（减、乘、除、与、或等）
                根据运算结果判断是否转移执行

## 高级语言
高级编程语言

    它们与具体机器结构无关 
    面向算法描述，比机器语言描述能力强很多 
    高级语言中一条语句对应几条、几十条甚至几百条指令
    有 面向过程 和 面向对象 的语言之分 
    处理逻辑分为三种结构
        * 顺序结构、选择结构、循环结构 
    有两种转换方式： 编译和解释
        * 编译程序：将高级语言源程序转换为机器级目标程序，执行时之钥启动目标程序即可
        * 解释程序：将高级语言语句逐条翻译成机器指令并立即执行，不生成目标文件
    





