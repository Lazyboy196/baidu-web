任务一<br>完成一个HTML页面代码编写（不写CSS，不需要关注样式，只关注文档结构）
====
<br>
    任务一是基础：主要巩固熟悉一下常用标签。
[示例图](http://htmlpreview.github.io/?https://github.com/fenglinismydream/baidu-web/blob/master/%E5%B0%8F%E8%96%87%E5%AD%A6%E9%99%A2/index1.html)

任务二<br>在步骤一的代码基础上增加CSS样式代码的编写）
====
<br>
    任务二是在任务一的基础上添加样式，这是主要是练习css的基本语法定位。<br>
    这是地方在做最后表单对齐的时候遇到了点麻烦，因为之前没有接触过表单对齐，然后又通过学习表单方面的知识，学习到将表单放入table中，是一种简单的解决方法。
[示例图](http://htmlpreview.github.io/?https://github.com/fenglinismydream/baidu-web/blob/master/%E5%B0%8F%E8%96%87%E5%AD%A6%E9%99%A2/index2.html)

任务三<br>左右两栏宽度固定，中间一栏根据父元素宽度填充满，最外面的框应理解为浏览器。
====
<br>
    我是用左边左浮动，右边有浮动，中间宽度用margin实现，上下margin为0，左右margin分别为左右块的宽度。<br>
    当时以为左右块宽度只是简单的宽度，设置之后发现并不能实现，然后加上padding值之后实现。<br>
    其他的实现方式：<br>
      `'margin负值法':。<br>
  body{margin: 0; padding: 0; }
  .left , .right{ height: 300px; width: 200px; float: left;}
  .right{ margin-left: -200px; background-color: red;}
  .left{ margin-left: -100%;background-color: #080808; }
  .middle{ height: 300px; width: 100%; float: left;background-color: blue;}

    '绝对定位法':左右两栏采用绝对定位，分别固定于页面的左右两侧，中间的主体栏用左右margin值撑开距离。
     body{margin: 0; padding: 0;}
    .left , .right{top: 0;height: 300px;width: 200px;position: absolute;}
    .right{ right: 0;background-color: red;}
    .left{ left: 0; background-color: #080808;}
    .middle{ margin: 0 200px; height: 300px;background-color: blue;}`

[示例图](http://htmlpreview.github.io/?https://github.com/fenglinismydream/baidu-web/blob/master/%E5%B0%8F%E8%96%87%E5%AD%A6%E9%99%A2/index3.html)

任务四<br>灰色元素水平垂直居中，有两个四分之一圆位于其左上角和右下角。
====
<br>
    实现四分之一圆我是用正方形加border-radius:100%;实现圆，然后固定在父类坐上和右下角，在给父类加overflow:hidden;让超出父类的隐藏，只显示四分之一圆。
[示例图](http://htmlpreview.github.io/?https://github.com/fenglinismydream/baidu-web/blob/master/%E5%B0%8F%E8%96%87%E5%AD%A6%E9%99%A2/index4.html)

任务五<br>在步骤一的代码基础上增加CSS样式代码的编写
====
<br>1.头部和底部的黑色区域始终是100%宽<br>
2.页面右侧部分为固定宽度，左侧保持与浏览器窗口变化同步自适应变化<br>
3.左侧的各个模块里面的内容宽度跟随左侧整体宽度同步自适应变化<br>
4.10张图片需要永远都完整展现，所以会随着宽度变窄，从两行变成三行甚至更多，也有可能随着宽度变宽，变成一行<br>
    
    任务五：在任务二的基础上应用任务三的自适应宽度布局。<br>
    
[示例图](http://htmlpreview.github.io/?https://github.com/fenglinismydream/baidu-web/blob/master/%E5%B0%8F%E8%96%87%E5%AD%A6%E9%99%A2/index5.html)

任务六<br>通过HTML及CSS模拟报纸排版
====
<br>
   根据示例图完成效果图<br>
[示例图](https://github.com/fenglinismydream/baidu-web/blob/master/%E5%B0%8F%E8%96%87%E5%AD%A6%E9%99%A2/img/task_1_6_3.jpg)

任务七<br>实现常见的技术产品官网的页面架构及样式布局
====
<br>
   根据示例图完成效果图<br>
[示例图](https://github.com/fenglinismydream/baidu-web/blob/master/%E5%B0%8F%E8%96%87%E5%AD%A6%E9%99%A2/img/task_1_7_1.psd)

