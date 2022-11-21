# 1.Markdown学习
## 1.1 Markdown文字
Markdown标题使用1-6个井号(#), 对应 1-6 级标题。
//# 这是一级标题
//## 这是二级标题
//### 这是三级标题
//#### 这是四级标题
//##### 这是五级标题
//###### 这是六级标题
* 斜体用一个*号包起来
*这是倾斜的文字*
* 加粗用两个*号包起来 
**这是加粗的文字**
* 斜体加粗用三个*号包起来
***这是斜体加粗的文字***
* 删除线用两个~~号包起来
~~这是加删除线的文字~~
## 1.2 Markdown块引用
* Markdown 使用>字符作为块引用.
> 这些是一块被引用的内容。
## 1.3 Markdown列表
* Markdown 支持有序列表和无序列表两种。
无序列表使用星号*,加号+, 和连字符-.上一级和下一级之间隔三个空格即可列表嵌套。
* 1 
* 2
* 3
   * a
   * b
   * c
- a   
- b
- c
+ 1
+ 2
+ 3
## 1.4 Markdown水平线
如果一行中只有三个以上的连字符-, 星号*, 或者下划线_则会在该位置生成一个hr标签. 星号和连字符之间的空格也是允许的.
********
分割线
--- 
分割线
___
图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
## 1.5 Markdown超链接
[超链接名](超链接地址 "超链接title")
[百度](https://baidu.com)
## 1.6 Markdown代码块
* 单行代码：代码使用反引号包起来。
`function(){alert("hello")}`
* 代码块：代码用三个反引号包起来，且反引号单独占一行。
```
    function fun(){
         echo "这是一句非常牛逼的代码";
    }
    fun();
```

# 2.HTML学习
## 2.1 HTML简介
* [HTML简介](./source/html/1.HTML简介.html "HTML简介")
## 2.2 HTML基本语法
* [HTML基本语法](./source/html/2.HTML基本语法.html "HTML基本语法")
## 2.3 HTML常用标签
* [HTML常用标签](./source/html/3.HTML常用标签.html "HTML常用标签")
## 2.4 HTML列表
* [HTML列表](./source/html/4.HTML列表.html "HTML列表")
## 2.5 HTML表格
* [HTML表格](./source/html/5.HTML表格.html "HTML表格")
## 2.6 HTML表单
* [HTML表单](./source/html/6.HTML表单.html "HTML表单")
## 2.7 HTML5新增元素
* [HTML5新增元素](./source/html/7.HTML5新增元素.html "HTML5新增元素")
## 2.8 HTML5-video元素
* [HTML5-video元素](./source/html/8.HTML5-video元素.html "HTML5-video元素")
## 2.9 HTML5-audio元素
* [HTML5-audio元素](./source/html/9.HTML5-audio元素.html "HTML5-audio元素")

# 3.CSS学习
## 3.1 CSS-基础语法
* [CSS-基础语法](./source/css/1.CSS-基础语法.html "CSS-基础语法")
## 3.2 CSS-元素类型
* [CSS-元素类型](./source/css/2.CSS-元素类型.html "CSS-元素类型")
## 3.3 css字体样式
* [CSS-字体样式](./source/css/3.CSS-字体样式.html "CSS-字体样式")
## 3.4 css文本样式
* [CSS-文本样式](./source/css/4.CSS-文本样式.html "CSS-文本样式")
## 3.5 CSS-伪类和伪元素
* [CSS-伪类和伪元素](./source/css/5.CSS-伪类和伪元素.html "CSS-伪类和伪元素")
## 3.6 CSS-盒子模型
* [CSS-盒子模型](./source/css/6.CSS-盒子模型.html "CSS-盒子模型")
## 3.7 CSS-水平居中
* [CSS-水平居中](./source/css/7.CSS-水平居中.html "CSS-水平居中")
## 3.8 CSS-背景样式
* [CSS-背景样式](./source/css/8.CSS-背景样式.html "CSS-背景样式")
## 3.9 CSS-定位样式
* [CSS-定位样式](./source/css/9.CSS-定位样式.html "CSS-定位样式")
## 3.10 CSS-浮动样式
* [CSS-浮动样式](./source/css/10.CSS-浮动样式.html "CSS-浮动样式")
## 3.11 CSS-transform
* [CSS-transform](./source/css/11.CSS-transform.html "CSS-transform")
## 3.12 CSS-transition
* [CSS-transition](./source/css/12.CSS-transition.html "CSS-transition")
## 3.13 CSS-Flex布局
* [CSS-Flex布局](./source/css/13.CSS-Flex布局.html "CSS-Flex布局")
## 3.14 CSS-Grid布局
* [CSS-Grid布局](./source/css/14.CSS-Grid布局.html "CSS-Grid布局")
## 3.15 CSS3-新增属性
* [CSS3-新增属性](./source/css/15.CSS3-新增属性.html "CSS3-新增属性")
## 3.16 CSS-小米呼吸列表
* [CSS-小米呼吸列表](./source/css/16.CSS-小米呼吸列表.html "CSS-小米呼吸列表")
## 3.17 CSS-定位练习
* [CSS-定位练习](./source/css/17.CSS-定位练习.html "CSS-定位练习")

# 4.静态页面项目结构
-index.html 首页
css 
   -normalize.css 浏览器重置样式
   -common.css 常用通用样式
js
   -tool.js 工具类
   -util.js 工具类
images 存放通用的图片
   -favicon.ico 网址图标
videos 存放视频文件
font 存放字体图标














