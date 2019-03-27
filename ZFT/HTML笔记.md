HTML是由蒂姆.本尼斯李创建的
<html> 文件开始标记
<head>文件头开始标记
</head>文件头结束标记
<body>文件主题开始标记
</body>文件主题结束标记
</html>文件结束标记
文档类型声明用<!DOCTYPE>元素定义
名字空间是<html>元素的一个属性写在元素起始标签里
名字空间属性用xmlns来表示
网页头部元素<head>作用是定义页面头部的信息
其中可以包含标题元素 <meta>元素
页面元素表现形式：
1、自封闭的元素
指起始和结束使用同一个元素标签
2、可包含内容的元素
属性必须添加在元素起始标签中，用空格来分割属性与元素名称
按照属性作用可以将属性分为几类：
表现属性用来控制元素表现效果，如：元素的高度 宽度 边框 文本排列方式 语言等属性
事件属性用来添加行为，一般要结合Javascript来实现，如：onmouseover属性 onload属性
标记属性用来标记某个元素，如：ID属性 name属性
级联样式是指使用及联演示表，如：style属性 class属性
其他属性指几类属性以外的属性， 如type value属性
<a>元素中不能包含其他的<a>元素。
<pre>元素中不能包含<object> <big> <img> <small> <sub> 或<sup>元素
<botton>元素不能包含<input>  <textarea>  <lable>   <select>  <botton>   <form>    <inframe>   <fieldest>或<isindes>元素
<lable>元素中不能包含其他的<lable元素
<form>元素中不能包含其他的<form>元素