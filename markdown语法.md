# markdown语法

## 1 标题

标题使用#，几个#表示几级标题

## 2 流程图

使用``` 开始画流程图，比如下面这种时序图：

```sequence
Bob -> Alice: hello Bob, How are you?
```

上图的实际代码是

```c
​```sequence
  Bob -> Alice: hello Bob, How are you?
```

从上面的例子可以看出用markdown画时序图真的很方便。当然还可以画其他的各种图，比如流程图：

```flow
​```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
```

上图的实际代码是

```c
​```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
```

## 3 加粗

在文字的两边加上\**就可以对文字进行加粗，比如”**这个是我要说的重点**“，我在文字的两边加上了

**。

## 4 超链接

使用\[超链接的名称](超链接的地址)这样的格式可以生成超链接

[百度](https://baidu.com)

上面的百度超链接的代码为

```c
[百度](https://baidu.com)
```

## 5 其他

> 一级引用
>
> > 二级引用
> >
> > > 三级引用

上面引用的代码为

```c
> 一级引用
  > 二级引用
   > 三级引用
```

在斜体的文字的左右分别用*包起来

在斜体加粗的文字的左右分别用三个*包起来

在要删除的文字左右分别用两个～～包起来







