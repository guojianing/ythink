# ythink
===============
### Yaf框架与ThinkPHP框架的结合体，看中的是Yaf的速度和TP的易用，所以把两者结合在一起！
 + Yaf版本：2.3.5stable
 + Thinkphp版本：5.0.0 RC1



### TP的helper函数均可使用，如：C()、S()、M()、I()、session()、cookie()等
---------------------------------
以下是测试数据
1.用yaf自带视图引擎（不渲染）
 + 不查数据库：35毫秒
 + 简单数据查询：65毫秒

 2.用tp视图引擎（不渲染）
 + 不查数据库：45毫秒
 + 简单数据查询：80毫秒
 + 测试helper里的函数都可以用，这下开发接口没什么痛处了

 + 如果完全禁用视图引擎估计还有提升空间，对于做接口开发&&熟悉thinkphp&&提升响应速度，可以尝试这个ythink。

> --版权归yaf和thinkphp