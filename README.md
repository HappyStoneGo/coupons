### 更新日志 12.31
- 修改个人中心关注公众号按钮点击跳转
- 吃什么页面添加分享功能

### 更新日志 12.30
- 添加吃什么页面

### 更新日志 12.28

- 添加首页排序功能
- 修复订阅功能无法更改发送状态
- 增加缓存openid功能
- 添加个人中心

### 更新日志 12.22

- 新增订阅功能
- 新增右上角提醒收藏


### 使用方法

源码为uniapp项目，需下载hbuilder导入项目打包，可编译成h5或小程序(跳转地址为小程序路径)

- [使用uniapp开发小程序教程](https://mp.weixin.qq.com/s/T5QcSwNaq9VPllqXVVWKfA)


### 常见问题
### 
1. [如何获取美团饿了吗的推广链接]

美团联盟：https://union.meituan.com/

饿了么、双十一：https://pub.alimama.com/

​	2.如何打包成小程序

编译成小程序的话，需要配置coupons里小程序路径

比如跳转饿了么小程序：

```
minapp: {
    appid: 'wxece3a9a4c82f58c9',
    path: 'pages/sharePid/web/index?scene=https://s.click.ele.me/wR9ecuu'
}
```

2. 如何使用云函数
上传云函数前修改cloudfunctions-aliyun/common/utils/index.js
```
exports.APPID = 'wx9472d5ad54e879ed';  //这里是我的appid，需要改成你自己的
exports.SECREAT = '7fefd*************65778a';   //密钥也要改成你自己的
```

如有线上案例或疑问，请提issue，或者关注【羊毛猎人】
