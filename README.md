### __《C和指针》练习与学习笔记__
---


_第五章 操作符和表达式_
 
左移位
> 最左边的几个值被舍弃，右边多出来的几个空位则由0补齐

右移位分为 __逻辑移位__ 与 __算数移位__

逻辑移位
>左边移入的值用0补齐

算数移位
>左边移入的值用符号位补齐。原先符号位为1则补1，为0则补0

只有当负数的时候，算数右移和逻辑右移才会不一样

```
如 10010110 >> 2
逻辑右移是 00100101
算数右移是 11100101
```
