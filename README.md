# 演示图片
<img src="https://date.clost.net" width = "200" height = "200" align=center />

# 介绍
实时更新日期的图片的静态网页，每天以图片显示今天的日历。你可以插入到某个页面中，运用这个链接实现动态日历。创作初心仅仅想在notion中的todolist中插入动态日历。但是无法用插入图片实现，因为其中包含js资源，所以将其转化为php格式，用embed命令插入页面实现动态日历。<br>后来解决了这个问题，将js资源删除并使用php调用网页，从而完美实现将动态日历插入notion中。如果仍无法在notion显示，请记得关闭伪静态。


## 演示网址
由于php格式更加先进，现已转换php在线日历，由本人服务器支撑。<br>
php格式：https://date.clost.net<br>
[原作者](https://github.com/edent)的svg格式：https://shkspr.mobi/svg/calendar.svg


## 快速部署
新建一个网站，将代码中的部分复制粘贴到你的index.php即可。或者插入我的链接https://date.clost.net 即可使用，比如：
在你需要插入的部分插入
`![](https://date.clost.net)`或者`<img src="https://date.clost.net" width = "200" height = "200" align=center />`其中width为宽度，height为高度，align为位置left/center/right。

## 其他说明
由于是纯静态网站，你可以运用cf-workers、github page、netfly、vercel等实现无服务器搭建。

## 来源
https://github.com/edent/Dynamic-SVG-Calendar-Icon

## 鸣谢
[edent](https://github.com/edent)<br>
以及待添加的你


1. a - "am" 或是 "pm"
2. A - "AM" 或是 "PM"
3. d - 几日，二位数字，若不足二位则前面补零; 如: "01" 至 "31"
4. D - 星期几，三个英文字母; 如: "Fri"
5. F - 月份，英文全名; 如: "January"
6. h - 12 小时制的小时; 如: "01" 至 "12"
7. H - 24 小时制的小时; 如: "00" 至 "23"
8. g - 12 小时制的小时，不足二位不补零; 如: "1" 至 12"
9. G - 24 小时制的小时，不足二位不补零; 如: "0" 至 "23"
10. i - 分钟; 如: "00" 至 "59"
11. j - 几日，二位数字，若不足二位不补零; 如: "1" 至 "31"
12. l - 星期几，英文全名; 如: "Friday"
13. m - 月份，二位数字，若不足二位则在前面补零; 如: "01" 至 "12"
14. n - 月份，二位数字，若不足二位则不补零; 如: "1" 至 "12"
15. M - 月份，三个英文字母; 如: "Jan"
16. s - 秒; 如: "00" 至 "59"
17. S - 字尾加英文序数，二个英文字母; 如: "th"，"nd"
18. t - 指定月份的天数; 如: "28" 至 "31"
19. U - 总秒数
20. w - 数字型的星期几，如: "0" (星期日) 至 "6" (星期六)
21. Y - 年，四位数字; 如: "1999"
22. y - 年，二位数字; 如: "99"
23. z - 一年中的第几天; 如: "0" 至 "365"
