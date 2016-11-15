将MCMS项目源码导入eclipse；
创建数据库db-mcms-open,注意：数据库使用utf-8编码，导入doc/db-mcms-open.sql备份文件；
修改src\main\resources\config.properties文件中的数据库设置参数；
后台访问地址：http://+ip地址（或localhost）+tomcat端口+项目发布名/ms/login.do 必需先访问后台界面再访问前台界面
前台访问地址：http://+ip地址（或localhost）+tomcat端口+项目发布名如果发布的地址不是http://localhost:8080/mcms，先在后台生成静态页面再进行访问
管理员账号，用户名：msopen 密码：msopen


核心框架：Spring Framework 4
安全框架：Apache Shiro 1.2
视图框架：Spring MVC 4
任务调度：Spring Task 4
持久层框架：MyBatis 3
数据库连接池：Alibaba Druid 1.0
日志管理：SLF4J 1.7、Log4j
JS框架：jQuery 1.10
CSS框架：Twitter Bootstrap 2.3.1。
富文本：Ueditor


标签化建站：不需要专业的后台开发技能，只要使用系统提供的标签，就能轻松建设网站；
html静态化：系统支持全站静态化；
跨终端：站点同时支持PC与移动端访问，同时会自动根据访问的终端切换到对应的界面，数据由系统统一管理；
海量模版：铭飞通过MStore（MS商城）分享更多免费、精美的企业网站模版，降低建站成本；
丰富插件：为了让MCms适应更多的业务场景，在MStore用户可以下载对应的插件，如：站群插件、微信插件、商城插件等；
每月更新：铭飞团队承诺每月28日为系统升级日，分享更多好用等模版与插件；
文档丰富：为了让用户更快速的使用MCms系统进行开发，铭飞团队持续更新开发相关文档，如标签文档、使用文档、视频教程等；