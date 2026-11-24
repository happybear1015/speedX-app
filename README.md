# speedX

speedX 是一个面向个人和团队的加速客户端，提供 Windows、macOS、Linux 桌面端，以及 Android（手机端 APK）和 iOS / iPadOS 客户端（TestFlight 分发）。

## 功能

- 全平台客户端覆盖：Windows、macOS、Linux、Android、iOS
- 全平台核心路由、分流与节点优选算法严格一致
- 使用账号登录，不公开订阅链接
- 连接前自动体检，发现并修复常见环境问题
- 托盘常驻 / 前台服务、快速连接、连接状态提示
- 套餐、流量、用户由管理员在后台统一管理

## 下载

请在本仓库的 **[Releases](https://github.com/happybear1015/speedX-app/releases)** 页面下载对应平台的最新安装包：

| 平台 | 文件 | 说明 |
| --- | --- | --- |
| Windows x64 | `speedX_x.x.x_x64-setup.exe` | Windows 桌面安装程序 |
| Android (手机端) | `speedX_x.x.x_arm64.apk` | 安卓手机端安装包，下载后直接安装 |
| macOS Apple Silicon | `speedX_x.x.x_aarch64.dmg` | macOS DMG 镜像（双击即可安装） |
| Linux | `speedX_x.x.x_amd64.AppImage` / `.deb` | 通用免安装 AppImage 或 Debian 安装包 |

macOS 正式包使用 Developer ID 签名并经过 Apple 公证，可直接双击打开。每个 Release 的具体签名状态以该 Release 的说明为准。

## 使用

1. 下载并安装对应平台安装包。
2. 打开 speedX，输入管理员提供的账号和密码登录。
3. 在主界面点击连接；连接状态会显示在窗口、托盘图标或手机通知栏中。
4. 如需断开或切换线路，请在界面中操作。

## 移动端（Android / iOS）

- **Android 手机端**：在 Releases 中下载 `speedX_x.x.x_arm64.apk`，在系统提示中允许安装后直接安装使用。
- **iOS / iPadOS**：通过 TestFlight 分发，不提交 App Store。安装邀请和账号由管理员提供。

## 常见问题

### Android 提示“未知来源应用”

这是从 GitHub / 浏览器直接下载 APK 的正常系统安全提醒，点击“允许本次安装”或在设置中开启浏览器安装权限即可。

### macOS 提示“已损坏”或“无法打开”

请确认下载的是最新 Release 中**已签名并公证**的 macOS 包。旧版本可能是 ad-hoc 签名，首次打开需要右键 → 打开。

### 登录失败

请确认账号未过期、套餐未到期，并使用管理员提供的最新账号信息。

### 连接失败

先点击界面中的“连接前体检”查看环境问题；如果仍失败，请联系管理员并提供错误提示。

## 许可与第三方组件

第三方组件许可见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。
