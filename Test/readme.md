

# Good morning 

[TOC]

Markdown语法简要说明
标题
-
# 一级标题
## 二级标题
###  三级标题

样式
-
跳转到[目录](#index)
*斜体* _斜体_
**粗体** 
==高亮==
~~删除线~~
>引用

H~2~O 下标

2^10^ 上标

列表
-
无序列表
- Item
  * Item
    + Item
 
有序列表
1. Item 1
2. Item 2
3. Item 3

待办列表:
- [ ] Incomplete item
- [x] Complete item

链接
-
###  文字链接

欢迎来到[胡萝卜周](http://www.carrotchou.blog "胡萝卜周，分享乐趣")
```
欢迎来到[胡萝卜周](http://www.carrotchou.blog "胡萝卜周，分享乐趣")
```
>`[链接文字](链接地址 "链接标题")`
>**_链接地址与链接标题前有一个空格。_**
>[ ]里写链接文字，( )里写链接地址，" "中为链接指定title属性，可加可不加。

我经常去[GitHub][1]、[知乎][2]以及[简书][3]，[简书][3]是一个不错的[写作社区][]。

[1]:https://github.com "GitHub"
[2]:https://www.zhihu.com "知乎"
[3]:http://www.jianshu.com "简书"
[写作社区]:http://www.jianshu.com
```
我经常去[GitHub][1]、[知乎][2]以及[简书][3]，[简书][3]是一个不错的[写作社区][]。

[1]:https://github.com "GitHub"
[2]:https://www.zhihu.com "知乎"
[3]:http://www.jianshu.com "简书"
[写作社区]:http://www.jianshu.com
``` 
>````
>[链接文字][链接标记]
>[链接标记]:链接地址 "链接标题"
>````
>如果链接文字本身可以做为链接标记，也可以写成`[链接文字][]  
[链接文字]:链接地址`

### 图片链接
An image: ![Alt](img.jpg)图片链接
A sized image: ![Alt](img.jpg =60x50)固定大小的图片


代码
-
单行代码
Some `inline code`.
代码块
```
// A code block
var foo = 'bar';
```
语言标注
```javascript
// An highlighted block
var foo = 'bar';
```

表格
-
Item     | Value
-------- | -----
Computer | $1600
Phone    | $12
Pipe     | $1


| Column 1 | Column 2      |
|:--------:| -------------:|
| centered | right-aligned |

自定义列表
-
Markdown
　　:  Text-to-HTML conversion tool

Authors
　　:  John
　　:  Luke

注脚
-
Some text with a footnote.[^1]

[^1]: The footnote.

缩写
-
Markdown converts text to HTML.
*[HTML]: HyperText Markup Language

公式编辑器
-
$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.$

> Jkkoi整理自网络

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

我展示的是一级标题

=================

我展示的是二级标题

-----------------

*斜体文本*

_斜体文本_

**粗体文本**

__粗体文本__

***粗斜体文本***

___粗斜体文本___

~~删除线~~

分割线

***

* * *

*****

- - -

----------

1. 第一项：

    - 第一项嵌套的第一个元素

    - 第一项嵌套的第二个元素

2. 第二项：

    - 第二项嵌套的第一个元素

    - 第二项嵌套的第二个元素

> 引用
> 可以多行合并
> # 里面的MD依然会被解析

> 引用可以嵌套
> > 第一层嵌套
> > > 第二层嵌套

> 区块中使用列表与常规不同
> 1. 第一项
> 2. 第二项
> + 第一项
> + 第二项
> + 第三项

* 同样的，列表中也可以使用引用
    > MD示例
    > Jkkoi整理自网络
* 第二项

`单行代码`代码块，不会被解析
`Console.WriteLine("") ` 控制台输出

第一行可选择填写语言类型以自动高亮
```javascript
$(document).ready(function () {
    alert('JS');
});
```

```python
print()
def md():
    return True
```

```csharp
Console.WriteLine();
```

[链接](https://www.bing.com)
<https://www.bing.com>
直接输入网址会出问题https://www.bing.com

插入图片
![注释](https://i.loli.net/2020/01/12/P1DZegrNO2JtHT3.jpg)
HTML标签的属性也是可以用的
<img src="https://i.loli.net/2020/01/12/P1DZegrNO2JtHT3.jpg" width="10%">
<font face="微软雅黑" color="red" size="5">自定义字体样式、颜色、大小</font>
<font color="#0000ff">也可以单独指定字体颜色</font>
<p align="left">居左文本</p>
<p align="center">居中文本</p>
<p align="right">居右文本</p>

------

使用html标签<br/>换行

------

-: 设置内容和标题栏居右对齐。
:- 设置内容和标题栏居左对齐。
:-: 设置内容和标题栏居中对齐。

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

**文本加粗** 
\*\* 正常显示星号 \*\*

LaTeX
$$
\vec{F}=m\vec{a}
$$

$e=mc^2$
