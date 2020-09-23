# ~~Daily Schedule for OS Tutorial Summer of Code 2020~~

# Daily Schedule for OS Tutorial Autumn of Code 2020

前半是当年没做完+没咋写的夏天干的好事……_(:з」∠)_现在秋季重做了，先留着吧。


## TOC

| Mon               | Tues              | Wed                          | Thur                         | Fri                          | Sat               | Sun               |
| ----------------- | ----------------- | ---------------------------- | ---------------------------- | ---------------------------- | ----------------- | ----------------- |
|                   |                   | 23 <br> ([D1](#day-1-20200923)) | 24   | 25   | 26   | 27   |
| 28 | 29  | 30            | 1           | 2         | 3              | 4        |
| 5           | 6| 7| 8| 9| 10| 11|
| 12| 13| 14 | 15| 16| 17| 18                |
| 19                | 20                | 21                           | 22                           |                              |                   |                   |

------

## Day-1 2020/7/23
### 环境配置
  其实WSL2以前装过的，但是不知道为啥我给卸了，可能是不怎么好用？不过这次就得重装了（悲）
  其实说起来rust倒是在windows下有着十分完整的工具链了……但是那个却确实是有操作系统依赖的，的确是不用为妙。
  基本上算是轻车熟路，以后感觉有条件应该尽量用WSL2环境
### Lab0
  其实主要就是环境的基本配置。基本毫无难度。
  
## Day0 2020/7/24
### Lab1
  Lab1其实本身实验难度并不算大，毕竟指导已经给的十分详细了。
  当然指导的代码也有一些小问题，比如handler.rs中use模块是严重不全的，不过这个其实很容易改。另一个是最后的描述问题，main()的修改事实上应该是将unreachable修改为loop从而满足基本语法要求。
  另外理论上context其实应该加上debug trait但是我这儿时间确实不大够就没加……有点卑微_(:з」∠)_
### Lab1-practice
  1.
    sp - 34 * 8
    在中断结束后才会完成恢复过程，中途是不会发生变化的。
  2.
    这样的程序是没有出口的，它是不会停下来的。
  3.
    实验代码待上传（这就是不常用GitHub的后果）
    
## Day1 2020/7/25
  今天才算是真正第一天开始的实验的日子……当然前面其实应该有Day0 Day-1之类的但是暂时没啥时间补上了有点心累…………
  这一天暂时完成的是完善了的Lab-2（Lab-1在这之前已经完成了），但是暂时还没有上传……
  当然，这一部分其实也真正是Day2写的（悲
  另外晚上看到了大家在群里的发言，确实大家特别强，怎么感觉我好像就有点像是纯属混入其中的鶸……
### Lab2
  

## Day2 2020/7/26
  这一天都在啃Lab3……Lab3开始感觉知识就有些跟不上了，赶得太紧果然不大好
### 顺便开了个跟我好像没太大关系的会
  探讨了下去深圳的条件和深圳的条件，但是好像和晚起步很久的我没有太大的关系，这太致命了（悲）
  其实要说那个Hackthon的形式我是真的很心动了。然而吧……然而吧。
### Lab3
  
# 好了，秋季上车重做，我们重新从Day0开始（

## Day0 2020/9/22
  经要求这次又得拿个GitHub仓库来保存分享结果……反正上次也没写完，这次就拿它直接来用好了。
  其实上次学的也不是那么深入，这次也算是加深下印象吧。系统配置这里继续使用WSL2来作为开发环境，笔记本折腾不起双系统，也暂时没钱买固态来引导。
  系统安装过程没什么难的。考虑到要写的东西又翻了翻相关参考书籍。

## Day1 2020/9/23
  今天把lab0再做了一遍，想想当时第一次做出来还是很激动的，现在恐怕更多的是感慨了吧？
  另外把git也配置了下，想了想还是采用把实验部分的代码单独摘到win下直接发，更（？）方便管理。
  另外学SICP的时候顺便碰了碰emacs，好像很香，org-mode都说天下第一不过我倒是存疑……
