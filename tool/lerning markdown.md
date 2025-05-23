# lerning markdown
Markdown 是一种轻量级标记语言，排版语法简洁。做为一种轻量级标记语言，常用的标签大约只有10个左右，包含标题、段落、换行、强调、引用、有序列表、无序列表、代码块、分隔线、简单表格等。  

学习目标：  
* 能够熟练的使用一种 markdown 编辑器，推荐 Typora  
* 掌握 markdown 常用标签  

注：本文也同样采用 markdown 语法进行编写。  

## 标题
标题做为文档处理中最常见的功能之一，markdown 提供了很好的支持。markdown 将常用标题分为6级，前置位使用**#**号来标记。格式如下：  

Heading H1        语法：# Heading1  
Heading H2        语法：## Heading2  
Heading H3        语法：### Heading3  
Heading H4        语法：#### Heading4s  
Heading H5        语法：##### Heading5  
Heading H6        语法：###### Heading6  

## 段落和换行
在说段落之前，先介绍一下齐头式和缩进式进行一段介绍  

* 齐头式：每段开头定格书写，段落之间空一行。这种格式整体看起来更加清爽简洁，段落分布清晰；
* 缩进式：每段开头缩进4-5字符，段落之间不空行。这是传统的英语写作格式，更显正式。  

段落没有特殊的格式，直接编写文字就好，段落的换行是使用两个空格加上换行。
## 强调
通过将文本设置为粗体或斜体，强调其重要性。  

粗体：I just love **bold text**.              语法：前后各加两个星号  
斜体：I just love *bold text*.                     语法：前后各加一个星号  
粗斜体：I just love ***bold text***.       语法：前后各加三个星号  
## 引用
要创建块引用，请在段落前添加一个 > 符号  

> This is block reference.  

## 有序列表
可以将多个条目组织成有序列表。  

1. First item
2. Second item
3. Third item
4. Fourth item
## 无序列表
可以将多个条目组织成无序列表，并且可进行分层。  

* First item
* Second item
  * indented item
* Third item
* Fourth item
## 代码块
段落上是一个函数或代码片段，可以用三个反引号把它包起来并指定一种语言。  

```java
    public static void main(){
        print("hello world");
    }
```
## 公式
行内公式：  
``` bash
$ y=x*z $
```

块公式：

``` bash
$$
	y=x*z
$$
```

## 分隔线
在单独的一行上使用三个星号，并且不包含其他内容。  

***
## 简单表格
制作表格使用`|`来分隔不同的单元格，使用`-`来分隔表头和其他行。  

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |
|      |      |      |

