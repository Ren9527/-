# Shadowrocket小火箭配置使用教程

## 应用概述

Shadowrocket 是在 iOS 平台上的客户端软件，支持 Shadowsocks、ShadowsocksR 以及 VMess 协议。

目前 Shadowrocket 已经被 Apple 根据政府要求从中国大陆区的 App Store 移除，之前在中国大陆商店购买此软件的用户将不能获得更新或重新下载。
**请确保从苹果商店下载最新版小火箭，如果您不是最新版，请升级到最新版。**

[获取小火箭](AppleID.md)

## 将V2ray节点导入小火箭

**首选方法：**  拷贝订阅链接，将其导入小火箭。

**备选方法：** 拷贝节点URL后(不是订阅链接)，切换到Shadowrocket(小火箭)，小火箭会自动弹出提示："将复制配置添加到您的列表(取消/添加)",点"添加"按钮即可。

## Shadowrocket小火箭连不上的解决办法

我们发现可能是小火箭有bug，有时候会连不上，有2个办法：

1、是到ios的vpn设置的地方，关闭vpn，再重新打开就连上了

2、另外，就是重启一下手机，然后打开小火箭，重新连接，就连上了

这是一个付费软件，你需要购买才能使用。

## 应用下载

[App Store:Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118)

### 获取服务器配置链接

## 配置 Shadowrocket

打开 Shadowrocket，点击底部导航栏的「设置」进入设置页面，随后往下划至 最底部，进入「服务器订阅」子页面。

将「打开时更新」的开关 **打开**。

![1](https://v2free.org/docs/SSPanel/iOS/images/shadowrocket-1.jpg)

**回到首页**，点击右上角的加号，再次点击第一行的「类型」，选择 **Subscribe**。

![2](https://v2free.org/docs/SSPanel/iOS/images/shadowrocket-2.jpg)

在「备注」中输入本站名称，随后在「URL」中粘贴上方 **[获取订阅](#获取订阅)** 中的订阅链接并保存。

![3](https://v2free.org/docs/SSPanel/iOS/images/shadowrocket-3.jpg)

随后点击右上角保存，此时会自动更新获取服务器。

***小火箭手工更新订阅方法：
点“服务器节点”最上方的订阅链接右边的“i”图标，然后再点右上角的“完成”。***

获取节点后，点击选中一个节点，然后点界面右上角的"未连接"开关，就可以开启vpn连接自由上网了。

### 分流规则

小火箭自带的一个简单的默认配置，有基本分流功能，自带规则比较精简，包含了常用网站，好处是体积小速度快，缺点是你上的网站如果不是常用或者是个cdn，它不一定会走代理。如果你不满意，可以继续下载配置一个高级分流规则。

在底部导航栏进入「配置」页面，点击右上角加号。

在弹出的输入框中输入 [此链接网址](https://raw.githubusercontent.com/Hackl0us/Surge-Rule-Snippets/master/LAZY_RULES/Shadowrocket.conf) 【电脑：右键点链接->复制链接地址；手机长按链接，然后复制链接地址；或点击打开链接后从浏览器地址栏复制链接地址】。

随后点击 **远程文件** 中新增的配置文件地址，在弹出的菜单中选择第二个「使用配置」，此时 APP 会自动开始下载配置并应用配置。

![4](https://v2free.org/docs/SSPanel/iOS/images/shadowrocket-4.jpg)

**回到首页**，点击进入「全局路由」将其更改为 **配置**。

![5](https://v2free.org/docs/SSPanel/iOS/images/shadowrocket-5.jpg ':size=400')

## 开始使用

点右下角的：设置->延迟测试方法，改为

CONNECT

回到 Shadowrocket 首页，点“连通性测试”测速，然后选择速度快延迟低的节点，随后打开第一行开关即可。

如提示添加 VPN 配置，请点击 Allow 并验证您的 密码、Touch ID、Face ID 。
