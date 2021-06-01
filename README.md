# 基于玩Android 开放API 的app开发
## APP简介
### 功能
* 玩Android平台的登录验证与注册
* 玩Android平台关于首页文章的显示与访问
### 使用步骤
#### 首页文章
* 打开APP
![1633E447EB750BEA19BBC51EBFE6E088](https://user-images.githubusercontent.com/74126057/120310078-8e54aa00-c308-11eb-8e27-0365b9a6e711.jpg)
* 下拉刷新文章列表
![F9527BBFF9B4194D8FC0CA18AFB0902D](https://user-images.githubusercontent.com/74126057/120310237-bf34df00-c308-11eb-8bf7-f11846b95713.jpg)
* 点击转入文章对应网址
![76A56E482D6C1F358CBB8B993EABCEB0](https://user-images.githubusercontent.com/74126057/120310395-ec818d00-c308-11eb-987e-824ad0d5a910.jpg)
* 登录界面
![30686125FE3B59DED67F09E856954D3A](https://user-images.githubusercontent.com/74126057/120310451-fd320300-c308-11eb-9e2c-7e71d64bdacb.jpg)
![A5ED461D553F923B907330C101424447](https://user-images.githubusercontent.com/74126057/120310472-01f6b700-c309-11eb-847c-4cae5205edae.jpg)
* 注册界面
![D3D909331A894A7EF1CE79B728EA9B0B](https://user-images.githubusercontent.com/74126057/120310511-0de27900-c309-11eb-9d93-3fa862096f59.jpg)
* 上滑刷新（残次版）
## 重要技术及知识点
1，对SwipeRefreshLayout的使用实现下拉刷新
2，接口回调实现信息传递
3，在adpater中使用intent对信息进行传递
4，为recycleview添加addOnScrollListener以判断是否滑动到底
5，json解析
6，网络请求的两种方式“GET”“POST”的使用
## 心得体会
* 对recycleview的adapter有了更深的理解
* 增长的对接口回调使用的经验
* 了解了关于谷歌官方下滑刷新控件的理解
* 刷新了我对Android开发的理解：Android开发有两层：1，活动与活动间的信息传递2，xml文件与活动文件间的信息传递
