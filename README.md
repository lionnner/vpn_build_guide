# VPS-Shadowsocks(纸飞机)服务端搭建&客户端推荐
<img src="images/Icon.png" width="200">

# 1.<a id="服务端搭建"></a>Shadowsocks 服务端搭建

* [Debian下 shadowsocks-libev版一键安装脚本](https://teddysun.com/358.html)
* [CentOS下     shadowsocks-libev版一键安装脚本](https://teddysun.com/357.html)
* [CentOS/Debian/Ubuntu下 shadowsocks-Python版一键安装脚本](https://teddysun.com/342.html)
* [CentOS/Debian/Ubuntu下 shadowsocks-R版一键安装脚本](https://shadowsocks.be/9.html)
* [CentOS/Debian/Ubuntu下 shadowsocks-go版一键安装脚本](https://teddysun.com/392.html)


### 简单说下这四个版本的区别：
1. libev 版： 内存占用小(600k左右)，低 CPU 消耗，甚至可以安装在基于 OpenWRT 的路由器上
2. Python版： 支持多用户多端口配置
3. Go版： 与 Python 版不同的是，其客户端程序能使用多个服务端配置
4. R版：没用过~

# 2.Shadowsocks 客户端下载
1. [Windows 下载点击(github)](https://github.com/shadowsocks/shadowsocks-windows/releases)
2. [Mac 下载点击(github)](https://github.com/shadowsocks/ShadowsocksX-NG/releases/)
3. [Android 下载点击(github)](https://github.com/shadowsocks/shadowsocks-android/releases)
4. iOS AppStore 搜索"wingy"

# 3.VPS 购买推荐
1. [Badnwagon(搬瓦工)](https://bwh1.net/index.php)
2. [Alpharacks](https://www.alpharacks.com)
3. [老左博客推荐](http://www.laozuo.org/myvps)


####如果不着急使用，VPS购买切记赶在节假日之间(老外节日+国内节日)买，所购买价格即之后续费价格,可以先注册相应账号,然后节假日注意邮件消息
目前只接触过 Badnwagon和Alpharacks,简单说下使用心得: 

* 1. Badnwagon:  
月付2.99$套餐  
ping值在160ms左右  
提供一键搭建shadowsocks服务端按钮(不过密码跟端口号是它自己生成的)
 

<img src="images/Badnwagon_record.png" width="300">

* 2. Alpharacks:  
年付5$套餐  
ping值在190ms左右  
已经开始支持支付宝  

<img src="images/Alpharacks_record.png" width="400">

