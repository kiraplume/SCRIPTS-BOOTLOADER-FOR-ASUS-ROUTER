# 更新日志

## 版本21.0（2021-04-03）

#### 新增

1. 无

#### 变更

1. Entware_20210330发布，请参考使用手册升级系统

#### 删除

1. 无

## 版本20.0（2021-03-21）

#### 新增

1. 无

#### 变更

1. Entware_20201203发布，请参考使用手册升级系统

#### 删除

1. 无

## 版本19.0（2020-10-05）

#### 新增

1. 无

#### 变更

1. Entware_20200910发布，请参考使用手册升级系统
2. 更新addons_install

#### 删除

1. 无

## 版本18.1（2020-08-01）

#### 新增

1. 无

#### 变更

1. Entware_20200615发布，请参考使用手册升级系统

#### 删除

1. 无

## 版本18.0（2020-08-01）

#### 新增

1. 无

#### 变更

1. 更新addons_install
2. 更新script_bootloader_usb_umount
3. 更新dnsmasq.d

#### 删除

1. 无

## 版本17.0（2020-05-01）

#### 新增

1. 无

#### 变更

1. Entware_20200401发布，请参考使用手册升级系统
2. 更新How_to_Use_zh-CN.md
3. 更新How_to_Use_en-US.md
4. 更新addons_install
5. 更新dnsmasq.d
6. 更新drive_modifier，增加EXT4支持
7. 更新entware，增加安装离线库功能
8. 更新install
9. 更新install_online
10. 更新update
11. 更新upgrade，增加离线升级功能

#### 删除

1. 删除Python 2.7及全部相关内容。Python 2.7已于20200101停止维护

## 版本16.1（2020-04-01）

#### 新增

1. 无

#### 变更

1. 更新monit，更改验证信息格式
2. 更新dependency，添加git和git-http
3. 更新install_online，取消依赖curl
4. 更新addons_install，处理.monit.id和.monit.state
5. 更新script_bootloader_usb_umount，处理.monit.id和.monit.state
6. 更新drive_modifier，修复零分区及分区方案问题
7. 修复Bugs

#### 删除

1. 无

## 版本16.0（Chinese New Year）

#### 新增

1. 无

#### 变更

1. 更新核心插件
2. 规范代码
3. 修复Bugs

#### 删除

1. 无

## 版本15.1（2020-01-21）

#### 新增

1. 无

#### 变更

1. 更新全部插件
2. 规范代码
3. 修复Bugs

#### 删除

1. 无

## 版本15.0（Christmas Day）

#### 新增

1. 新增系统更新程序update，可用于更新系统+Entware+外部插件。此为重大更新，请使用者务必全新部署本系统
2. 新增exclusion_list_of_addons_update
3. 新增exclusion_list_of_addons_install
4. 新增gohash

#### 变更

1. 更新install_online
2. 更新install
3. 更新restore
4. 更新addons_install
5. 更新gotee
6. 更新fwd，修复bugs

#### 删除

1. 删除sys_install
2. 删除exclusion_list_of_addons

## 版本14.2（2019-12-20）

#### 新增

1. 无

#### 变更

1. 更新install_online

#### 删除

1. 无

## 版本14.1（2019-12-08）

#### 新增

1. 无

#### 变更

1. fwd补全中文注释，规范代码，修复bugs

#### 删除

1. 无

## 版本14.0（2019-11-01）

#### 新增

1. fwd防火墙

#### 变更

1. 无

#### 删除

1. 无

## 版本13.1（2019-10-07）

#### 新增

1. 无

#### 变更

1. 更新install_online
2. 更新label_modifier
3. 更新prerequisite_checker
4. 规范代码

#### 删除

1. 无

## 版本13.0（2019-10-01）

#### 新增

1. 新增gotee，解决了原厂固件中没有`tee`命令的问题
2. 新增prerequisite_checker，在安装过程开始前检查环境
3. 准备国际化

#### 变更

1. 更新install_online
2. 更新label_modifier

#### 删除

1. 无

## 版本12.1（2019-09-17）

#### 新增

1. 无

#### 变更

1. 更新dependency
2. 更新entware
3. 规范代码

#### 删除

1. 无

## 版本12.0（2019-09-10）

#### 新增

1. 无

#### 变更

1. 更新install
2. 规范代码

#### 删除

1. 无

## 版本11.1（2019-08-19）

#### 新增

1. 无

#### 变更

1. 更新dnsmasq.d
2. 规范代码

#### 删除

1. 无

## 版本11.0（2019-08-11）

#### 新增

1. 新增dnsmasq.d，通过自动监控/opt/etc/dnsmasq.d目录，允许dnsmasq加载该目录中的用户自定义配置文件

#### 变更

1. 更新Install，加入dnsmasq.d
2. 规范代码

#### 删除

1. 无

## 版本10.8（2019-07-06）

#### 新增

1. 无

#### 变更

1. 规范代码
2. 增加vim

#### 删除

1. 无

## 版本10.7（2019-5-24）

#### 新增

1. 无

#### 变更

1. 增强install_online和label_modifier
2. 增加psmisc

#### 删除

1. 无

## 版本10.6（2019-05-16）

#### 新增

1. 在线安装程序

#### 变更

1. 无

#### 删除

1. 无

## 版本10.5（2019-04-22）

#### 新增

1. 无

#### 变更

1. 规范代码

#### 删除

1. 无

## 版本10.4（2019-04-08）

#### 新增

1. 无

#### 变更

1. 使本系统可安装于U盘任意层级目录中
2. 默认安装openssh-client

#### 删除

1. 无

## 版本10.3（2019-03-24）

#### 新增

1. 无

#### 变更

1. 配合Entware升级

#### 删除

1. 无

## 版本10.2（2019-03-10）

#### 新增

1. 无

#### 变更

1. 更新程序结构

#### 删除

1. 无

## 版本10.1（2018-09-14）

#### 新增

1. 无

#### 变更

1. 更新部分配置文件

#### 删除

1. 无

## 版本10.0（2018-08-29）

#### 新增

1. 为实现一键安装，最大程度减轻部署难度，特将插件库和系统合并
2. 新增的插件安装程序addons_install，实现插件安装菜单化

#### 变更

1. 安装程序install更新为“一键安装”，配合新增的插件安装程序addons_install，大幅降低了安装难度和复杂度

#### 删除

1. 无

## 版本9.1（2018-08-15）

#### 新增

1. 新增Monit配置文件：
   - fw_filter_INPUT_v2ray_server
   - fw_nat_PREROUTING_ipsec
   - fw_nat_PREROUTING_l2tp

#### 变更

1. 无

#### 删除

1. 无

## 版本9.0（2018-08-13）

#### 新增

1. 新增进程锁机制，防止本系统被重复加载

#### 变更

1. 无

#### 删除

1. 无

## 版本8.2（2018-08-13）

#### 新增

1. 新增Monit配置文件：syncthing

#### 变更

1. 更新Monit配置文件：vlmcsd

#### 删除

1. 无

## 版本8.1（2018-08-05）

#### 新增

1. 新增Monit配置文件：ntpd

#### 变更

1. 无

#### 删除

1. 无

## 版本8.0（2018-07-27）

#### 新增

1. 新增Monit进程监控系统
   > **特别说明**
   >
   > 此为重大变更，今后发布的插件，将尽可能使用Monit进程管理系统进行统一管理，不再兼容8.0版之前的系统

#### 变更

1. 修改[使用说明](https://github.com/JACK-THINK/SCRIPTS-BOOTLOADER-FOR-ASUS-ROUTER/blob/master/How_to_Use.md)为图文版

#### 删除

1. 无

## 版本7.0（2018-07-24）

#### 新增

1. 新增python2环境

#### 变更

1. 修改开机启动逻辑，使用monit插件管理服务类程序

#### 删除

1. 无

## 版本6.3（2018-07-19）

#### 新增

1. 无

#### 变更

1. 修改部分程序执行逻辑，提高执行效率

#### 删除

1. 无

## 版本6.2（2018-06-01）

#### 新增

1. 无

#### 变更

1. 提高Entware环境的兼容性

#### 删除

1. 无

## 版本6.1（2018-05-31）

#### 新增

1. 无

#### 变更

1. 提高Entware环境的兼容性

#### 删除

1. 无

## 版本6.0（2018-05-21）

#### 新增

1. 新增[开发工具插件](https://github.com/JACK-THINK/SCRIPTS-BOOTLOADER-FOR-ASUS-ROUTER/tree/master/script_bootloader/usr/development_tools)（含gcc，python3，pip3，coreutils及全部include文件）。本插件安装的程序较多，对U盘空间要求较高

#### 变更

1. 取消强制开启虚拟内存功能。将swap功能做成插件，供有需要的用户手动安装
2. 将entware安装程序及swap安装程序移至各自的bin目录

#### 删除

1. 无

## 版本5.0（2018-05-15）

#### 新增

1. 新增插件[开发标准文档](https://github.com/JACK-THINK/SCRIPTS-BOOTLOADER-FOR-ASUS-ROUTER/blob/master/Instruction_for_Add-on_Development.md)，并配有[示例](https://github.com/JACK-THINK/SCRIPTS-BOOTLOADER-FOR-ASUS-ROUTER/blob/master/script_bootloader/usr/software)
2. 系统安装日志会表明路由器型号
3. 自动维护插件程序结束列表，不再需要用户手动编写

#### 变更

1. 重新调整程序执行逻辑
2. 进一步使用软编码，提高程序健壮性
3. 为便于插件开发，大幅调整目录结构。使用本版本必须全新安装，不能基于旧版升级

#### 删除

1. 无

## 版本4.0（2018-05-12）

#### 新增

1. 新增对U盘目录`/home/`的操作提示
2. 新增注释，明确文件类型
3. 新增默认开启虚拟内存
4. 重新调整程序执行逻辑
5. 全新采用软编码，程序可自适应U盘卷标

#### 变更

1. 提高Entware安装程序的兼容性

#### 删除

1. 无

## 版本3.1（2018-05-06）

#### 新增

1. 无

#### 变更

1. 在使用过程中发现Entware的部分软件对`/home`目录没有写权限，本次更新将`/home`目录迁移至U盘中，以解决此问题

#### 删除

1. 无

## 版本3.0（2018-05-01）

#### 新增

1. 新增华硕路由器固件类型检测功能，可根据固件种类自动配置运行环境
2. 新增**虚拟内存**功能（swap），以确保Entware在部分型号路由器上流畅运行（默认禁用，启用方法见[使用说明](https://github.com/JACK-THINK/SCRIPTS-BOOTLOADER-FOR-ASUS-ROUTER/blob/master/How_to_Use.md)）

#### 变更

1. 前一版本出现重大bug：Entware不能安装于运行华硕官方固件的部分型号的华硕路由器，本版已修正

#### 删除

1. 无

## 版本2.2（2018-04-30）

#### 新增

1. 提高兼容性，避免路由器上插2个及以上U盘时，`sda1`引用错误U盘的情况
2. 提供U盘卷标修改工具`label_modifier`，默认会修改U盘卷标为`ASUS_ROUTER`并格式化。**使用前必须做好内容备份，并拔掉路由器上的其它全部U盘**

#### 变更

1. 无

#### 删除

1. 无

## 版本2.1（2018-04-30）

#### 新增

1. 无

#### 变更

1. 修改源代码注释拼写错误

#### 删除

1. 无

## 版本2.0（2018-04-29）

#### 新增

1. 新增[Entware](https://github.com/Entware/Entware)安装程序`Entware_install`，可根据路由器型号自动安装匹配的Entware版本，无需用户参与安装过程
2. 本系统（含Entware）运行于U盘，完全脱离路由器`/jffs`分区
3. 本系统（含Entware）适用于华硕原厂固件和华硕梅林固件

#### 变更

1. 采用全新项目名称**SCRIPTS BOOTLOADER FOR ASUS ROUTER**
2. 采用全新的目录结构及文件名，以兼容[Entware](https://github.com/Entware/Entware)
3. 重新编写每个程序内容，统一编码及注释风格，便于用户阅读

#### 删除

1. 删除系统中全部`vlmcsd`字样

## 版本1.0（2018-04-27）

1. **ASUSWRT-and-ASUS_MERLIN-Self-Starting-Scripts**版本1.0发布