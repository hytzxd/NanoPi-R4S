# NanoPi R4S RK3399 超频指南
固件默认的大小核频率为 1.8GHz/1.4GHz，可以超频至 2.0GHz/1.5GHz 或 2.2GHz/1.8GHz

## 超频至 2.0GHz/1.5GHz
1. 下载 rockchip-2.0_1.5.dtb 至根目录：`wget https://raw.githubusercontent.com/LewiVir/NanoPi-R4S/main/configs/overclock/rockchip-2.0_1.5.dtb`
2. 将 rockchip-2.0_1.5.dtb 复制到 `/mnt/mmcblk0p1` 并重命名为 `rockchip.dtb`：`cp -f rockchip-2.0_1.5.dtb /mnt/mmcblk0p1/rockchip.dtb`
3. 重启：`reboot`

## 超频至 2.2GHz/1.8GHz
1. 下载 rockchip-2.2_1.8.dtb 至根目录：`wget https://raw.githubusercontent.com/LewiVir/NanoPi-R4S/main/configs/overclock/rockchip-2.2_1.8.dtb`
2. 将 rockchip-2.2_1.8.dtb 复制到 `/mnt/mmcblk0p1` 并重命名为 `rockchip.dtb`：`cp -f rockchip-2.2_1.8.dtb /mnt/mmcblk0p1/rockchip.dtb`
3. 重启：`reboot`

## 还原为 1.8GHz/1.4GHz
1. 下载 rockchip-1.8_1.4.dtb 至根目录：`wget https://raw.githubusercontent.com/LewiVir/NanoPi-R4S/main/configs/overclock/rockchip-1.8_1.4.dtb`
2. 将 rockchip-1.8_1.4.dtb 复制到 `/mnt/mmcblk0p1` 并重命名为 `rockchip.dtb`：`cp -f rockchip-1.8_1.4.dtb /mnt/mmcblk0p1/rockchip.dtb`
3. 重启：`reboot`
