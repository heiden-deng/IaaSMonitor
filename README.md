# IaaSMonitor
IaaSMonitor project
* 2017-02-09:项目初始化，添加OkHttp的Jar包。
* 2017-02-09:增加了doLogin()和doGet()方法用于登陆和发起Get请求。
* 2017-02-09:增加Json.jar以及从MyEclipse将已开发的功能迁移。
* 2017-02-09:实现了登陆获取Token的功能。
* 2017-02-09:增加了ErrorResponseCodes类用于显示http的错误信息。
* 2017-02-09:增加bootstrap和jquery，调整登录和主页面的布局。
* 2017-02-09:增加了LoginJson的解析功能，将对应节点的EndpointUrl和Token相关信息保存在内存中。
* 2017-02-09:增加AngularJs，实现登录和主页面的连接，并实现了显示详情页面。
* 2017-02-09:删除ErrorResponseCodes、OpenStackInfo、Token类及相关方法。
* 2017-02-09:增加了doPost()方法HttpPostBodyMaker类用于构造HTTPPost请求的body。
* 2017-02-09:增加AngularJs，实现登录和主页面的连接，并实现了显示详情页面。
* 2017-02-10:增加createMultipleServers()、createServer()、doDelete()的Body构造方法。
* 2017-02-12:增加请求列表服务serviceListService，用于统一管理所有请求的url
* 2017-02-12:增加请求user清单，用于统一管理所有请求的user
* 2017-02-12:增加请求program清单，用于统一管理所有请求的program
* 2017-02-12:增加获取网络信息、路由信息、端口信息、子网列表、端口列表页面。
* 2017-02-12:更新了网络单元下页面的显示信息。
* 2017-02-12:修复登录失败后依然可以跳转问题;修复请求发送两次问题;
* 2017-02-13:添加对象存储分类、增加登陆时的参数项目名称、容器列表清单页面。
* 2017-02-13:增加对象存储页面的窗口遮罩,在遮罩上显示容器内的文件名及文件大小
* 2017-02-13:在HttpPostBodyMaker中增加了createUser方法。
* 2017-02-13:增加因超时跳转至登录，重新登录后，再次跳转至之前请求的页面。
* 2017-02-13:增加创建用户界面；
* 2017-02-13:增加强制刷新当前页面；
* 2017-02-14:增加用户详情页面，实现页面的跳转。
* 2017-02-14:修改网络，增加安全组、浮动IP、servers相关界面的显示功能.
* 2017-02-14:增加用户界面checkbox的全选删除功能(删除部分未写，但实现对某条记录的删除)
* 2017-02-14:增加导航栏、注销功能
* 2017-02-15:增加默认页面；增加分页功能
* 2017-02-15:增加项目和密钥对的详细信息界面。
* 2017-02-15:移除虚拟机下概况页面，建立分页服务，全局访问。
* 2017-02-16:增加首页图表(未实现真实数据显示);增加对stack的显示
* 2017-02-16:调整多个请求访问的处理方式($q.all())
* 2017-02-16:增加大数据集群模板创建虚拟机功能,修改成主从的创建方式。
* 2017-02-16:增加实例详情
* 2017-02-17:增加实例日志信息
* 2017-02-17:增加网络创建虚拟机
* 2017-02-18:增加stack详情以及链接界面
* 2017-02-18:增加剩余的链接跳转功能
* 2017-02-18:完成页面的样式布局、跳转链接。
* 2017-02-20:修改冲突。
* 2017-02-20:增加遮罩效果，用于请求时间过长。
* 2017-02-20:更新Stack的创建模板、增加同步用户的功能
* 2017-02-20:解决部署tomcat请求链接错误问题。
* 2017-02-20:将左侧的菜单精简成2个大菜单，第一个为【概况】且无子菜单，第二个为【虚拟机】且子菜单为[栈]。
* 2017-02-20:移除栈清单页面中，表格最后一列的操作功能。
* 2017-02-20:将栈详情页面中每个表格的最后一列编辑功能去除掉。
* 2017-02-20:栈详情页面事件标签表格中，访问有些栈资源会提示不存在问题，需要将这些不存在的链接去除掉。
* 2017-02-20:将栈详情页面表格显示的内容与dashboard进行对应，将日期显示进行格式化，显示成"yyyy-MM-dd hh:mm:ss"形式。
* 2017-02-20:分别对admin管理员和testsw普通用户进行功能测试，验证是否因角色不同，导致某些功能不能操作。
* 2017-02-20:增加端口详情界面。。
* 2017-02-20:整合port以及stack详情页面
* 2017-02-21:完成同步用户的功能、增加请求类型的文字提示、增加创建Stack后返回IP地址的功能（死循环）
* 2017-02-22:增加DispatcherController用于分发来自paas的请求
* 2017-02-23:调整本地存储时token等的名称，防止冲突。
* 2017-02-23:修复因超时导致页面重新登录，跳转失败问题
* 2017-02-23:获取概况界面的显示参数。
* 2017-02-23:调整概况显示方式
* 2017-02-23:增加_en结尾的英文版网页，修正创建多个集群时虚拟机重名的问题。
* 2017-02-23:修复因getEndPointService.flushPoint请求延迟，导致页面获取endpoint为null问题。
* 2017-02-23:增加表格排序功能
* 2017-02-23:增加表格排序功能
* 2017-02-24:增加表格表头排序时样式提示
* 2017-02-24:添加表格条件筛选功能(根据输入的条件自动筛选,属于前台筛选)
* 2017-02-24:修复创建集群失败后不退出程序的问题
* 2017-02-24:增加CSV文件导出
* 2017-02-24:增加控件图标
* 2017-02-28:调整创建虚机的响应内容格式
* 2017-02-28:调整创建虚机后的请求放至子线程，同时调整请求的频率至5s一次。
* 2017-03-02:完成大数据模板的接口调试
* 2017-03-06:增加同步用户时为每个Project添加admin权限的admin用户。
 