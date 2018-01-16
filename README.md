# 一些遇到的tips #

多看看别人的代码总会体会很多，一些写法，规范是很值得自己学习的，这里就记录下我在
他处看到的让我觉得一亮的东西，深浅不一哈:relaxed:

## 一个浏览器事件兼容的小判断 ##

    const tap = 'ontouchstart' in window
    ? 'touchstart'
    : 'click';

>其实就是个判断语句

1. 注意分行的写法
2. 事件名直接是window对象的属性