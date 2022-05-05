**项目背景**：在学习完HTML，CSS，JavaScript的知识后，将这些知识运用到实际项目中，完成2048小游戏。

**项目介绍**：该游戏在移动端和网页都可以运行，电脑使用上下左右按键进行操作，手机可以滑动进行操作。游戏界面是一个4x4的方格，每个方格都可能出现滑块，游戏开始时随机出现两个滑块，每个滑块的值90%可能为2，10%可能为4。每个滑块可以上下左右移动到不可移动位置，两个滑块的值相同可进行合并，顶部score会记录当前分数，分数为元来分数+合并后的值，BestScore记录有史以来最高分。当某个滑块的值为2048时，游戏胜利。当每个滑块都有值，并且相邻两个滑块无法合并时，游戏结束。

**项目技术**：

* 使用flex布局完成静态页面渲染
* 利用scss拆分css文件，并使用scss的循环和变量渲染滑块位置
* 使用prototype原型实现js对象属性和方法分离
* 利用Math.random()实现滑块动态随机添加
* 使用回调函数处理监听到键盘事件，处理滑块移动
* 使用css的transform和js的计时器延时实现滑块移动的动画效果
* 使用localStorage本地缓存保存游戏进度和当前分数