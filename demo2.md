# Demo2

## 连接 demo

### 内嵌式连接

- 外部连接：[百度](http://www.baidu.com)
- 内部连接，连接仓库的其它文件：[demo1](demo1.md)
- 内部连接，连接本文档的其它部分：[代码块 demo](demo2.md#代码块-demo)

### 引用式连接

- 外部连接：[百度]
- 外部连接：[百度][baidu]
- 内部连接，连接仓库的其它文件：[demo1]
- 内部连接，连接本文档的其它部分：[代码块 demo]

## 图片 demo

- 图片的MarkDown语法  

	![alt](url text)

### 内嵌式连接  
- 外部图片
![baidu](https://www.baidu.com/img/bd_logo1.png "百度网站")

- 仓库内的图片 demo  
![](images/Linux.png)

### 图片的引用式连接  
- 外部图片
![baidu][baidu_logo]

- 仓库内的图片 demo  
![][linux_logo]

### 图片大小限制
`<img src="./xxx.png" width = "300" height = "200" alt="图片名称" align=center />`

修改 `width` 和 `height` 即可。  
`src=" "` 的值可以是相对目录(`./xxx.png`)，也可以是外部链接(`http://xx/xxx.png`)，但不可以这样使用`![baidu][baidu_logo]`

例如：

<img src="images/Linux.png" width="600" height="600" alt="编译器和连接器" align=center />


## 引用 demo

> 这是一个引文。  

——出自《出处》

多重引用。

>>> 这是多重引文。

## 代码块 demo

- 行内代码

这个代码中用来声明变量是`var a = 10`, 打印变量内容是`console.log`函数的调用

- 块式代码

```javascript
var a = 10;
console.log(a);
```

    var a = 10;
    console.log(a);  


<!--- 下面是本文档中用到的连接 -->
[百度]: http://www.baidu.com
[baidu]: http://www.baidu.com
[demo1]:demo1.md
[代码块 demo]:demo2.md#代码块-demo

[baidu_logo]: https://www.baidu.com/img/bd_logo1.png
[linux_logo]: images/Linux.png
