# OpenWrt18.06-X86-64最新版云编译项目

## 固件来源：
此固件为纯软路由精简固件，主要为低价低功耗小主机定制，比如n270,n2600,d525等老硬件。

精简方向为非常见硬件驱动、与软路由无关的硬件驱动，无线驱动以及相关的软件，以及一切非必要插件软件（主要指系统驱动以及环境配置等方面用不到的）。

x86固件，主要为n270定制，部分保留了amd的32位低功耗硬件驱动，保留千兆百兆常见网卡驱动。

x64固件，精简了非常见型号老旧硬件驱动，以及新硬件驱动，无百兆网卡驱动等，主要为n2600,d525,j1800等适配，网卡仅支持常见的千兆网卡型号。

总而言之，这就是个纯软路由固件，luci插件基本都能用，暂未遇到因精简引起的问题。

此固件在以下各位大佬的基础上进行了最大程度上的精简，感谢大佬们的无私奉献。

====================================================================================
firker脚本 https://github.com/firker/openwrt-Exclusive
P3TERX云编译脚本地址：[https://github.com/P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)

lean固件源码地址：[https://github.com/coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)

project-openwrt固件源码地址：[https://github.com/project-openwrt/openwrt](https://github.com/project-openwrt/openwrt)

由衷感谢所有为openwrt无私奉献的大佬们。

## 固件说明：

lean源码版本，内核为***5.4***（ipv6）版和***4.19***版

project-openwrt源码版本，内核为***4.19***版(同步[linux4.19内核](https://www.kernel.org/))

自动每3天更新一次，手动不定时更新

> `ip：192.168.1.1 密码：password`

## 固件下载
### 点击[Actions](https://github.com/firker/openwrt-Exclusive/actions) 或者[Releases](https://github.com/firker/openwrt-Exclusive/releases) 选择需要的版本
![avatar](https://raw.githubusercontent.com/firker/openwrt-Exclusive/main/boc/c.png)

## 固件截图：
### 4.19版
![avatar](https://raw.githubusercontent.com/firker/openwrt-Exclusive/main/boc/d.png)
### 5.4版（支持IPV6）
![avatar](https://raw.githubusercontent.com/firker/openwrt-Exclusive/main/boc/b.png)
### project 4.19版
![avatar](https://raw.githubusercontent.com/firker/openwrt-Exclusive/main/boc/e.png)
## 其他
联系：[Tg频道订阅](https://t.me/zhinengchaoshenzhe)

稳定版云编译项目：[https://github.com/firkerword/openwrt-Exclusive](https://github.com/firkerword/openwrt-Exclusive)
