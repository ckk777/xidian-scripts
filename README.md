xidian-scripts
==============

这是什么?
-------


只是一些实用的小脚本
	
	* get_xidian_news: 获得近期校内的新闻
	
	* get_pay_info: 获得自己校园网流量使用情况
	
	* get_grades: 查询自己的成绩

	
Setup
-------

我在Mac Os X上使用Python 2.7.2, Linux应该也没问题:)

我假定你已经安装好了python和[pip](http://www.pip-installer.org/en/latest/, "Pip")


1. 安装依赖:

	pip install requests, lxml

2. 如果要使用get_pay_info, 请安装 [tesseract](http://code.google.com/p/tesseract-ocr/)
	
3. 在get_pay_info.py, get_grades.py设置自己的学号和密码

4. 在get_xidian_news.py中的DAY输入你想获得最近几天的消息

5. 没有第5步


Usage
-----
完全由你决定如何使用:)

1. 手动执行
2. 把get_pay_info.py加到shell启动脚本中
	![](http://i.imgur.com/A227l.png)
3. 结合grep查询指定科的成绩
 	![](http://i.imgur.com/h4iKJ.png)
4. 自己定制啦:)



最后
-------
欢迎pull requests







