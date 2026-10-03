# EhViewer Desktop · Windows releases

此仓库只发布 Windows x64 安装包、更新签名和 `latest.json` 更新清单。应用源代码保存在用户的私人仓库中。

## 下载

打开 [Releases](https://github.com/koshea114/ehviewer-desktop-releases/releases)，下载最新版本的 `EhViewer Desktop_*_x64-setup.exe`。

从 0.2.0 开始，应用的「连接与设置 → 应用更新」会检查本仓库的新版本。点击「下载并更新」后自动下载、验证更新签名和安装，不需要 GitHub 登录。0.1.x 没有更新器，需要手动安装 0.2.0 一次。

更新保持相同的应用身份，保留本地设置、阅读进度和系统凭据库内的登录状态。网站会话过期或要求额外验证时，仍需要在应用内登录窗口重新验证。

每个发布版附带安装程序的 `.sig` 签名、`latest.json` 和 SHA-256 校验清单。更新器强制验证签名及签名绑定的版本，拒绝未签名或被修改的更新包。该更新签名与 Windows Authenticode 代码签名是不同机制；当前安装程序没有 Authenticode 签名。

此项目为独立桌面客户端，不是 Android 上游的官方桌面版本。
