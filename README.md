# QunQun Releases

公开发布 QunQun Android 安装包和版本说明。

## 当前版本

- 版本：`6324.4`
- versionCode：`10`
- 安装包：[DisQun-6324.4-debug.apk](./DisQun-6324.4-debug.apk)

仓库保留一个历史版本：[`DisQun-1.0.3-debug.apk`](./DisQun-1.0.3-debug.apk)。

安装包也可以通过 GitHub 的仓库文件页下载。

## 客户端更新清单

客户端启动时会读取仓库根目录的 [`update.json`](./update.json)。发布新版本时请递增
`versionCode`，填写 `versionName`、`downloadUrl` 和 APK 的 SHA-256；当旧版本低于
`minSupportedVersionCode` 时客户端会强制更新，其余版本会显示可取消的更新提示。
