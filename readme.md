# vnshop 商城
技术栈： vue mongodb node 
![2019-04-24-23-30-32](http://s.shudong.wang/aaa.jpg)
> 课程视频，可以联系我
https://shudong.wang/about
## 项目架构
前后分离

前端：
    使用vue cli 脚手架方式搭建

api：
    使用node express框架搭建

## 项目目录
cd vnshop
mkdir -p client note server

#### vnshop
    client #客户端代码，里面放的是vue项目工程文件

    note #搭建项目的详细笔记
        
    server #node express 代码

## 项目上线 视频上传到segmentfault 讲堂
* 01.购买流行的vps服务器教程
* 02.域名注册
* 03.域名注册商介绍godaddy.com域名注册，park.io等信息
* 04.利用xshell连接Linux Ubuntu系统详细操作方式
* 05.【全栈项目上线（vue+node+mongodb）】安装lnmp环境 nginx mysql php 环境
* 06.lnmp环境安装成功并且测试
* 07.nodejs环境安装
* 08.安装mongodb
* 09.mongodb安装测试执行mongodb shell命令
* 10.解决无法解析主机名字问题
* 11.mongodb通用解决方案
* 12.缩减版的安装php mysql Nginx node mongodb 6分钟搞定
* 13.部署项目的方式，介绍
* 14.怎么在一台服务器上部署多个站点
* 15.项目上线方案一上传文件解压文件实现
* 16.项目上线方案二从github拉取
* 17.项目上线完毕
* 18.负载均衡的概念
* 19.使用git webhooks 优雅的自动化上线vue项目（巨详细） 
* 20.git webhooks 自动化上线
* 21.搭建博客系统WordPress
* 22.搭建hexo博客
# daylog

## day1 
    00.项目初始化
    01.vue常见错误收集
    02.初始化商品组件，拆分头部，底部组件
    03.使用mock数据，配合本地的express把商品列表渲染出来
## day2
    01.让学员把自己的商城项目提交到github的vnshop项目的issue方便查看
    02.复习上周讲的商品组件
    03.使用vue-lazyload插件实现图片懒加载   
    04.使用express脚手架生成，配置nodemon和supervisor方式启动修改后不需要重启node服务
    05.使用express连接mongodb
    07.使用express通过查询mongodb数据实现goods商品列表接口
    08.使用vue请求server的goods的api，并且配置跨域成功访问
    10.商品按照价格排序的接口开发
    11.商品安装价格排序的vuejs前端实现

## day3
    01.根据价格区间筛选api实现
    02.根据价格区间筛选vue前台实现
    03.分页api接口实现
    04.配置滚动下拉加载插件
    05.vue配合下拉滚动插件，实现下载加载商品
    08.加入购物车api实现
    09.加入购物车vue前台实现

### day4
    01.复习昨天内容，对下拉加载，什么时候不加载逻辑重新分析，修复设置过滤价格分页不从新来读问题
    02.登录注册逻辑
    03.登录前台后台实现
    04.整理上午讲的前后台登录实现，详细笔记
    05.在项目前后分离的状态下，刷新页面，怎么保持用户登录，用户退出
    06.如何在vue里面优雅的解决跨域，路由冲突问题
    07.访问拦截

### day5
    01.项目调试方式，解决问题方法
    02.购物车商品数量的添加和减少，是否选中
    03.全选，全不选思路，vue前台实现
    08.在删除商品之前弹出模态框提示是否要真的删除商品

### day6
    02.设置默认收货地址
    03.选择收货地址，点击下一步到地址订单确认地址
    04.订单确认模块


### 详细内容
    1 课程规划 
    2 github操作的几个场景 
    3 把本地的仓库提交到远程 
    4 vue初识.周边资源介绍 
    5 vue.helloworl.插值，双向绑定 
    6 指令.bind if 
    7 上传代码到github上 
    8 生命周期案例详细讲解 
    9 jq在生命周期函数里面的应用 
    10 v-on事件 
    11 v-show指令 
    12 模版和渲染 
    13 插槽基本使用，具名插槽，项目中应用场景 
    14 组件1，组件2，全局组件 
    15 动态组件 
    16 props 
    17 watch监听、深度监听 
    18 filter自定义过滤器 
    19 git操作指南、把老师的的代码拉下来，并且更新代码的详细指导 
    20 自定义指令 
    21 自定义拖拽命令 
    22 vue-resource、get、post、jsonp、方式请求接口 
    23 axios 请求api的方式post 和 get区别 
    24 vue-cli项目初始化 
    25 git合并 
    26 解决问题的方式 
    27 vue项目目录的说明 
    28 vue.编译流程，webpack文件讲解 
    29 vue文件分析 
    30 vue项目入口文件分析 
    31 路由history，hash，默认激活样式，exact讲解 
    32 自定义全局激活样式,嵌套路由 
    33 路由重定向 
    34 路由传参 
    35 复习 
    36 成产环境和开发环境 
    37 解决问题的能力 
    38 在vue项目中使用axios访问接口，解决跨域问题 
    39 案例，获取知乎日报的信息，写在组件上，解决跨域，图片403问题 
    40 使用vue-axios方式访问api 
    41 vue-axios源码分析 
    42 vuex介绍 
    43 vuex在项目简单入门使用 
    44 vuex 提交 mutation paload传参 
    45 学习的方式 
    46 mutations 提交type类型 
    47 actions使用方式 
    48 getters使用方式 
    49 mapState，mapGetters,mapAction辅助函数使用 
    50 项目初始化 
    52 vue常见错误收集 
    52 初始化商品组件，拆分头部，底部组件 
    53 使用mock数据，配合本地的express把商品列表渲染出来 
    54 2017.10.20-11.51.51 
    55 提交vnshop item 地址 
    56 复习.vnshop组件 
    57 vue-lazyload.懒加载图片使用 
    58 express 脚手架生成，配置nodemon和supervisor方式启动修改后不需要重... 
    59 express 连接mongodb 
    60 对上午复习 
    61 express通过查询mongodb数据实现goods 商品列表接口 
    62 vue请求server的goods的api，并且配置跨域成功访问 
    63 开发前的，需要分析 
    64 商品按照价格排序的接口开发 
    65 商品安装价格排序的vuejs前端实现 
    66 整理商品价格排序的笔记 
    67 根据价格区间筛选api实现 
    68 根据价格区间筛选vue前台实现 
    69 分页api接口实现 
    70 配置滚动下拉加载插件 
    71 vue配合下拉滚动插件，实现下载加载商品 
    72 域名注册 
    73 表驱动法 
    74 加入购物车api实现 
    75 .加入购物车vue前台实现 
    76 解决productNum 出现bug问题 
    77 01.复习昨天内容，对下拉加载，什么时候不加载逻辑重新分析，修复设置过滤价格分页... 
    78 登录注册逻辑 
    79 前后登录实现 
    80 .整理上午讲的前后台登录实现，详细笔记 
    81 在项目前后分离的状态下，刷新页面，怎么保持用户登录，用户退出 
    82 如何在vue里面优雅的解决跨域，路由冲突问题 
    83 访问拦截 
    84 购物车列表页面渲染 
    86 项目调试方式，解决问题方法 
    86 购物车商品数量的添加和减少，是否选中 
    87 全选，全不选思路，vue前台实现 
    88 补充上午的商品数量操作的api方法 
    89 全选和反选的api 
    90 总价格实时变化 
    91 .删除购物车商品数据 
    92 在删除商品之前弹出模态框提示是否要真的删除商品 
    93 封装全局模态框组件.购物车判断登录与未登录情况的弹出不同模态框 
    94 在购物车列表页面去结账 
    95 .地址列表页面渲染