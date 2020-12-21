# NanoPi R4S RK3399 超频指南
固件默认大小核频率的最高频率为 2.2GHz/1.8GHz，可以更改至 2.0GHz/1.5GHz 或 1.8GHz/1.4GHz

## 2.2GHz/1.8GHz
```
wget https://raw.githubusercontent.com/LewiVir/NanoPi-R4S/main/configs/overclock/rockchip-2.2_1.8.dtb
cp -f rockchip-2.2_1.8.dtb /mnt/mmcblk0p1/rockchip.dtb
reboot
```

## 2.0GHz/1.5GHz
```
wget https://raw.githubusercontent.com/LewiVir/NanoPi-R4S/main/configs/overclock/rockchip-2.0_1.5.dtb
cp -f rockchip-2.0_1.5.dtb /mnt/mmcblk0p1/rockchip.dtb
reboot
```

## 1.8GHz/1.4GHz
```
wget https://raw.githubusercontent.com/LewiVir/NanoPi-R4S/main/configs/overclock/rockchip-1.8_1.4.dtb
cp -f rockchip-1.8_1.4.dtb /mnt/mmcblk0p1/rockchip.dtb
reboot
```
