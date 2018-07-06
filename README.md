# Myscroll.js
> 👽 一款基于Jquery的无缝轮播图插件，小巧轻量，简单的api利于新手使用。

## 特性
 + 无缝轮播，任意两张图片切换无缝
 + 小巧轻量
 + 使用简单,易于上手
 + HTML结构拓展性高

## 效果展示
![qrcode.png](https://raw.githubusercontent.com/MingShined/myscroll.js/master/images/example.png)
### [预览地址](http://www.jq22.com/yanshi17444)

## 使用示例
    $('#banner1').myscroll();

## API
    1.picEl: $('#move'),  图片父级，不传默认为banner内第1个div
    2.ctrlEl: $('#ctrl'),  控制条父级，包括小圆点和左右箭头，不传默认为banner内第2个div
    3.libs: true,  是否创建底部小圆点，true || false,不传默认true
    4.arrows: true,  是否创建左右箭头，true || false,不传默认true
    5.autoPlay: true,  是否自动播放，true || false,不传默认true
    6.time: 1000,  自动播放间隔时间，true || false,不传默认2000
    7.speed: 400,  图片切换速度，不传默认400
    8.effect: 'left',  轮播的改变方式 top||left||fade，不传默认left
    9.hover: false  是否移入banner显示左右箭头 true || false 不传默认true

## 兼容
1. IE7+
2. Chrome
3. Firfox
4. 其他主流浏览器

## 个人联系方式

> **QQ** 996578843 
> **注** 仅用于用于反馈交流 请勿骚扰哦 