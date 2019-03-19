# zhihutxt
这是一个多线程爬虫，通过输入问题关键字，查询该关键字下所有问题，并将每一个问题下的所有答案保存下来

知乎文本文件的爬取 文件名合法问题 判断文件名合法 匿名话题 搜索关键字得到所有问题的所有回答

如何判断文件名是否合法呢？因为在进行创建文件的过程中，我们总是会遇到这种问题，于是需要用到re正则表达式了：
re.search('[|\/|:|*|?|<}>|\|]|"',fileName)
这个样子就好啦，当然你可以增加Windows下的其他不合法的标点符号文件名

![image](https://github.com/BitArtificial/zhihutxt/blob/master/1.png)


![image](https://github.com/BitArtificial/zhihutxt/blob/master/2.png)
