# jingdata
### 需要注意
###### 1.
第一阶段先爬取所有项目的id，由于该网站的项目列表页由纯JS加载，想要提升单位时间内的爬取速度，<br>**尝试用抓包的方式获取服务器请求，分析账号限制有多大**，保存id到数据库
###### 2.
第二阶段再根据数据库的id获取有价值的信息
###### 3.
部署logging模块，分别输出不同级别的日志，随时准备**停止爬虫**，优化代码
