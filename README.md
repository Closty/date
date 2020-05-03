# 介绍
实时更新日期的图片的静态网页，每天以图片显示今天的日历。你可以插入到某个页面中，运用这个链接实现动态日历。创作初心仅仅想在notion中的todolist中插入动态日历。但是无法用插入图片实现，因为其中包含js资源，所以将其转化为html格式，用embed命令插入页面实现动态日历。<br>后来由linmi很巧妙地解决了这个问题，将js资源删除并使用php调用网页，从而完美实现将动态日历插入notion中。如果仍无法在notion显示，请记得关闭伪静态。


## 演示网址
由于php格式更加先进，现已转换php在线日历，由本人服务器支撑。<br>
php格式：https://date.clost.net<br>
或使用由linmi服务器支持的php格式：https://linmi.cc/calendar<br>
[原作者](https://github.com/edent)的svg格式：https://shkspr.mobi/svg/calendar.svg


## 快速部署
新建一个网站，将[代码中的部分](https://github.com/Closty/date/blob/master/index.html)复制粘贴到你的index.html即可。

## 其他说明
由于是纯静态网站，你可以运用cf-workers、github page、netfly、vercel等实现无服务器搭建。

## 来源
https://github.com/edent/Dynamic-SVG-Calendar-Icon

## 鸣谢
[edent](https://github.com/edent)<br>
[linmi](https://github.com/linmi)<br>
以及待添加的你
