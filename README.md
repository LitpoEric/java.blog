<!-- title: 我的JSP作业, 简单的博客 -->
<!-- category: Web -->
<!-- tag: java, jsp -->
<!-- date: 2013/12/2 -->
<!-- state: published -->
<!-- link: java.blog -->
﻿
java.blog
=========

我的作业,使用 jsp 实现的简单的博客.

截图
----

![首页截图](https://raw.github.com/WenerLove/java.blog/master/index_screenshot.png)

![登录和注册截图](https://raw.github.com/WenerLove/java.blog/master/login_screenshot.png)

<!-- more -->

关于搭建
-------

数据库使用的 h2,连接 URL 在 U5.java 里,搭建的时候根据需要修改该连接.

当前是 `jdbc:h2:tcp://localhost/~test`,使用的服务器模式.

修改为 `jdbc:h2:test` 则会使用嵌入式模式.数据表会自动创建.


使用了
------

* [bootstrap](http://getbootstrap.com/)
* [jquery](http://jquery.com/)
* [ormlite](http://ormlite.com/)
* [h2 database](http://h2database.com)
* [font awesome](http://fontawesome.io/)
* jstl,servlet
* [less](http://lesscss.org/)
* json3
* [x-editable](http://vitalets.github.io/x-editable/)

注意
----

* generate.jsp 是用于生成测试数据的

TODO
----

* 修改数据连接的获取方式,将连接保存到 `application` 上,以支持嵌入式模式,只进行一次连接
