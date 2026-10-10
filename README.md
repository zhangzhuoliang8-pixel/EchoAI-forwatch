# 回声AI · Echo AI

专为 **Android / Wear OS 手表**打造的 AI 助手。

> 本仓库**只发布 release 安装包，不含源码**。每个版本的安装包都在 [Releases](https://github.com/zhangzhuoliang8-pixel/EchoAI-forwatch/releases) 页面。


- 反馈邮箱：echoai_xyz@outlook.com

## ⬇️ 下载最新版

### 👉 [**点这里下载最新版 APK**](https://github.com/zhangzhuoliang8-pixel/EchoAI-forwatch/releases/latest/download/EchoAI-4.0FIX-v26.apk) 👈

上面这个链接**永远指向最新版本**，可以直接分享给朋友、贴到群里，不用每次换链接：

```text
https://github.com/zhangzhuoliang8-pixel/EchoAI-forwatch/releases/latest/download/EchoAI-4.0FIX-v26.apk
```

也可以直接到 [Releases](https://github.com/zhangzhuoliang8-pixel/EchoAI-forwatch/releases) 页面挑指定版本下载。

## 当前最新版本

| 项目 | 值 |
| --- | --- |
| 版本名 | `4.0FIX` |
| 版本号（versionCode） | `26` |
| 应用包名 | `watch.zl.echo.ai` |
| 安装包文件名 | `EchoAI-4.0FIX-v26.apk` |
| 文件大小 | 4.67 MiB（4900493 字节） |
| 发布日期 | 2026-10-10 |
| 系统要求 | Android 8.0（API 26）及以上 · Wear OS 3+ |
| SHA-256 | `9A170375B7672B79E6D196A34130172720EC60054AF071A3387F748E345FDFE8` |
| 签名证书 SHA-256 | `37c74d638231abe4ffd1150d6e452400ef7a2b0a94ad7a20e0fe12ee73e5e9f3` |
| 本版对应 Release | [v4.0FIX](https://github.com/zhangzhuoliang8-pixel/EchoAI-forwatch/releases/tag/v4.0FIX) |

## 安装方法

### 方式一：手机上直接安装（最简单）

1. 用手机浏览器打开上面的下载链接；
2. 下载完成后，点开下载好的 `EchoAI-4.0FIX-v26.apk`；
3. 系统提示「未知来源应用」时，允许浏览器或文件管理器安装；
4. 安装完成后打开「回声AI」，按提示注册 / 登录即可使用。

### 方式二：装到 Wear OS 手表

- 手表和手机配对后，部分机型可用手机上的「Wear OS」应用推送安装；
- 更通用的做法是直接用 adb 侧载（见方式三），数据线连手表时注意开启「开发者选项 → ADB 调试」；
- 手表上首次使用需要联网，建议先配好 Wi-Fi。

### 方式三：用 adb 安装（推荐给开发者）

```bash
adb install -r EchoAI-4.0FIX-v26.apk
```

升级安装（保留数据）就用上面这条；如果提示签名不一致，说明你装过非官方签名的包，需要先卸载旧包。

## 校验下载的安装包是否完整

下载后可以核对 SHA-256，和上表一致就说明文件没有损坏、也没有被替换：

Windows（PowerShell）：

```powershell
Get-FileHash .\EchoAI-4.0FIX-v26.apk -Algorithm SHA256
```

macOS / Linux：

```bash
sha256sum EchoAI-4.0FIX-v26.apk
```

期望值：

```text
9A170375B7672B79E6D196A34130172720EC60054AF071A3387F748E345FDFE8
```

## 安全提示

- 官方发布渠道只有两个：**本仓库的 Releases**（手动下载）和 **App 内置更新**（官网 <https://echoai1.xyz>）。除此之外的下载站、网盘、群文件都与本项目无关；
- 官方安装包的签名证书 SHA-256 固定为 `37c74d638231abe4ffd1150d6e452400ef7a2b0a94ad7a20e0fe12ee73e5e9f3`，如果从其它渠道拿到安装包，可以用下面的命令确认指纹一致再安装：

```bash
# 需要 Android SDK build-tools
apksigner verify --print-certs EchoAI-4.0FIX-v26.apk
```

- 本仓库不含源码、不接受 PR；使用中遇到问题请发邮件到 echoai_xyz@outlook.com。

## 历史版本

所有历史版本都在 [Releases](https://github.com/zhangzhuoliang8-pixel/EchoAI-forwatch/releases) 页面。旧版本不会再收到更新，遇到问题请先升级到最新版。

## English

**Echo AI** — an AI assistant for Android phones and Wear OS watches.

- **Download the latest APK:** [EchoAI-4.0FIX-v26.apk](https://github.com/zhangzhuoliang8-pixel/EchoAI-forwatch/releases/latest/download/EchoAI-4.0FIX-v26.apk) (permanent link, always points to the newest release)
- Requires Android 8.0 (API 26)+ / Wear OS 3. No source code in this repository; release packages only.
- SHA-256 of the current build: `9A170375B7672B79E6D196A34130172720EC60054AF071A3387F748E345FDFE8`
