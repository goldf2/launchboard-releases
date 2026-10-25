# 无界桌面 安装包与更新

当前测试版：**0.10.2-beta.1**（build 13，arm64）。

此仓库只发布安装包、使用说明与原生更新元数据，不包含应用源码或用户资料。

## 下载

- [Sparkle 更新 ZIP](https://github.com/goldf2/launchboard-releases/releases/download/v0.10.2-beta.1/LaunchBoard-0.10.2-beta.1-macos-arm64.zip)
  SHA256：`b1a5195e4036cbe127d27d6e9c90a3a990c64473373169a4efe086f5943cb74d`
- [首次安装 DMG](https://github.com/goldf2/launchboard-releases/releases/download/v0.10.2-beta.1/LaunchBoard-0.10.2-beta.1-macos-arm64.dmg)
  SHA256：`71d3dbf194954f0814a81e2d3afcefa873f8f489439060f0cf7e25a08c6a7961`

## 软件更新

应用菜单与设置中选择“检查更新”。默认接收正式版和测试版通知；下载和安装需要确认。关闭测试版不会降级。现有尚未带更新功能的旧版，需要先手动安装此接入版一次。

更新使用 Sparkle 2.10.0；原生 feed 和 ZIP 均由本产品独立 Ed25519 密钥签名，签名验证保持开启。当前没有正式版，正式渠道不会显示虚构版本。

公开更新源：`https://raw.githubusercontent.com/goldf2/launchboard-releases/main/updates/appcast.xml`

## 当前发行条件

这是 ad-hoc 签名测试包，尚无 Apple Developer ID 签名与公证；无人值守自动安装关闭。下载验签与真正替换旧版是不同验收，本次实际升级尚未完成。应用数据保留在原来的独立数据目录。
