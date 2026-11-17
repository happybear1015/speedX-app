# speedX

speedX 是一个面向个人和团队的加速客户端，提供 Windows、macOS、Linux 桌面版，以及 iPad / iPhone 客户端（TestFlight 分发）。

## 功能

- 三平台桌面客户端：Windows、macOS、Linux
- 使用账号登录，不公开订阅链接
- 连接前自动体检，发现并修复常见环境问题
- 托盘常驻、快速连接、连接状态提示
- 套餐、流量、用户由管理员在后台统一管理

## 下载

请在本仓库的 **Releases** 页面下载对应平台的安装包：

| 平台 | 文件 |
| --- | --- |
| Windows x64 | `speedX_x.x.x_x64-setup.exe` |
| macOS Apple Silicon | `speedX_x.x.x_aarch64.dmg` |
| Linux | `speedX_x.x.x_amd64.deb` / `speedX_x.x.x_amd64.AppImage` |

macOS 正式包使用 Developer ID 签名并经过 Apple 公证，可直接双击打开。每个 Release 的具体签名状态以该 Release 的说明为准。

## 使用

1. 下载并安装对应平台安装包。
2. 打开 speedX，输入管理员提供的账号和密码登录。
3. 在主界面点击连接；连接状态会显示在窗口和托盘图标中。
4. 如需断开或切换线路，请在界面中操作。

## iPad / iPhone

iOS / iPadOS 版本通过 TestFlight 分发，不提交 App Store。安装邀请和账号由管理员提供。

## 常见问题

### macOS 提示“已损坏”或“无法打开”

请确认下载的是最新 Release 中**已签名并公证**的 macOS 包。旧版本可能是 ad-hoc 签名，首次打开需要右键 → 打开。

### 登录失败

请确认账号未过期、套餐未到期，并使用管理员提供的最新账号信息。

### 连接失败

先点击界面中的“连接前体检”查看环境问题；如果仍失败，请联系管理员并提供错误提示。

## 许可与第三方组件

第三方组件许可见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。
