# ele
项目实训时，小组制作的，本人负责“登录页面”、“首页”、“商家列表“，内容样式参考原网址: https://github.com/bailicangdu/node-elm 
<br/>
一、 首页和商家列表使用了开放接口，直接在github上演示会有跨域问题，数据无法显示，其他页面使用静态JSON文件，无影响
<br/>
二、 用到的技术有vue.js 2.0、webpack、 vue-router、ES6、npm
<br/>
三、 个人在制作项目中遇到的问题有：
<br/>
  1.路由拦截，防止未登录的情况下，手动输入路径，用到vue-router的beforeEach()钩子解决
  <br/>
  2.keep-alive,由于首页有较多AJAX请求，所以想路由返回时，页面不刷新，保留组建状态
  <br/>
四、 通过这次项目，熟练掌握使用vue框架，切身体会到一个真正前端的项目，不只是HTML、CSS和JS，还有底层架构、打包编译等等，刷新了我对前端行业的认识。
