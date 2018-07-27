[TOC]
# 标题

而在 Markdown 中，你只需要在文本前面加上 `#` 即可，同理、你还可以增加二级标题、三级标题、四级标题、五级标题和六级标题，总共六级，只需要增加 `#` 即可，标题字号相应降低。 

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

# 列表

列表格式也很常用，在 Markdown 中，你只需要在文字前面加上 `-` 就可以了，例如： 

- 文本1

- 文本2

- 文本3

1. 文本1
2. 文本2
3. 文本3

# 链接和图片

在 Markdown 中，插入链接不需要其他按钮，你只需要使用 `[显示文本](链接地址)` 这样的语法即可，例如：



在 Markdown 中，插入图片不需要其他按钮，你只需要使用 `![](图片链接地址)` 这样的语法即可，例如：

 # 引用

在我们写作的时候经常需要引用他人的文字，这个时候引用这个格式就很有必要了，在 Markdown 中，你只需要在你希望引用的文字前面加上 `>` 就好了， 



```
`n`
```

`n`

 # 粗体和斜体

Markdown 的粗体和斜体也非常简单，用两个 `*` 包含一段文本就是粗体的语法，用一个 `*` 包含一段文本就是斜体的语法。 

```
**的和我和文化**
*的和我和文化*
```

**的和我和文化**  

*的和我和文化*

 # 代码引用

需要引用代码时，如果引用的语句只有一段，不分行，可以用 ` 将语句包起来。
如果引用的语句为多行，可以将```置于这段代码的首行和末行

# 表格

```
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

```
dog | bird | cat
----|------|----
foo | foo  | foo
bar | bar  | bar
baz | baz  | baz
```
dog | bird | cat
----|------|----
foo | foo  | foo
bar | bar  | bar
baz | baz  | baz



# 显示链接中带括号的图片

![][1]
[1]: http://latex.codecogs.com/gif.latex?\prod%20\(n_{i}\)+1



```
* * *

***

*****

- - -

---------------------------------------
```

* * *

***

*****

- - -

---------------------------------------



This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

# MarkDown 图片大小问题

```
![lena](C:\Users\x1c\Desktop\for-markdown-pic\20151129213701642.jpg)
```

![lena](C:\Users\x1c\Desktop\for-markdown-pic\20151129213701642.jpg) 


```
<img src="C:\Users\x1c\Desktop\for-markdown-pic\20151129213701642.jpg" width=128 height=128 />
```
<img src="C:\Users\x1c\Desktop\for-markdown-pic\20151129213701642.jpg" width=256 height= />

```
<img src="C:\Users\x1c\Desktop\for-markdown-pic\20151129213701642.jpg" width="50%" height="50%" />
```
<img src="C:\Users\x1c\Desktop\for-markdown-pic\20151129213701642.jpg" width="50%" height="50%" />

```
<center>
<img src="C:\Users\x1c\Desktop\for-markdown-pic\20151129213701642.jpg" width="25%" height="25%" />
Figure 1. Lena
</center>
```

<center>
<img src="C:\Users\x1c\Desktop\for-markdown-pic\20151129213701642.jpg" width="25%" height="25%" />
Figure 1. Lena
</center>


```
$$
y=\begin{cases}
-x,\quad x\leq 0\\
x, \quad x>0
\end{cases}
$$
```


$$
y=\begin{cases}
-x,\quad x\leq 0\\
x, \quad x>0
\end{cases}
$$

# 斜体和粗体

```
1. *斜体*或_斜体_
2. **粗体**
3. ***加粗斜体***
4. ~~删除线~~
```

1. *斜体*或_斜体_
2. **粗体**
3. ***加粗斜体***
4. ~~删除线~~

# 超链接

Markdown 支持两种形式的链接语法： 行内式和参考式两种形式，行内式一般使用较多。

### 3.1. 行内式

语法说明：

- []里写链接文字，()里写链接地址, ()中的”“中可以为链接指定title属性，title属性可加可不加。title属性的效果是鼠标悬停在链接上会出现指定的 title文字。[链接文字](链接地址 “链接标题”)’这样的形式。链接地址与链接标题前有一个空格。

代码：
```
1. 欢迎来到[梵居闹市](http://blog.leanote.com/freewalk)

2. 欢迎来到[梵居闹市](http://blog.leanote.com/freewalk "梵居闹市")
```
显示效果：

1. 欢迎来到[梵居闹市](http://blog.leanote.com/freewalk)

2. 欢迎来到[梵居闹市](http://blog.leanote.com/freewalk "梵居闹市")

### 3.2. 参考式

参考式超链接一般用在学术论文上面，或者另一种情况，如果某一个链接在文章中多处使用，那么使用引用 的方式创建链接将非常好，它可以让你对链接进行统一的管理。

语法说明： 
参考式链接分为两部分，文中的写法 [链接文字][链接标记]，在文本的任意位置添加[链接标记]:链接地址 “链接标题”，链接地址与链接标题前有一个空格。

如果链接文字本身可以做为链接标记，你也可以写成[链接文字][] 
[链接文字]：链接地址的形式，见代码的最后一行。

代码：

```
1.我经常去的几个网站[Google][1]、[Leanote][2]以及[自己的博客][3]
2. [Leanote 笔记][2]是一个不错的[网站][]。
3.
4. [1]:http://www.google.com "Google"
5. [2]:http://www.leanote.com "Leanote"
6. [3]:http://http://blog.leanote.com/freewalk "梵居闹市"
7. [网站]:http://http://blog.leanote.com/freewalk
```

我经常去的几个网站[Google][1]、[Leanote][2]以及[自己的博客][3]
[Leanote 笔记][2]是一个不错的[网站][]。

[1]:http://www.google.com "Google"
[2]:http://www.leanote.com "Leanote"
[3]:http://http://blog.leanote.com/freewalk "梵居闹市"
[网站]:http://http://blog.leanote.com/freewalk

### 3.3. 自动链接

语法说明： 
Markdown 支持以比较简短的自动链接形式来处理网址和电子邮件信箱，只要是用<>包起来， Markdown 就会自动把它转成链接。一般网址的链接文字就和链接地址一样，例如：

代码：

```
1. <http://example.com/>
2. <address@example.com>
```

显示效果：

<http://example.com/> 
[address@example.com](mailto:address@example.com)



# 锚点

网页中，锚点其实就是页内超链接，也就是链接本文档内部的某些元素，实现当前页面中的跳转。比如我这里写下一个锚点，点击回到目录，就能跳转到目录。 在目录中点击这一节，就能跳过来。还有下一节的注脚。这些根本上都是用锚点来实现的。

注意： 
\1. Markdown Extra 只支持在标题后插入锚点，其它地方无效。 
\2. Leanote 编辑器右侧显示效果区域暂时不支持锚点跳转，所以点来点去发现没有跳转不必惊慌，但是你发布成笔记或博文后是支持跳转的。

语法描述： 
在你准备跳转到的指定标题后插入锚点{#标记}，然后在文档的其它地方写上连接到锚点的链接。

代码：

```
1. ## 0. 目录{#index}
2. 
3. 跳转到[目录](#index)
```

显示效果：


## 目录{#123}

跳转到[目录](#123)

### 定义型列表

语法说明：

定义型列表由名词和解释组成。一行写上定义，紧跟一行写上解释。解释的写法:紧跟一个缩进(Tab)

代码：

```
1. Markdown
2. :    轻量级文本标记语言，可以转换成html，pdf等格式（左侧和四个不可见的空格）
3. 
4. 代码块 2
5. :   这是代码块的定义（左侧四个不可见的空格）
6. 
7.         代码块（左侧有八个不可见的空格）
```
Markdown
    轻量级文本标记语言，可以转换成html，pdf等格式（左侧有一个可见的冒号和四个不可见的空格）

代码块 2
    这是代码块的定义（左侧有一个可见的冒号和四个不可见的空格）

        代码块（左侧有八个不可见的空格）

# 注脚

语法说明：

在需要添加注脚的文字后加上脚注名字[^注脚名字],称为加注。 然后在文本的任意位置(一般在最后)添加脚注，脚注前必须有对应的脚注名字。

注意：经测试注脚与注脚之间必须空一行，不然会失效。成功后会发现，即使你没有把注脚写在文末，经Markdown转换后，也会自动归类到文章的最后。

代码：
```
1. 使用 Markdown[^1]可以效率的书写文档, 直接转换成 HTML[^2], 你可以使用 Leanote[^Le] 编辑器进行书写。
2. 
3. [^1]: Markdown是一种纯文本标记语言
4. 
5. [^2]: HyperText Markup Language 超文本标记语言
6.
7. [^Le]: 开源笔记平台，支持Markdown和笔记直接发为博文


```


显示效果：

使用 Markdown[^1]可以效率的书写文档, 直接转换成 HTML[^2], 你可以使用 Leanote[^Le] 编辑器进行书写。

[^1]: Markdown是一种纯文本标记语言

[^2]: HyperText Markup Language 超文本标记语言

[^Le]: 开源笔记平台，支持Markdown和笔记直接发为博文


注：脚注自动被搬运到最后面，请到文章末尾查看，并且脚注后方的链接可以直接跳转回到加注的地方。

```flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
```


```flow
st=>start: Start|past:>http://www.google.com[blank]
e=>end: End:>http://www.google.com
op1=>operation: get_hotel_ids|past
op2=>operation: get_proxy|current
sub1=>subroutine: get_proxy|current
op3=>operation: save_comment|current
op4=>operation: set_sentiment|current
op5=>operation: set_record|current

cond1=>condition: ids_remain空?
cond2=>condition: proxy_list空?
cond3=>condition: ids_got空?
cond4=>condition: 爬取成功??
cond5=>condition: ids_remain空?

io1=>inputoutput: ids-remain
io2=>inputoutput: proxy_list
io3=>inputoutput: ids-got

st->op1(right)->io1->cond1
cond1(yes)->sub1->io2->cond2
cond2(no)->op3
cond2(yes)->sub1
cond1(no)->op3->cond4
cond4(yes)->io3->cond3
cond4(no)->io1
cond3(no)->op4
cond3(yes, right)->cond5
cond5(yes)->op5
cond5(no)->cond3
op5->e
```
# 任务列表

```
这是文字……

- [x] 选项一
- [ ] 选项二  
- [ ]  [选项3]
```

这是文字……

- [x] 选项一
- [ ] 选项二  
- [ ] 选项三   



22.锚点
代码
注：只有标题支持锚点， 跳转目录方括号后 保持空格

[公式标题锚点](#1)
# [需要跳转的目录]{#1} 


$\operatorname*{Res}_{z=1}$

$\sum \limits_{x \to 1}$



tag=>type: content:>url

```flow
flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
```

```flow
st=>start: Start|past:>http://www.google.com[blank]
e=>end: End:>http://www.google.com
op1=>operation: get_hotel_ids|past
op2=>operation: get_proxy|current
sub1=>subroutine: get_proxy|current
op3=>operation: save_comment|current
op4=>operation: set_sentiment|current
op5=>operation: set_record|current

cond1=>condition: ids_remain空?
cond2=>condition: proxy_list空?
cond3=>condition: ids_got空?
cond4=>condition: 爬取成功??
cond5=>condition: ids_remain空?

io1=>inputoutput: ids-remain
io2=>inputoutput: proxy_list
io3=>inputoutput: ids-got

st->op1(right)->io1->cond1
cond1(yes)->sub1->io2->cond2
cond2(no)->op3
cond2(yes)->sub1
cond1(no)->op3->cond4
cond4(yes)->io3->cond3
cond4(no)->io1
cond3(no)->op4
cond3(yes, right)->cond5
cond5(yes)->op5
cond5(no)->cond3
op5->e
```

```sequence
title: 时序图例子
A->B: 实线实箭头
B-->C: 虚线实箭头
C->>C: 实线虚箭头
note right of C: 自通知
note over B,C:横跨通知
C->A:长通知
note left of A:左通知
```



7.1 在jupyter中设置link，需要设置两部分：
要跳到的位置(the destination) 
需要在要跳转到的位置添加下面语句:

<a id='the_destination'></a>
1
这里的id取值任意赋值，下面在添加链接时要用

需要添加链接的文字（an internal hyperlink to the destination），即点击该处可以跳转到the destination，在需要添加链接的文字后面加入：

[需要添加连接的文字](#the_destination)
1
下面是一个例子： 
源码： 
这里写图片描述
效果图： 
