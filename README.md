# 微信官方JS-SDK

微信官方JS-SDK拷贝副本，主要用于[ewexin.js](https://github.com/EthanZhong/eweixin)依赖引用。由于jweixin.js的[使用规范](http://mp.weixin.qq.com/wiki/7/aaa137b55fb2e0456bf8dd9148dd613f.html),需要用户先配置签名验证信息`wx.config`,然后捕获`wx.ready`的成功状态，最后用户才可以开始去调用`wx`的其它`api`。这种严格的执行顺序没有什么问题，却像一层枷锁。[ewexin.js](https://github.com/EthanZhong/eweixin)则在jweixin的基础上简单封装了一层顺序和调用限制的控制，这样就可以让我们在任意时间，任意顺序，任意地点，调用任意`api`。

##拷贝来源

[微信官方JS](https://res.wx.qq.com/open/js/jweixin-1.0.0.js)

##使用方式

[微信官方文档](http://mp.weixin.qq.com/wiki/7/aaa137b55fb2e0456bf8dd9148dd613f.html)
