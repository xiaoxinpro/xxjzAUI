#小歆记账APICloud项目(AUI前端框架)

![](http://upload-images.jianshu.io/upload_images/1568014-caeefa6ab53be35b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##简介

小歆记账AUI项目(APICloud客户端) 是一个基于APICloud + AUI的记账应用，同时兼容安卓和iOS平台，以下简称小歆记账AUI。

> GitHub：https://github.com/xiaoxinpro/xxjzAUI

小歆记账AUI数据存储部分在服务端，与[小歆记账WebApp项目](https://github.com/xiaoxinpro/xxjzWeb)共用数据库，通过Ajax与[小歆记账WebApp](https://github.com/xiaoxinpro/xxjzWeb)后台通信。其中AUI为前端框架，APICloud负责逻辑处理和云编译。

> 注意：小歆记账AUI必须与[小歆记账WebApp项目](https://github.com/xiaoxinpro/xxjzWeb)配套使用，不能单独工作。

##安装使用

###源码调试
小歆记账AUI项目包为app源码，在APICloud中新建一个项目将代码覆盖，即可调试安装。

###APP下载
小歆记账AUI还处于后期完善阶段，APP还是测试版本，iOS只能使用7天，建议下载源码自行调试安装。[点击这里下载APP](http://jz.xxgzs.org/xxjzApp/index.php/Home/Login/index/type/app)

##目录结构


    xxjzAUI  项目根目录
      ├─css                          CSS目录
      │  ├─calendar.css              日历样式文件
      │  ├─font-awesome.min.css      FontAwesome样式文件
      │  └─aui-...                   AUI样式文件
      ├─fonts                        字体目录
      │  └─fontawesome-webfont.ttf   FontAwesome字体文件
      ├─html                         HTML目录
      │  ├─about_win.html            关于窗口文件
      │  ├─add_frm.html              添加页面文件
      │  ├─chart_win.html            图表窗口文件
      │  ├─edit_win.html             编辑窗口文件
      │  ├─find_frm.html             搜索页面文件
      │  ├─find_win.html             搜索结果窗口文件
      │  ├─forget_win.html           找回密码窗口文件
      │  ├─index_frm.html            主页页面文件
      │  ├─index_win.html            主窗体文件
      │  ├─list_all_year_win.html    历年账单窗口文件
      │  ├─list_day_win.html         日账单窗口文件
      │  ├─list_win.html             月账单窗口文件
      │  ├─list_year_win.html        年账单窗口文件
      │  ├─login_frm.html            登录页面文件
      │  ├─regist_win.html           注册账号窗口文件
      │  └─user_frm.html             用户中心页面文件
      ├─icon                         图标目录
      ├─image                        图片目录
      ├─launch                       启动图片目录
      ├─script                       JS脚本目录
      │  ├─api.js                    APICloud接口文件
      │  ├─app.js                    自定义接口文件
      │  ├─base64.js                 Base64库文件
      │  ├─calendar.js               日历插件库文件
      │  ├─countUp.js                数字动画脚本文件
      │  ├─echarts.js                图表库文件
      │  └─aui-...                   AUI脚本文件
      ├─config.xml                   APP配置文件
      └─index.html                   入口文件

##开发工具

APICloud 云端一体 重新定义移动应用开发;一站式高效APP开发和管理平台,使用标准WEB技术开发跨平台APP；覆盖APP全生命周期，包括开发、API集成、测试、渠道打包、运营管理等。[www.apicloud.com](http://www.apicloud.com/)

##参考

* [APICloud](https://github.com/apicloudcom)
* [aui](https://github.com/liulangnan/aui)
* [countUp.js](https://github.com/inorganik/countUp.js)
* [echarts](https://github.com/ecomfe/echarts)
* [mobile-calendar](https://github.com/xiaoxinpro/mobile-calendar)

![](http://upload-images.jianshu.io/upload_images/1568014-5dea0b27c4182022.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)