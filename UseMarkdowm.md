# Markdown 语法介绍 #


<!--这个是html的注释,markdowm支持html标签-->

<!--
多行注释
多行注释
多行注释
-->

标题:
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题


引用:
Markdown 标记区块引用和 email 中用『>』的引用方式类似，只需要在整个段落的第一行最前面加上『>』：例如

> Coding.net 为软件开发者提供基于云计算技术的软件开发平台，包括项目管理，代码托管，运行空间和质量控制等等。


区块引用可以嵌套，只要根据层次加上不同数量的『>』：

> 这是第一级引用。
>
> > 这是第二级引用。
>
> 现在回到第一级引用。

引用的区块内也可以使用其他的 Markdown 语法，包括标题、列表、代码区块等：

> ## 这是一个标题。
> 1. 这是第一行列表项。
> 2. 这是第二行列表项。
>
> 给出一些例子代码：



列表:
列表项目标记通常放在最左边，项目标记后面要接一个字符的空格。

无序列表：
使用星号、加号或是减号作为列表标记

- Red
- Green
- Blue
	- RedBlue
	- OtherBlue

有序列表：
使用数字接着一个英文句点

1. Red
	1.1 你好
	1.2 再见 
2. Green
3. Blue
	(1) ReaBlue
	(2) OtherBlue

如果要在列表项目内放进引用，那『>』就需要缩进：

*  Coding.net有以下主要功能:
    > 代码托管平台
    > 在线运行环境    
    > 代码质量监控    
    > 项目管理平台


CheckBox: 
表示列表是否勾选状态（注意：[ ] 前后都要有空格）

- [ ] 不勾选
- [x] 勾选


代码块:
只要把你的代码块包裹在``` 之间，你就不需要通过无休止的缩进来标记代码块了。举个例子:

```
class PersonManager {
    static Person createPerson(String name,int age){
        return Person.createPerson(name,age)
    }
}
```


强调:
在Markdown中，可以使用 * 和  _  来表示斜体和加粗。

斜体：
*Coding，让开发更简单*
_Coding，让开发更简单_


加粗：
**Coding，让开发更简单**
__Coding，让开发更简单__

删除线:
~~This was mistaken text~~


自动链接:
方括号显示说明，圆括号内显示网址， Markdown 会自动把它转成链接，例如：

[超强大的云开发平台Coding](http://coding.net)

表格:
在 Markdown 中，可以制作表格，例如：

First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell


或者也可以让表格两边内容对齐，中间内容居中，例如：

First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right


分割线:
在 Markdown 中，可以使用 3 个以上『-』符号制作分割线，例如：

这是分隔线上部分内容
---
这是分隔线上部分内容


图片:
Markdown 使用了类似链接的语法来插入图片, 包含两种形式: 内联 和 引用.

内联图片语法如下:

![](/pic/head.png)

图片指定大小:
<img src="/pic/head.png" height="100" width="100" 
style="margin-left:45px margin-top:100px">