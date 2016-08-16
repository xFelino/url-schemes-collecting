URL schemes collecting
---

收集 iOS 常用 App 的 URL schemes，可用于各种启动器，或者添加到桌面。

欢迎`Star`、`Pull request`或提交 `Issue`。

#### 1. 微信
功能 | URL | 备注
---- | ---- | ----
扫一扫 | weixin://dl/scan | 最新版微信不能再从外部调用 [#2](https://github.com/paicha/url-schemes-collecting/issues/2)
朋友圈 | weixin://dl/moments
收藏 | weixin://dl/favorites
我的二维码 | weixin://dl/myQRcode

#### 2. 支付宝
功能 | URL
---- | ----
扫一扫 | alipayqr://platformapi/startapp?saId=10000007
付款码 | alipayqr://platformapi/startapp?saId=20000056
红包 | alipay://platformapi/startapp?saId=88886666

#### 3. 网易云音乐
功能 | URL
---- | ----
听歌识曲 | orpheuswidget://recognize

#### 4. Surge
功能 | URL
---- | ----
启动 | surge:///start[?autoclose=true]
停止 | surge:///stop[?autoclose=true]
切换状态 | surge:///toggle[?autoclose=true]
