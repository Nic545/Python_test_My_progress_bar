### Python_test_My_progress_bar
python初学--自己写的一个进度条小程序

使用起来非常简单，最简单的初始化仅需要输出一共需要执行的步数；
默认的进度条长度为50个字符；
如果需要自定义，仅需要在创建类的对象的时候设置自己喜欢的字符和进度条的长度

之后在每一次的遍历循环之中调用一下`pb.show()`函数即可

！进度条的输出最好放在最后一行或者最开始一行输出，否则可能会覆盖掉一些你想要通过输出看到的东西
