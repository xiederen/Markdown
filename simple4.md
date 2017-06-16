# 总结

## 标题
标题前加#号 且要用一个空格隔开
一级标题#  
二级标题##  
三级标题###  
四级标题####  
五级标题#####  
六级标题######
# 一级标题 
## 二级标题 
### 三级标题 
####  四级标题
##### 五级标题 
###### 六级标题   

## 文本
普通文本，就是直接输入文字，  
要另起一段就需要在上一行的后面加两个空格<br>
使用br标签也可以换行
###单行文本

		单行文本前面加两个tab

###多行文本
		每行行首加两个tab
		每行行首加两个tab

### 部分文字高亮
文字`高亮`,文字`高亮`
### 强调
	格式：*斜体*，**粗体**，***斜粗体***
	另一种写法：_斜体_，__粗体__ ，___斜粗___ 
	
*斜体*，**粗体**，***斜粗体***  
_斜体_ ，__粗体__ ，___斜粗___ 
  


###删除线
	~~删除线~~
~~删除线~~

### 横线
hr标签
<hr>

### 缩进（引用别人的文章）
	>语言
	>>编程语言
	>>>java
	之后的文本要用一行空行隔开
> 语言
>> 编程语言
>>> java  


## 链接
	给一段文字加入超链接是[要显示的文字](链接的地址 '鼠标悬停文字')中括号[]小括号()之间不加空格  
	外部链接： [百度](https://www.baidu.com '123')
	内部（同仓库）链接：[simple3](simple3.md)
	文档内的链接：[多级列表](simple4.md#多级列表)
	
外部链接：[百度](https://www.baidu.com '123')  
内部（同仓库）链接：[simple3](simple3.md)  
文档内的链接：[多级列表](simple4.md#多级列表)


## 列表
### 无序列表
编辑的时候使用的是星号 *
* name
* age
* gender
### 有序列表
1. name
2. age
3. gender

### 多级列表
第二行开始每行行首多加一个tab  

* 语言
	* 编程语言
		* Java


## 图片
	叹号! + 方括号[图片加载不了显示的文字] + 括号(url '鼠标悬停文字') 行首必须加叹号，  
	外部图片：![百度logo](https://www.baidu.com/img/bd_logo1.png 'logo')  
	内部图片：![中奖](images/p_1.jpg)
外部图片：
![百度logo](https://www.baidu.com/img/bd_logo1.png 'logo')
内部图片：
![中奖](images/p_1.jpg)
## 代码块
我们需要在代码的上一行和下一行用``` 标记  

要实现语法高亮那么只要在 ``` 之后加上你的编程语言即可（忽略大小写）  

	```javascript
	var name = 'zs';
	console.log(name);
	```
	
```javascript
	var name = 'xr';
	console.log(name);
```
	


## 表格
	| 这 | 是 | 表 | 头 |  
	|---|---|---|---|  
	|cell1|cell2|cell3|cell4|  
	|image]|url|demo|emoji|  

| 这 | 是 | 表 | 头 |
|---|---|---|---|
|cell1|cell2|cell3|cell4|
|row2|row2|row2|row2|
|![logo][百度logo]|[百度]|demo|:smile:|

## GFM
GitHub在标准markdown语法的基础上做了修改，称为Github Flavored Markdown，简称GFM  

	task list  
	- [x] list1  
	- [ ] list2  
	- [x] list3 
	在方括号内加上x即选中状态
	 
task list
- [x] list1
- [ ] list2
- [x] list3

## emoji 表情
	:emoji code:
	:simle:  
	
:simle:  
:joy:    
:grin:  
:open_mouth:




	<!--以下是本文的链接引用-->

[百度logo]:https://www.baidu.com/img/bd_logo1.png 'logo'  
[百度]:https://www.baidu.com '123'
