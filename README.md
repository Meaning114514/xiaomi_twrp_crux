# Device tree for Xiaomi Mi 9 Pro 5G(codenamed _"crux"_)

Device configuration for Xiaomi Mi 9 Pro 5G
=========================================

The Xiaomi Mi 9 Pro 5G (codenamed _"crux"_) is a high-end smartphone from Xiaomi.

It was announced in February 2019. Release date was in September 2019.

感谢以下大佬：

Wzsx150

Flower-Studio 

HeliumStudio-Dev 

Xirduly

system正常解密可刷入rom
修复之前刷入后重启依旧twrp的严重bug

目前bug:

Data解密 (需要vendor取消加密)

振动

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (1x2.94 GHz Kryo 485 & 3x2.42GHz Kryo 485 & 4x1.8GHz Kryo 485)
Chipset | Qualcomm SDM855 Snapdragon 855 Plus
GPU     | Adreno 640
Memory  | 6/8 GB RAM
Shipped Android Version | 10.0
Storage | 64/128/256 GB (UFS 2.1)
Battery | Non-removable Li-Po 3300 mAh
Display | 1080 x 2340 pixels, 6.39 inches (~428 ppi pixel density)
Camera  | 48MP(Primary),12MP(Telephoto), 16MP(Ultrawide), dual-LED (dual tone) flash, 20MP(Selfie)

## Device picture
![Xiaomi Mi 9 Pro 5G](https://raw.githubusercontent.com/PixelExperience/official_devices/master/images/.thumbs/300/crux.png)

## Compile

Lunch command :
```
lunch twrp_crux-eng && mka recoveryimage
```