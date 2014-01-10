kevin
=====
---v5kevin作业展示项目

------
第四小结视频笔记
===
mysql -uroot -p:  有密码的数据库；
- 
- 1.show databases； 查看数据库;
- 2.create database v5；建立数据库v5;
- 3.use v5 进入到v5这个库然后才能建表;
- 4.create table test；建立表test;
- 5.错误位置 看near后面的就行了;
- 6.
	create table news(
		id int primary key auto_increment,
		title char(100),
		content text
	) chaset utf8;

- 7.查看表结构 desc news;
- 8.