---
title: esp_key
date: 2026-02-08 23:37:22
tags:
---

## 物理密钥
基于[picokeys](https://www.picokeys.com/)的物理密钥

## 编译构建

### esp32s3 构建

```
git clone https://github.com/polhenarejos/pico-fido

cd pico-fido 

git submodule update --init --recursive

idf.py set-target esp32s3 

idf.py -DPICO_BOARD=Yubikey5 build

idf.py flash
```

## 非官方配置工具

Yubico Yubikey

命令行工具
[boku_no_key](https://github.com/Lumingtianze/boku_no_key)

图形化工具s
[boku_no_key](https://github.com/finn4/FIDOConfigTool)

