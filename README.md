# web_frame
springmvc +spring+ mybaits  SSM

A 集成代码生成器 [正反双向](单表、主表、明细表、树形表，开发利器)+快速构建表单; 
  freemaker模版技术 ，0个代码不用写，生成完整的一个模块，带页面、建表sql脚本，处理类，service等完整模块

B 集成阿里巴巴数据库连接池druid; 数据库连接池  阿里巴巴的 druid。Druid在监控、可扩展性、稳定性和性能方面都有明显的优势

C 集成安全权限框架shiro ; Shiro 是一个用 Java 语言实现的框架，通过一个简单易用的 API 提供身份验证和授权，更安全，更可靠

D 集成ehcache 分布式缓存 ;
  是一个纯Java的进程内缓存框架，具有快速、精干等特点,广泛使用的开源Java分布式缓存。

E 集成微信接口开发; 
  
F 图片爬虫技术； 
  
G  SQL 编辑器, 支持复杂sql语句，生成报表，可以导出excel；

H websocket及时通讯技术；（即时聊天、及时站内信并声音提醒、实时在线管理、websocket及时刷新页面）;

I redis 工具类接口;   

G 多数据源（支持同时连接无数个数据库，可以不同的模块连接不同数的据库）


//-------------------------------------------------------------------------------------------------------------------------

1. 模块化、服务化，流程化，耦合度低、扩展性好，灵活度高，工具类封装完整，干净利索，调用简单方便 
2. 提供Rest服务，支持APP手机应用(android和ios)接口、php、.net、易语言、VB等第三方接口调用 
3. 全新高大尚HTML5+css3.0+bootstrap响应式开发界面UI，( 手机 PC 平板 截图在下面)、前沿.  spring restful 风格 
4. 框架搭建完善成熟，在此基础上做过很多项目，系统具有并发处理、分布式、稳定性。 
5. 系统功能完善，此为框架平台，文档、注释齐全，提供技术支持，专门供二次开发 
6. 在此基础上可二次开发(OA、ERP、CRM ,医疗管理、金融、网站后台、APP后台、电子商务、商城(赠送UI)等等 

系统模块 ---------------------------------------------------------------------------------------------------------------------

1.   权限管理：点开二级菜单进入三级菜单显示 角色(基础权限)和按钮权限
      角色(基础权限): 分角色组和角色,独立分配菜单权限和增删改查权限。
      按钮权限: 给角色分配按钮权限。
2.   按钮管理：自定义按钮管理，维护按钮权限标识等
3.   菜单管理：无限级别自定义菜单，自定义菜单图标，业务菜单和系统菜单分离，菜单状态显示隐藏（递归处理）
4.   数据字典：无限级别，支持多级别无限分类。内设编号，排序等
5.   组织机构：无限级别，公司or部门管理
6.   在线管理：websocket技术，实时检测在线用户列表，统计在线人数,可强制用户下线 同一用户只能在一个客户端登录
7.   系统用户：对各个基本的用户增删改查，单发、群发站内信邮件短信，导入导出excel表格，批量删除
8.   会员管理：对前台用户管理，分配会员级别，到期时间，状态，联系信息等资料
9.   代码生成：生成完整的模块代码，并保留生成记录模版，可复用 （超强悍开发利器） 
      正向生成:  生成完整的模块，页面、处理类、service层、myabaits的xml 建表的sql脚本等
      反向生成:  任意连接其它数据库(mysql、oracle、sqlserver)，根据表反射生成本系统的模块
10. 性能监控：监控整个系统的性能，SQL监控，SQL防火墙，URL监控，SPRING监控，SESSION监控等
11. 接口测试：POST or GET 方式检测系统接口，参数加密，json返回结果，计算服务器响应时间
12. 发送邮件：单发，群发邮件  
13. 置二维码：生成二维码图表保存到服务器 or  解析读取二维码内信息 
14. 图表报表：柱状图、饼状图、折线图、各种图表大全
15. 地图工具：打开地图, 鼠标点击地图某位置获取经纬度坐标，根据经纬度计算两点距离
16. 打印测试：页面打印预览测试
17. 图片管理：对批量上传的图片统一管理 ，点击放大，可打开多个，自由切换，绚丽预览效果
18. 图片爬虫：输入某网址，爬出其图片显示在页面上，可以放大预览。可保存到服务器上，到图片管理里面
19. 站内信：收信箱和发信箱， websocket技术通讯技术做的及时收信提醒，可配置语音提示来信 
20. 系统设置：修改系统名称，邮件服务器配置，短信账号设置，图片水印配置，微信配置
21. 及时聊天：打开聊天窗口，可群聊、一对一聊天
22. 表单构建：拖拽式快速自定义构建表单，组建元素丰富，有富文本、上传控件、下拉框等等
23. 主附结构：提供一个主表和明细表模块的例子(用本代码生成器生成的)
24. 员工管理：和组织机构部门管理，可以绑定登录系统用户，授权数据权限

数据库管理-------------------------------------------------------------------------------------------------------------------

25. 数据库备份：可备份单表、整库，支持本地和远程数据库备份(java界面编程技术，socket编程技术)
26. 备份定时器：quartz 2.2 强大的任务调度，多线程备份数据库，任务启动关闭异步操作
27. 数据库还原：历史备份记录，还原数据库 or 单表 ，统计备份时间和文件大小
28. SQL编辑器：强大的SQL编辑器，支持编辑语句复杂查询语句，生成动态报表，可导出excel
//-------------------------------------------------------------------------------------------------------------------------

菜单权限：分配给每个角色不同的菜单权限, 每个角色看到的菜单不同，无限级别菜单
按钮权限：独立分配不同的角色不同的功能权限，增删改查权限分配具体到不同的菜单，自定义按钮管理
支持多用户分权限管理后台,  权限具体到不同的菜单不同的按钮


##技术点
1. 导出 导入 excel 文件 
2  导出word文件 
3. IO 流上传下载文件 
4. 群发邮件，可以发html、纯文本格式，可以发给任意邮箱(实现批量发送广告邮件) 
5. 群发or单独 发送短信，支持两种第三方短信商接口 
6. spring   aop  事务处理 
7. 代码生成器 (freemarker)， 代码 zip 压缩打包 
8. MD5加密 SHA加密（登录密码用此加密）接口加密身份校验 
9. 数据库连接池  阿里的 druid。Druid在监控、可扩展性、稳定性和性能方面都有明显的优势,支持并发  
10.加入安全框架 shiro (登录授权)(session管理)  
11.根据汉字 解析汉字的全拼(拼音)和首字母(导入excel到用户表，根据用户的汉字姓名生成拼音的用户名)  
12.app接口@ResponseBody（支持与其它语言数据交互） 
13.极光推送 (推送给APP及时消息，APP不启动也能收到) 
14.微信接口(身份验证，文本、图文回复等) 微信远程控制服务器重启、锁定、其它应用程序 
15.java Quartz2.2 任务调度  
16.java websocket 即时通讯技术，点对点，群聊，单聊 
17.Lucene全文检索(在赠送的项目中) 
18.Base64传输图片 
19.图片加水印(图片水印，文字水印） 
20.生成 or  解析 二维码 
21.HTML5 + JAVAEE  WebSocket 通信技术，WebSocket 验证用户登录，强制某用户下线 
22.批量异步上传图片，可预览，有进度条，支持拖拽上传(百度webuploader )。列表动态滑动放大展示。 
23.ehcache 自定义二级缓存 ，选择缓存存放目录，处理并发，增加系统性能 
24.服务器内部GET POST 请求 
25.uploadify 上传插件，单条、批量上传多线程，带进度条，异步，图片、视频, 其它文件格式均可上传 
26.地图选点获取经纬度坐标，根据俩经纬度计算距离 
27.tab标签页面功能，标签自由切换，不重复操作数据库 
28.站内信语音提醒，js控制音频播放
29.百度富文本编辑器，可上传图片
30.网页爬虫技术，可根据网页地址爬取图片和网页标题等信息(爬取某商城图片保存本服务器) 
31.redis 技术 
32.多数据源技术  
