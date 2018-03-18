# BlogForTech
go语言技术内幕
1. 经常看到不少关于go的内幕的文章，看得很多，总结的很少，这里作为一个blog提出这方面的内容
go 的协程实现机制
   (1)比较典型的实现方式是M，P,G，其中G对应的是协程本身，P 对应的是处理器内容，M对应的是操作系统级的内容，这样就会实现处理线程和调度的关系
      具体的实现机制可以参考:
      https://www.zhihu.com/question/20862617
      
2. go 面试100题
https://www.jianshu.com/p/f690203ff168

3. 深入go部分的内容
https://tiancaiamao.gitbooks.io/go-internals/content/zh/03.4.html
