 一个Vue的Vuex版项目：重构CnodeJS社区

**涉及了Vuex的 State，Getters，Mutations，Actions**

```bash
npm install
npm run dev
```

(默认用的是8080端口)

论坛项目主要为论坛帖子信息展示，分为主页帖子列表，可进行滚动加载内容，点击进入帖子详细内容以及跟帖回复信息内容页面，点击作者头像页面进入作者的详细信息页面，展示作者的积分，主题参与等信息。
技术实现：使用vuex对该项目的状态管理进行了重构，使用getters获取状态，mutation更改状态，action获取接口数据异步处理状态，store管理状态，该项目采用vue2.0和Vue-router管理路由，组件分为主页，详情页，侧边信息页，作者页。
