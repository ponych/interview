h1. 基础题
#. 用php 输出昨天的日期
#. error_reporting 值 , display_errors On
#. 获得客户端的 ip
#. php / js  数组/ hash 的 遍历
#. jquery 把所有 class为 digit 的 input 的非空值 取出，组成一个 hash
#. 写一个jquery plugin， $(dom).red() ,就像 $(dom).show(); 类似
#. php 面对对象 的魔术方法( magic method ) 举例
#. 如何删除 cookie
#. 
#. http status code http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html
#. 附加: http 请求 类别 http://www.w3.org/Protocols/rfc2616/rfc2616-sec9.html
#. 怎样 做页面跳转
#. ubuntu & centos & archlinux 安装软件包的命令

h2. 算法题

#. js trim 函数 return str.replace(/^\s*(.*?)\s*$/ , "$1")

SQL

DROP TABLE IF EXISTS mytree;
CREATE TABLE mytree (
id INT(10) AUTO_INCREMENT PRIMARY KEY,
title VARCHAR(50) ,
rgt INT(10),
lft INT(10)
);

INSERT INTO mytree 
(`title`,`lft` ,`rgt` )
VALUES 
('中国' ,1, 10),
('北京' ,2, 5),
('海淀' ,3 ,4),
('浙江' ,6,9),
('杭州' ,7,8);

一句SQL 取出带层级结构 的数据


h3.  知识范围

#. 使用过哪些 linux 版本，有什么好处 - 使用过 vim 吗?  文字替换 jason -> john
#. 用过什么版本控制系统
#. <script src="1.js" >alert(1);</script> 见: http://www.w3.org/TR/1999/REC-html401-19991224/interact/scripts.html#edef-SCRIPT