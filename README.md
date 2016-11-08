# Linksys WRT1900AC(v1 & v2 & ACS) / WRT1200AC OpenWrt 相关资源

包含一些编译好的 IPK 软件包，以及中文的说明文档。

欢迎大家积极贡献和维护。

## 通知

* OpenWrt 15.05.1 已经发布

## 快速问答

Q: WRT1900AC(v1 & v2) / WRT1200AC 之间有什么区别？现在该买哪个？

A: WRT1900AC v2 和 v1 的主要区别是更换了更好的 CPU，内存翻倍(512M)，因为发热量更小所以去掉了风扇。WRT1200AC 的性能和 WRT1900AC v2 一致，区别在于无线部分和天线的数量。现在要买的话一定要买 WRT1900AC v2 或者 WRT1200AC。当然，v1 如果特别便宜的话另算。

Q: OpenWrt 的支持怎么样了？

A: 系统没有什么问题，但是无线驱动依然有一点问题（5G 的带宽不够，在吞吐量大的情况下会卡住等等）。不过已经算是可以用了。目前最稳定的版本是 Chaos Calmer 15.05.1 正式版。

Q: 如何从原版固件刷成 OpenWrt？

A: 使用网线连接路由器(重要)，在 web 界面点击 connectivity，选择 Manual firmware update，选择固件，点击上传即可。

Q: 如何从 OpenWrt 刷回原版固件？

A: 在 OpenWrt 的 Web 界面上传 Linksys [原版固件](http://www.linksys.com/us/support-article?articleNum=148550)即可。

Q: [固件下载页面](https://downloads.openwrt.org/chaos_calmer/15.05.1/mvebu/generic/)有这么多链接，我该用哪个？

A: 路由器代号：`mamba: WRT1900AC v1`；`cobra: WRT1900AC v2`；`shelby: WRT1900ACS`；`caiman: WRT1200AC`。从原版固件更新到 Openwrt 使用 `factory.img`；从 Openwrt 更新到 Openwrt 使用 `sysupgrade.tar`。

## 有用链接

* [OpenWrt Linksys WRT1900AC](http://wiki.openwrt.org/toh/linksys/wrt1900ac)
* [OpenWrt 15.05.1 下载](https://downloads.openwrt.org/chaos_calmer/15.05.1/mvebu/generic/)
* [Linksys 1900AC V1/V2原厂固件下载](http://www.linksys.com/us/support-article?articleNum=148550)
* [Linksys 1900ACS原厂固件下载](http://www.linksys.com/us/support-article?articleNum=165487)
* [一键切换 OPKG 源](https://github.com/NemoAlex/opkg-srouce-switcher)
* [网友 wangshuoyao 提供的固件](https://github.com/wongsyrone/lede-1) 这个版本集成了多个软件，有需要的可以自行编译

## 原创文章

* [安装和更新 IPK 软件包](https://github.com/NemoAlex/openwrt-wrt1900ac-docs/wiki/%E5%AE%89%E8%A3%85%E5%92%8C%E6%9B%B4%E6%96%B0%E8%BD%AF%E4%BB%B6)
* [IPK 软件包编译指南](https://github.com/NemoAlex/openwrt-wrt1900ac-docs/wiki/%E7%AE%80%E6%98%93%E6%8C%87%E5%8D%97%EF%BC%9A%E4%BD%BF%E7%94%A8-OpenWrt-%E7%9A%84%E4%BA%A4%E5%8F%89%E7%BC%96%E8%AF%91-SDK-%E6%9D%A5%E7%BC%96%E8%AF%91-ipk-%E8%BD%AF%E4%BB%B6%E5%8C%85)
