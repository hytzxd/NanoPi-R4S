# 使用 Github Actions 在线编译 NanoPi-R4S 固件

## 声明
* 本固件处于早期阶段，存在诸多稳定性和功能性问题，不提供任何技术支持
* 本固件的开发和维护完全是出于个人兴趣
* 本人之前从未接触过OpenWrt的固件编译，仍在不断摸索中
* 欢迎共同完善本固件

## 说明
* 推荐 Lean OpenWrt SquashFS 版本
* 管理 IP: 192.168.2.1
* 默认管理密码: password
* 添加超频指南 `configs/overclock`
* [分区扩容指南](https://mlapp.cn/1011.html)
* Lean / Official OpenWrt 目前每次重启会随机更改网卡的MAC地址

## 用法
直接从 Release 下载最新版固件；或 Fork 到自己的账号下，在 Actions 的 Workflow 中手动触发编译动作。

## 特色
### 基于Lean OpenWrt和官方OpenWrt的固件
请参考 [SuLingGG/OpenWrt-Rpi](https://github.com/SuLingGG/OpenWrt-Rpi)，本固件与之保持同步，大多数问题可在 [README.md](https://github.com/SuLingGG/OpenWrt-Rpi/blob/main/README.md) 中得到解答。

### 基于FriendlyWrt的固件
* 支持 RTL8821CU/RTL8822BU 芯片的 USB WiFi 设备，已知支持列表：
    - COMFAST 726B
    - COMFAST CF-759BF
* 集成 [vernesong/OpenClash](https://github.com/vernesong/OpenClash) 及其 core/tun/game binaries
* 集成 [jerrykuku/luci-app-vssr](https://github.com/jerrykuku/luci-app-vssr)
* 集成 [rufengsuixing/luci-app-adguardhome](https://github.com/rufengsuixing/luci-app-adguardhome)
* 集成 [coolsnowwolf/packages](https://github.com/coolsnowwolf/packages), [coolsnowwolf/luci](https://github.com/coolsnowwolf/luci) 与 [coolsnowwolf/lede/package/lean](https://github.com/coolsnowwolf/lede/tree/master/package/lean)
* 更新 [jerrykuku/luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)
* 集成 [pymumu/smartdns](https://github.com/pymumu/smartdns) 与 luci-app-smartdns
* 集成 [luci-app-jd-dailybonus](https://github.com/jerrykuku/luci-app-jd-dailybonus)

## 参考
* https://github.com/SuLingGG/OpenWrt-Rpi
* https://github.com/mj22226/openwrt/tree/nanopi-r4s
* https://github.com/P3TERX/Actions-OpenWrt
* https://github.com/soffchen/NanoPi-R2S
