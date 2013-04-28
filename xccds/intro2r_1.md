# R语言编程入门之一：导论

简单来讲，编程是借助计算机来解决某个问题。学习编程的就是训练我们解决问题的能力。有这样一种说法：在未来，不会编程的人即是文盲。

## 1 为什么要学习R编程

大部分情况下解决某些问题还需要依赖一些事实或数据，结合数据分析的框架和计算工具来帮助我们决策和判断。这时候R语言编程就会派上用场。例如从大的方面来看，投资方要决定在何处建立风力发电场，就需要采集天气数据加以建模分析，评估各项目方案。从小的方面来看，个人是否应该购买某个理财产品，你需要获取过去的市场信息，模拟未来可能的变化，计算该项资产未来的期望收益和标准差。所以说学习R编程就是学习在数据环境中解决问题，从中磨练技术、锻炼智力，还能得到满足的快感。

- 学会R编程，才能理解高手的代码，并从中领会其用意并成为真正的高手。
- 学会R编程，才能深入了解函数背后的理论，从而进一步解决从未有过的新问题。


## 2 如何学习R编程

- 读代码
- 写代码

编程无法在课堂或书本中学到，在游泳池里学游泳是最佳的方法，也是唯一的方法。[Learn Python The Hard Way](http://learnpythonthehardway.org/)一书的作者Zed A. Shaw曾说过“The Hard Way Is Easier”。所以就算是按照教材重复打一遍代码，也会有相当的收获。此外还要按照规范来编写代码，养成良好的习惯，包括各种符号的用法和良好的注释。在注释里作笔记是也一个好的学习方法，很多时候你只需要将旧代码略作修改就可以用到其它地方。

## 3 学习R编程的资源

- 书籍
    * S Programming
    * The Art of R Programming
    * A First Course in Statistical Programming with R
    * software for data analysis programming with R
    * Introduction to Scientific Programming and Simulation Using R
    
- 论坛和博客
    * http://cos.name/cn/forum/15 
    * http://www.r-bloggers.com/
    * http://www.statmethods.net/index.html
    * http://zoonek2.free.fr/UNIX/48_R/all.html
    * http://www.rdatamining.com/
    * http://www.r-statistics.com/
    * http://www.inside-r.org/
    * http://r-ke.info/
    * http://wiki.stdout.org/rcookbook/

## 4 如何获得帮助

R中的帮助文档非常有用，其中有四种类型的帮助

- help(functionname) 对已经加载包所含的函数显示其帮助文档，用?号也是一样的。
- help.search('keyword') 对已经安装的包搜索关键词，用??号功能一样。
- help(package='packagename') 显示已经安装的包的描述和函数说明
- RSiteSearch('keyword') 在官方网站上联网搜索


## 5 R语言的启动

R语言启动后会首先查找有无.Rprofile文档，用户可通过编辑.Rprofile文档来自定义R启动环境，该文件可放在工作目录或安装目录中。

之后R会查找在工作目录有无.RData文档，若有的话将自动加载恢复之前的工作内容。

在R中所有的默认输入输出文件都会在工作目录中。getwd() 报告工作目录，setwd() 负责设置工作目录。在win窗口下也可以点击Change Working Directory来更改。

Sys.getenv('R_HOME') 会报告R主程序安装目录

?Startup可以得到更多关于R启动时的帮助


## 参考资料

- [如何成为一名黑客](http://dongxi.net/b14rH)
- [How to be a Programmer](http://samizdat.mines.edu/howto/HowToBeAProgrammer.html)
- [Teach Yourself Programming in Ten Years](http://norvig.com/21-days.html)
