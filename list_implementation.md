##Python中list 的实现  
这篇文章介绍了Python中list是如何实现的。  
在Python中list特别有用。让我们来看下list的内部是如何实现的。  
来看下面简单的程序，在list中添加一些整数并将他们打印出来。  

    >>> L = []
    >>> L.append(1)
    >>> L.append(2)
    >>> L.append(3)
    >>> L
    [1, 2, 3]
    >>> for e in L:
    ...   print e
    ... 
    1
    2
    3
