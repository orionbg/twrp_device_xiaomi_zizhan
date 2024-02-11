# TWRP device tree for Xiaomi Mix Fold 2 - Not yet done!!!

Xiaomi Mix Fold 2 (codenamed _"ZIZHAN"_) is a high-end foldable smartphone from Xiaomi.

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | Qualcomm SM8475 Snapdragon 8+ Gen 1
CPU     | Octa-core (1x3.19 GHz Cortex-X2 & 3x2.75 GHz Cortex-A710 & 4x1.80 GHz Cortex-A510)
GPU     | Adreno 730
Memory  | 12GB RAM
Shipped Android Version | 13.0 with MIUI 14
Storage | 256/512 GB
Battery | Li-Ion 4500 mAh, non-removable, graphene-enhanced

## Device picture

![Xiaomi Mix Fold 2](https://fdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-mix-fold-2-2.jpg)

## Features

Will hopefully Work:

- [X] ADB
- [X] Decryption
- [X] Display
- [x] Touchscreen
- [X] Fasbootd
- [X] Flashing
- [X] MTP
- [X] Sideload
- [X] USB OTG
- [X] Vibrator

## To use it: (But don't just yet)

```
fastboot flash recovery_ab out/target/product/babylon/recovery.img
```
