# [Go to Basepage of Quansheng_UV-K5_Wiki](https://github.com/ludwich66/Quansheng_UV-K5_Wiki/wiki)

# [<img width="200" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/19823838-7a3f-4ba4-b943-df7f01d16527">](https://github.com/ludwich66/Quansheng_UV-K5_Wiki/wiki)


 
## Links to many people working on the UV-K5
* [ludwich66 - Quansheng UV-K5 Wiki](https://github.com/ludwich66/Quansheng_UV-K5_Wiki/wiki)
* [amnemonic- Quansheng_UV-K5_Firmware](https://github.com/amnemonic/Quansheng_UV-K5_Firmware)
* [Tunas1337 - UV-K5-Modded-Firmwares](https://github.com/Tunas1337/UV-K5-Modded-Firmwares)
* [sq5bpf - uvk5-reverse-engineering](https://github.com/sq5bpf/uvk5-reverse-engineering)
* [fagci - qs-uvk5-firmware-modder](https://github.com/fagci/qs-uvk5-firmware-modder)
* [piotr022 - UV_K5_playground - first attempts to prepare build and debug environment](https://github.com/piotr022/UV_K5_playground)
* [UVMOD RX-TX Onlime Firmware Patcher](https://re3con.github.io/uvmod/) *feature work*
* [UVMOD EU limits to RX patches only by whosmatt](https://github.com/whosmatt/uvmod)
* [中文版 Open Chinese Version (maintained independently)](https://uvmod.xanyi.eu.org/)
* [UVMOD in russian language project](https://uvmod.valek.net.ru/)
* [Discussion forum 4PDA](https://4pda.to/forum/index.php?showtopic=1071343&st=0)

## Introduction

Web-based client-side Quansheng firmware patcher written in Javascript and HTML using [Bootstrap 4.6.0](https://getbootstrap.com/docs/4.6/getting-started/introduction/), jQuery and parts of the [SB Admin 2 Theme](https://startbootstrap.com/theme/sb-admin-2).  
It is based on the discoveries by the many contributors in the [uvmod-kitchen](https://github.com/amnemonic/Quansheng_UV-K5_Firmware/tree/main/uvmod_kitchen) and implements the **same functionality** not limited to RX only but also TX in a modular and flexible javascript structure. This is an enhanced UVMOD from whosmatt src.

Visitors can generate a patched firmware image by selecting the desired patches. Patches modify the firmware on a binary level and can accept user input to customize variables. A custom base image can be supplied to allow support for mods that are compiled and linked directly into the firmware. 

## Mod development

Clone this repository and execute `python3 -m http.server` or `python -m http.server` in the root directory for an instant local web server, allowing easy testing.  
Mods are defined in [mods.js](mods.js), with an example mod to outline the pattern.  
Also __refer to the helper functions and documentation in__ [modframework.js](js/modframework.js).  

The supported format for binary data is in the format of a hex string __without separators__. You can use find and replace to remove all `\x` from a regular hex string or directly export the correct format from a bytes object in python using `print(''.join('%02x'%i for i in BYTES_OBJECT))`.

## **Comming soon** 
Offline universal firmware version patcher
based on search and replace pattern to change and modificate with precission the functions of these patches direct on all firmware versions and upcoming versions files.<br>

I'll take in account EU Country block on DNS domain cause of different law regulations in whosmatt location. 

*Credits and many thanks to whosmatt!*

* [agocsdaniel - opensheng](https://github.com/agocsdaniel/opensheng)
  <Br><Br>
* [Telegram Channel - EN](https://t.me/quansheng_uvk5_en)
* [Telegram Channel - RU](https://t.me/uv_k5)<br><br>
  I would like to ask the two Spanish Telegram Channels to merge. <br>
  It makes little sense to distribute a few OM to two "equal" channels. <br>
  Just open a third channel and direct all users there ;-)<br>
  Here is my offer until we find a solution together!<Br>
* [Telegram Channel - ES *](https://t.me/QuanShengES)
* [Telegram Channel - ES #](https://t.me/Quansenguvk5)<br><br>
* [Telegram Channel - IT](https://t.me/+W31XPFpurWk0NzM0)
* [Telegram Channel - PL](https://t.me/uvk5_pl)
* [Telegram Channel - DE](https://t.me/quanshenguv5kde)
* [Telegram Channel - UKR](https://t.me/radioamators/38782)<Br><Br>
* Facebook - [Quansheng Electronics Co., Ltd.](https://www.facebook.com/QuanshengRadios/)
* Facebook - [Quansheng UV-K5 User's Group](https://www.facebook.com/groups/229333669483573/)
* Facebook - [QuanSheng UV-K5 UV-K5(8) UV-K6 - Polska](https://www.facebook.com/groups/205485455659292/)
* Facebook - [Quansheng UV-K5 UK Users](https://www.facebook.com/groups/2291286734508728/)
* Facebook - [Quansheng UV-K5 Philippines User Group](https://www.facebook.com/groups/678587170703812/)<Br><Br>

* Official UV-K5 support page:              [Chinese](http://qsfj.com/support/downloads/3002) | [English](http://en.qsfj.com/support/downloads/3002)
* Official UV-K5 product page:              [Chinese](http://qsfj.com/products/3002)          | [English](http://en.qsfj.com/products/3002)
* Official UV-K5(8) aka UV-K6 support page: [Chinese](http://qsfj.com/support/downloads/3268) | [English](http://en.qsfj.com/support/downloads/3268)
* Official UV-K5(8) aka UV-K6 product page: [Chinese](http://qsfj.com/products/3268)          | [English](http://en.qsfj.com/products/3268)
<Br><Br>
* [FCC Reports](https://fcc.id/XBPUV-K5) / [fcc.gov](https://apps.fcc.gov/oetcf/eas/reports/ViewExhibitReport.cfm?mode=Exhibits&RequestTimeout=500&calledFromFrame=Y&application_id=8sqkxgC%2F1cYNHF0lGkSAwA%3D%3D&fcc_id=XBPUV-K5)
* [Google Drive folder with useful info](https://drive.google.com/drive/folders/1NmcPb5yl5jnz7uWBO-c4B89XYL5AZeHw)
