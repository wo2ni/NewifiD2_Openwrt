### 基于NewifiD2的Openwrt Firmware;

这是一个结合多个大神所开发的一系列Openwrt神级插件  
***基于Mips架构***的构建;    
包含的所有功能见下图***默认移除了无线芯片部分的所有驱动,以及USB3.0;***  

### 此路由器系统包含以下主要功能;
```
0,原生IPV6支持;
1,多线多拨,负载均衡;
2,微信推送支持;
3,网络唤醒支持;
4,....科学上网支持(SSR,V2RAY,Trojan,Trojan-Go,Xray,);
5,ZeroTier(SDWAN支持);
6,UPNP支持;
```
# 💖包含功能💖
|        |             |            |
|--------|-------------|------------|
|💕IPV6支持💕|💕多拨,负载均衡💕 |💕WOL远程唤醒💕|
|💕全自动科学上网💕|💕ZeroTier(SDWAN)💕 |💕UPNP💕 |

### 来几张靓图;

### 需要注意的地方......
```
(务必删除光猫里的RMS服务,以及自带的intelnet业务,以及不要保存任何日志;)
(自己建立ipv4/ipv6业务,牢记LOID和Vlanid;)
(只有这样才能彻底摆脱来自ISP的远程管控;)
```

### 构建平台
```
Debian9.9
```

#### 编译环境构建;
```
sudo apt-get -y update
sudo apt-get -y install build-essential \
        asciidoc binutils bzip2 gawk gettext git \
        libncurses5-dev libz-dev patch python3 python2.7 \
        unzip zlib1g-dev lib32gcc1 libc6-dev-i386 subversion \
        flex uglifyjs git-core gcc-multilib p7zip p7zip-full msmtp \
        libssl-dev texinfo libglib2.0-dev xmlto qemu-utils upx libelf-dev \
        autoconf automake libtool autopoint device-tree-compiler g++-multilib \
        antlr3 gperf wget curl swig rsync \
        sudo apt-get install libjsoncpp-dev \
        sudo ln -s /usr/include/jsoncpp/json/ /usr/include/json && sudo ldconfig
```

### 自己用到的源码Github地址;
- [💕→ Openwrt官方源码](https://github.com/openwrt/openwrt)
- [💕→ Lean Openwrt源码](https://github.com/coolsnowwolf/lede)
- [💕→ Lienol Openwrt源码](https://github.com/Lienol/openwrt)

### 自己用到的一些插件Github地址;
- [💕→ passwall ssr-plus源码](https://github.com/kenzok8/openwrt-packages)
- [💕→ Hello World源码](https://github.com/jerrykuku/luci-app-vssr)
- [💕→ server酱微信推送源码](https://github.com/tty228/luci-app-serverchan)
- [💕→ 京东签到源码](https://github.com/jerrykuku/luci-app-jd-dailybonus)
- [💕→ 新版argon主题源码](https://github.com/jerrykuku/luci-theme-argon)








## 生命不息,折腾不止;


### 友链
- [→ ipv6测试](https://www.test-ipv6.com/)
- [→ 佐须之男Openwrt教程](http://forgotfun.org/)
- [→ 恩山无线论坛](https://www.right.com.cn/)
- [→ 本人永久的Github地址](https://github.com/wo2ni)
