ImageComparerX
==============

A images compare tool coding in JAVA(Using Hanming distance and DCT algorithm)

用法：
可执行文件存放在Project的Runnable文件夹下，以压缩成一个zip包。
使用前请确认您的操作系统中已经安装了JDK6+或者JRE1.6+的JAVA环境，算法取自于一个国外的图像处理网站，不存在版权问题。

怎么使用？
解压工具zip包后，将需要比对的文件分别放在SourceImages和TargetImages文件夹下，双击“running.cmd”，Linux系统请大家
自行编写一个sh文件，执行完成后在Result中查看比对结果（目前很单纯，没有做任何花哨的图形化结果反馈），请注意：
比对文件名必须保持相同，包托拓展名，目前对于图片的格式没有限制，当然没有完全测试到，比对灵敏度我已经设置好，如果
您需要改变，请在源码中自行修改成你认为更合理的比对灵敏度和区间。

如果在使用过程中遇到了一些BUG，可以联系作者或者小A同学

工具专门使用了JAVA的动态代理模式的方式进行的编写，之后会在DiggerPlus上写一篇博文介绍这种模式，
并且以这个工具的源码作为实例。

欢迎大家使用~ 

陶醉测者  2014-09-02
