### 基于NewifiD2江湖俗称(新路由3)的Openwrt系统;

![route.jpg](https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=1980062630,316990257&fm=26&gp=0.jpg) 

#### !!警告!!
- 此软件仅为学习用途,***低调***使用,本人不提供出售任何***Fan,Qiang***服务;
- 请勿用于任何盈利手段,这包含了自己所有寒假的所有活动,;


这是一个结合多个大神所开发的一系列Openwrt神级插件的部分整合    
***基于Mips架构***的构建;默认移除***无线芯片***以及***USB3.0***驱动;  

# 💖包含功能💖
|        |             |            |
|--------|-------------|------------|
|💖原生IPV6支持💖|💖多线多拨💖 |💖负载均衡💖|
|💖TurboACC网络加速💖|💖ZeroTier(SDWAN)💖 |💖UPNP💖 |
|💖微信推送💖|💖WOL远程唤醒💖 |💖ipv4/ipv6防火墙💖 |
- ##### 💖全自动智能科学上网(支持SS,SSR,V2RAY,Trojan,Trojan-Go,Xray)💖

### 来几张靓照;
![2021-02-03 23-02-58 的屏幕截图.png](https://i.loli.net/2021/02/04/aSor2pvx37ZP5dW.png) 

![2021-02-03 23-40-31 的屏幕截图.png](https://i.loli.net/2021/02/04/YxPpTtO6BSeKLJQ.png)

![2021-02-03 23-22-22 的屏幕截图.png](https://i.loli.net/2021/02/04/Hh2keQCKZgw13pP.png)

![2021-01-29 09-51-45 的屏幕截图.png](https://i.loli.net/2021/02/04/YzOienUhMf1gsXC.png)

![594086172.jpg](https://i.loli.net/2021/02/04/W5U27mGrpDNXFcB.jpg)


### 需要注意的地方......
```
此固件必须结合光猫PPPOE方式使用,务必确保光猫工作在!!桥接模式下!!
务必删除光猫里的RMS服务,以及自带的Intelnet业务,以及不要保存任何日志;
自己创建ipv4/ipv6业务,!务必记下光纤LOID!和之前的VlanID;
只有这样此固件的惊人本领,将彻底释放;
```

### 下载;
- [→ 👉下载BootLoader及固件👈](https://github.com/wo2ni/NewifiD2_Openwrt/releases/tag/v0.1)

### 刷机教程;
##### 我一般的方法:
```
直接用热风枪干下Flash芯片,上编程器刷BootLoader,在干上去;  
此固件以完全移除了无线部分即使丢了EEPROM也无妨;
```

- [→ 👉推荐使用此方法👈](https://www.upantool.com/sense/luyouqi/14063.html)

### 构建平台
```
Debian9.9
```

#### 编译环境;
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
- [💕→ 应用过滤源码](https://github.com/destan19/OpenAppFilter)
- [💕→ server酱微信推送源码](https://github.com/tty228/luci-app-serverchan)
- [💕→ 京东签到源码](https://github.com/jerrykuku/luci-app-jd-dailybonus)
- [💕→ 新版argon主题源码](https://github.com/jerrykuku/luci-theme-argon)

## 生命不息,折腾不止;

### 友链
- [→ ipv6测试](https://www.test-ipv6.com/)
- [→ 佐须之男Openwrt教程](http://forgotfun.org/)
- [→ 恩山无线论坛](https://www.right.com.cn/)
- [→ 本人永久的Github地址](https://github.com/wo2ni)
