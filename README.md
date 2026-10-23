# 艾泽拉斯插件管家 · 开发版发布

此仓库仅用于发布 macOS 安装包（DMG）、SHA-256、更新清单与发布说明，不包含应用源码。

- 官网：https://azerothkit.online
- 安装包：https://github.com/Yaowen11/azerothkit-releases/releases
- 当前支持 Apple Silicon（arm64），macOS 13 或更新版本。
- 当前为本地临时签名的开发版，尚未完成 Developer ID 签名与 Apple 公证。
- 请勿为了运行开发版关闭系统安全保护。

下载 DMG 及同名 `.sha256` 文件后，在所在目录执行：

```sh
shasum -a 256 -c AzerothAddonManager-*.dmg.sha256
```

GitHub 自动生成的 Source code 压缩包仅含本仓库的说明文件，不是客户端源码。
问题与建议请通过官网留言反馈。
