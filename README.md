#增加 By nightcat 2016-05-11

#增加Tag的sitemap,负载优化，设置只读取最近的访问次数最少的1万条记录

#负载优化,修改stemap文章的条数为一万




# BaiduSubmit
 A typecho plugin for baidu SEO

老高目测对SEO还是有一些用处的。

## 功能

提交sitemap给百度服务器，优化收录。

由于插件会在添加文章、删除文章时向百度post信息，做这些操作的时候可能会比以前慢一点。

同时支持主动推送功能，目前每天有50条限额！ ---->  对应功能  百度站长--链接提交--自动提交--主动推送

新的百度xml地图为地址为 `http://yourweb/baidu_sitemap.xml` ---->  对应功能  百度站长--链接提交--自动提交--sitemap

请在百度站长后台设置sitemap，主动推送功能将会在每次编辑完文章后主动推送，或者在百度结构化日志界面批量推送！

## 安装

将文件夹重命名为`BaiduSubmit`，然后拷贝至`usr/plugins/`下，最后在后台->插件处安装。

## 升级方法

**请先禁用插件后再升级**

## 使用

全新的日志记录功能！

![日志记录][1]


  [1]: http://www.phpgao.com/usr/uploads/2015/05/879628597.png