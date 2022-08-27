# CS-APP
个人学习练习题,以及部分学习知识记录

page 68 ->2.35  2.36  2.37 (数值判断程序设计题)<br />

----

page 82 ->2.49
在浮点数能否有效的正整数范围，与尾数部分即n的大小有关（从整数往浮点数转换可以发现，除开被暂时忽略的整部部分的1，能否转成浮点数，关键看n是否大于等于小数部分的有效位个数，通俗的讲就是这n位能否装下所有的小数部分），即能表示n+1位的二进制无符号整数。<br />
n+1位的二进制无符号整数的最大是2 n + 1 − 1 2^{n+1}-12 
n+1
 −1。那么刚好不能表示的整数则为2 n + 1 − 1 + 1 = 2 n + 1 2^{n+1}-1+1 = 2^{n+1}2 
n+1
 −1+1=2 
n+1
 。<br />
注意上述答案是错误的。<br />
实际上2 n + 1 2^{n+1}2 
n+1
 是可以表示的，因为2 n + 1 2^{n+1}2 
n+1
 的无符号二进制肯定是1 后接n+1个0（2 n + 1 2^{n+1}2 
n+1
 是第n+2位的权值，从第1位开始），而此题说了阶码范围肯定够大，那么小数是0可以表示，而阶码部分也可以保证了，所以实际上是可以表示的。
而2 n + 1 + 1 2^{n+1}+12 
n+1
 +1则不可以表示，因为2 n + 1 + 1 2^{n+1}+12 
n+1
 +1的无符号二进制肯定是1 后接n个0 再接个1，除开前面属于整数部分的1，后面的小数还有n+1位呢（这里可不是全是0了啊），只有n位的浮点肯定不够表示呀。<br />
 
 答案为2 n + 1 + 1 2^{n+1}+12 n+1 +1。<br />
原文链接：https://blog.csdn.net/anlian523/article/details/83929008

----

第三版 第二章家庭作业（错误点家庭作业2.87最后一行，评论区已经评论改正后的结果）
[好文章]https://blog.csdn.net/weixin_30902675/article/details/94782128?spm=1001.2101.3001.6650.3&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-3-94782128-blog-115558675.pc_relevant_multi_platform_featuressortv2dupreplace&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-3-94782128-blog-115558675.pc_relevant_multi_platform_featuressortv2dupreplace&utm_relevant_index=4

----

https://zhuanlan.zhihu.com/p/379680768

----
