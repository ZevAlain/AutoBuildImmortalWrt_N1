## ImmortalWrt for 斐讯N1
#### luci版本 24.10.2 固件不是传统ext4和squashfs格式 而是btrfs格式 支持快照
#### 后台地址 路由器后台查询
#### 用户名 `root` 密码：password
#### 是否带docker: 否
#### 默认软件包大小 1GB
#### 内核版本:根据用户选择
#### 晶晨宝盒：✅ 自带 用于写入emmc 写入的时候务必关闭docker 和docker自启动 （这一步等以后稳定再考虑写入 非必要不写入）
#### rootfs.tar.gz 构建采用ImmortalWrt的ImageBuilder
#### 打包img 采用`onhub/amlogic-s9xxx-openwrt` 或 `flippy-openwrt-actions`
#### 默认底包位置：https://github.com/wukongdaily/AutoBuildImmortalWrt/releases/tag/rootfs
