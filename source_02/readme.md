 # 1、xHtml的语法规范
1. HTML中不区分大小写,但是我们一般都使用小写
2. HTML中的注释不能嵌套
3. HTML标签必须结构完整，要么成对出现，要么自结束标签  
	_浏览器尽最大的努力正确的解析页面，你所有的不符合语法规范的内容，浏览器都会为你自动修正，但是有些情况会修正错误_
4. HTML标签可以嵌套，但是不能交叉嵌套
5. HTML标签中的属性必须有值，且值必须加引号(双引号单引号都可以)

# 2、CSS语法
1. 语法格式    
	   选择器 声明块
* 选择器
>  通过选择器可以选中页面中指定的元素，并且将声明块中的样式应用到选择器对应的元素上
* 声明块
>  声明块紧跟在选择器的后边，使用一对{}括起来
>	* 声明块中实际上就是一组一组的名值对结构，这一组一组的名值对我们称为声明
>	* 在一个声明块中可以写多个声明，多个声明之间使用;隔开
>	* 声明的样式名和样式值之间使用:来连接

# 3、块元素和内联元素
* 块元素
> * 所谓的块元素就是会独占一行的的元素,无论他的内容有多少,他都会独占一整行。
> * div就是一个块元素，p h1 h2 h3 ...
> * div这个标签没有任何语义，就是一个纯粹的块元素，并且不会为它里边的元素设置任何的默认样式。
> * div元素主要用来对页面进行布局的
* 内联元素
> * 所谓的行内元素，指的是只占自身大小的元素，不会占用一行
> * span是一个内联元素（行内元素）	,常见的内联元素：a img iframe span
> * span没有任何的语义，span标签专门用来选中文字，然后为文字来设置样式
	   块元素主要用来做页面中的布局，内联元素主要用来选中文本设置样式，
* 说明  				
	  一般情况下只使用块元素去包含内联元素，而不会使用内联元素去包含一个块元素  
	   _a元素可以包含任意元素(块元素以及内联元素)，除了他本身_  
	   _p元素不可以包含任何块元素_