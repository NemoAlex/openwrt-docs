# Linksys WRT1900AC(v1 & v2) / WRT1200AC OpenWrt 相关资源

包含一些编译好的 IPK 软件包，以及中文的说明文档。

欢迎大家积极贡献和维护。

## 通知

* [把 15.05 RC3 的无线模块驱动更新到最新(重要)](https://github.com/NemoAlex/openwrt-wrt1900ac-docs/wiki/2015-%E5%B9%B4-8-%E6%9C%88-2-%E6%97%A5%EF%BC%9A%E5%85%B3%E4%BA%8E%E6%9C%80%E6%96%B0%E7%9A%84%E6%97%A0%E7%BA%BF%E6%A8%A1%E5%9D%97%E9%A9%B1%E5%8A%A8)

## 快速问答

Q: WRT1900AC(v1 & v2) / WRT1200AC 之间有什么区别？现在该买哪个？

A: WRT1900AC v2 和 v1 的主要区别是更换了更好的 CPU，内存翻倍(512M)，因为发热量更小所以去掉了风扇。WRT1200AC 的性能和 WRT1900AC v2 一致，区别在于无线模块和天线的数量。现在要买的话一定要买 WRT1900AC v2 或者 WRT1200AC。当然，v1 如果特别便宜的话另算。

Q: Openwrt 的支持怎么样了？

A: 系统很稳，无线驱动依然有一点问题。不过已经算是可以用了。目前最稳的版本是 Chaos Calmer 15.05 RC3。

Q: 如何从官方固件刷成 Openwrt？

A: 使用网线连接路由器(重要)，登陆路由器 web 界面，点击 connectivity，选择 Manual firmware update，选择固件，点击上传即可。

Q: [固件下载页面](https://downloads.openwrt.org/chaos_calmer/15.05-rc3/mvebu/generic/)有这么多链接，我该用哪个？

A: 路由器代号：`mamba: WRT1900AC v1`；`cobra: WRT1900AC v2`；`caiman: WRT1200AC`。从原版固件更新到 Openwrt 使用 `factory.img`；从 Openwrt 更新到 Openwrt 使用 `sysupgrade.tar`。

## 有用链接

* [OpenWrt Linksys WRT1900AC 官方页面](http://wiki.openwrt.org/toh/linksys/wrt1900ac)
* [OpenWrt 固件/编译 SDK 15.05-rc3 下载](https://downloads.openwrt.org/chaos_calmer/15.05-rc3/mvebu/generic/)
* [网友 popu111 提供的 opkg 国内镜像](http://www.right.com.cn/forum/thread-168519-1-1.html)
* [网友 wangshuoyao 提供的固件，适用于v1版](http://www.right.com.cn/forum/thread-166282-1-1.html)

## 原创文章

* [安装和更新 IPK 软件包](https://github.com/NemoAlex/openwrt-wrt1900ac-docs/wiki/%E5%AE%89%E8%A3%85%E5%92%8C%E6%9B%B4%E6%96%B0%E8%BD%AF%E4%BB%B6%E5%8C%85)
* [IPK 软件包编译指南](https://github.com/NemoAlex/openwrt-wrt1900ac-docs/wiki/%E7%AE%80%E6%98%93%E6%8C%87%E5%8D%97%EF%BC%9A%E4%BD%BF%E7%94%A8-OpenWrt-%E7%9A%84%E4%BA%A4%E5%8F%89%E7%BC%96%E8%AF%91-SDK-%E6%9D%A5%E7%BC%96%E8%AF%91-ipk-%E8%BD%AF%E4%BB%B6%E5%8C%85)
* [使用 crontab 定时更新 chinadns_chnroute](https://github.com/NemoAlex/openwrt-wrt1900ac-docs/wiki/%E4%BD%BF%E7%94%A8-crontab-%E5%AE%9A%E6%97%B6%E6%9B%B4%E6%96%B0-chinadns_chnroute)
