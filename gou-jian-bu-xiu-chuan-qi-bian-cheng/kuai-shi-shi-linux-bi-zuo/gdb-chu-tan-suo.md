# GDB初探索

请在开始进行C语言编程之后查阅使用

![GNU GDB](https://gw9u39xwqi.feishu.cn/space/api/box/stream/download/asynccode/?code=MGYwN2MyNzM1NzdmNzg0N2I1YTc5ODRhNmI5NzY0ZTRfcU14cUt0SUNVaWgwTVJYZEZRakRncGhzR1dMbEhhZTNfVG9rZW46Ym94Y25IWGdnZzZlTHk4NnZGbWI0c2hPa3NoXzE2NTg3Mjc0ODQ6MTY1ODczMTA4NF9WNA)

## GDB是什么？

调试器，简单来说就是当你代码跑不通时候修正错误用的https://sourceware.org/gdb/mascot/

## 基本操作

https://www.bilibili.com/video/BV1EK411g7Li?spm\_id\_from=333.337.search-card.all.click\&vd\_source=da5a5affb1b0c71c0d7e410b1d1a3c17

#### **GDB使用表**

_run （r）_运行程序_b_打断点，可以在函数和位置打断点_info b_查看打断点的位置_n_下一步，跳过函数的_list_查看源代码_-p_走PID路线edit \[file:]function 看现在停下的函数位置step 进入任何函数_p_打印变量_shell_输入命令_set logging on_记录日志_watchpoint_观察变量是否变化的观察点_watch_设置观察点位置，watch\*（地址）_layout split_开启TUI模式_whatis_查看变量类型_ptype_查看详细信息

**TUI**

_ctrl +x +a_开启_ctrl_+_p_+_n_往前_ctrl_ +_l_重新整理页面

## 官方手册

[GDB User Manual](https://sourceware.org/gdb/current/onlinedocs/gdb)有非常多高级用法，可以在必要的时候进行查阅，受益无穷
