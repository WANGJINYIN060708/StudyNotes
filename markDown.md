# markDown文档编写学习笔记（2019.3.25）
==============================================
## 1.标题
------------------------------------------------
### 1.1#代表一级标题
### 1.2##代表二级标题
### 1.3###代表三级标题
### 1.4####代表四级标题
### 1.5#####代表五级标题
### 1.6######代表六级标题
## 2.分级标题（= -）
------------------------------------------------
### 2.1 一级标题后加 =
### 2.2 二级标题后加 -
## 3.TOC
## 3.1 代码[TOC]
## 3.2 如何使用TOC
------------------------------------------------
## 4.引用
### 4.1 多行式
------------------------------------------------
>hello world!
>hello world!
>hello world!
### 4.2 多层嵌套
------------------------------------------------
>aaaaaa
>>bbbbbb
>>>cccccc
>>>>dddd
## 5.行内标记
注：用 ` 标记代码块将变成一行
------------------------------------------------
标记之外`hello world`标记之外
## 6.代码块
注：`与上行距离一空行`
------------------------------------------------
### 6.1 代码1(```)
```
<div>   
    <div></div>
    <div></div>
    <div></div>
</div>
```
### 6.2代码2(Tab)
注： Tab缩进   我是文字
......
------------------------------------------------
## 7.插入链接
### 7.1 代码1(内链式)
注：{:target="_blank"}跳转方式兼容性一般 ，多数第三方平台不支持跳转
------------------------------------------------
[百度1](http://www.baidu.com/" 百度一下"){:target="_blank"} 
### 7.2 代码2 
------------------------------------------------
[百度2][2]{:target="_blank"}
[2]: http://www.baidu.com/   "百度二下"
## 8.插入图片
### 8.1 代码1(内链式)
------------------------------------------------
![](./01.png '描述')
### 8.2 代码2（引用）
------------------------------------------------
![name][01]
[01]: ./01.png '描述'
## 9.序表
### 9.1 代码1(有序)
----------------------------
注：序列.后 保持空格
1. one
2. two
3. three
### 9.2 代码2(无序)
---------------------
* one
* two
* three
### 9.3 代码3（嵌套）
-----------------------
1. one
    1. one-1
    2. two-2
2. two 
    * two-1
    * two-2
### 9.4 代码4（序表嵌套代码块）
----------------------
* one

    var a = 10; 
## 10.表格
|    a    |       b       |      c     |
|:-------:|:------------- | ----------:|
|   居中  |     左对齐    |   右对齐   |
|=========|===============|============|
## 11. 加粗 **（完）**

## 12.斜体      *（完）*


 