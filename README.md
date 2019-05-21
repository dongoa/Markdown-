# Markdown简易教程
## 基础语法
### 标题
Markdown支持6种级别的标题，与html标签h1~h6对应。  
```
# h1
## h2
### h3
#### h4
##### h5
###### h6
```
# h1
## h2
### h3
#### h4
##### h5
###### h6
除此之外，Markdown支持另一种标题展现形式。  
```
一级标题
===
二级标题
---
```
一级标题
===
二级标题
---
### 高亮显示
```
> 这段文字高亮显示
```
> 这段文字高亮显示
### 插入链接或图片
```
[点击跳转至百度](http:www.baidu.com "百度")
![图片](./1.jpg "图片")
```
[点击跳转至百度](http:www.baidu.com "百度")  
![图片](./1.png "图片")  
如下给图片加上超链接的代码：
```
[![baidu](http://www.baidu.com/img/bdlogo.gif "百度Logo")](http:www.baidu.com "百度")
```
[![baidu](http://www.baidu.com/img/bdlogo.gif "百度Logo")](http:www.baidu.com "百度")
### 列表
Markdown支持有序列表和无序列表两种形式：  
+ 无序列表使用*或+或-标识，多级列表就是多加一个tab。
+ 有序列表使用数字加.标识
```
+ 蔡徐坤
	- 唱跳
	- Rap
	- 篮球
1. 蔡徐坤
 1. 唱跳
 2. Rap
 3. 篮球
```
+ 蔡徐坤
	- 唱跳
	- Rap
	- 篮球
1. 蔡徐坤
   1. 唱跳
   2. Rap
   3. 篮球  

Markdown只关注第一个列表代码的数字编号，例如第一个编号是3，第二个编号为4，指定了第一个编号，后面的编号错误也没有关系。
### 缩进
```
>一级
>>二级
>>>三级
```
>一级
>>二级
>>>三级
### 分隔线
```
***
---
```
***
---
产生分隔线的语法要求比较松，符号之间添加空格也可以。
### 强调
文字强调使用反斜杠, 使用单一符号标记的效果是斜体，使用两个符号标记的效果是加粗
```
`文字强调`
*斜体*
_斜体_
**加粗**
__加粗__
```
`文字强调`  
*斜体*  
_斜体_  
**加粗**  
__加粗__  
## 高级用法
### 插入代码块
插入代码块需要至少两个以上反引号进行包裹。  
\`\`\`
function(){
	console.log("Chicken you are too beautiful!");
}
\`\`\`
```
function(){
	console.log("Chicken you are too beautiful!");
}
```
### 插入表格
```
表头|条目一|条目二
:---:|:---:|:---:
项目|项目一|项目二
```
表头|条目一|条目二
:---:|:---:|:---:
项目|项目一|项目二
## 其他
### 特殊符号处理
如下字符需要加反斜杠转译：  
\\   反斜线  
\`   反引号  
\*   星号  
\_   底线  
\{\}  花括号  
\[\]  方括号  
\(\)  括弧  
\#   井字号  
\+   加号  
\-   减号  
\.   英文句点  
\!   惊叹号  
### 换行
需要在结尾处添加两个以上空格。  
### 删除线
```
~~要删除的文字~~
```
~~要删除的文字~~
### 单行文本和多行文本
在文字前添加一个tab
```
	多行文本
	多行文本
```
	多行文本
	多行文本
### 给文字上色
Markdown其实就是一种易于编写的普通文本，只不过加入了部分渲染文本的标签.
<div style='color:red;'>dasda</div>
< iframe height=’265’ scrolling=’no’ title=’Fancy Animated SVG Menu’ src=’http://codepen.io/jeangontijo/embed/OxVywj/?height=265&theme-id=0&default-tab=css,result&embed-version=2' frameborder=’no’ allowtransparency=’true’ allowfullscreen=’true’ style=’width: 100%;’>
:smile:  
H~2~O (需在设置中打开该功能)  
X^2^(需在设置中打开该功能)  
==高亮==(需在设置中打开该功能)  
\下划线  
\td_simon@outlook.com  
[^1].  
$$    
\mathbf{V}_1 \times \mathbf{V}_2 = \begin{vmatrix}  
\mathbf{i} & \mathbf{j} & \mathbf{k} \  
\frac{\partial X}{\partial u} & \frac{\partial Y}{\partial u} & 0 \  
\frac{\partial X}{\partial v} & \frac{\partial Y}{\partial v} & 0 \  
\end{vmatrix}  
$$   
- [ ] 不勾选  
- [x] 勾选  