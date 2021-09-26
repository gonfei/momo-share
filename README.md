## 简介

提高墨墨背单词单词上限。

每日分享上限20个。于是我就写了一个自动刷访问量的脚本。大体思路是：

1. 去免费代理ip网站爬代理
2. 利用代理访问文章
3. 增加访问量

## 版本

**momo-share4.0**之前用的是模仿人为操作去访问网页，这种方法更真实也更有效，缺点是速度慢。

**momo-share4.0**改用异步访问网页，以提高访问速度，亲测有效。

`4.0之前`

需要安装：

`pip install selenium`  // 需要安装浏览器驱动 该项目用的chrome浏览器

`chromedriver(对应浏览器版本下载)：`[下载地址](http://npm.taobao.org/mirrors/chromedriver)

`pip install requests`

`pip install bs4`

用到的库：bs4、random、requests、re、selenium、time

`4.0`

最近学习异步库所以借此机会将代码改用异步操作访问页面，经过一天的时间证明此方法有效可用。

在前期开发此脚本时，想过用requests去访问页面，结果事与愿违，此方法并没有被墨墨记录访问。因此就想着用selenium模仿人为操作，结果可想而知，但速度缺令人着急。可能是之前抓取代理个数太多原因，所以目前就改用异步脚本。

需要安装：

`pip install asyncio`

`pip install aiohttp`

`pip install bs4`

用到的库：re、random、asyncio、bs4、aiohttp



## 声明

代码中有很多代码可以优化的地方，目前功能可用加上学务繁忙，就先挂个坑等有机会再填。也非常欢迎，学习本项目的道友指正和更改，提高本项目内容质量。

本项目仅用于个人学习测试使用，勿用于非法用途，由于其他用途所产生的一切不良后果本人概不负责。



