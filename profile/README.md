<div align="center">

<img src="https://avatars.githubusercontent.com/u/348836906?s=200&v=4" width="112" alt="ArchoeraC">

# ArchoeraC

**嗯……如你所见，这里是 ArchoeraC。**

一个由 Archoera 与 [BetaStudio2](https://github.com/BetaStudio2) 维护的小作坊<br>
至于 Archoera 是谁……不用管，这不是重点 awa

<p>
  <a href="https://github.com/ArchoeraC/ArchoeraMusic"><img src="https://img.shields.io/badge/ArchoeraMusic-%E5%90%AC%E6%AD%8C-2E7D32?style=flat-square" alt="ArchoeraMusic"></a>
  <a href="https://github.com/ArchoeraC/ArchoeraCX"><img src="https://img.shields.io/badge/ArchoeraCX-%E5%BC%80%E6%B8%B8%E6%88%8F-3C8527?style=flat-square" alt="ArchoeraCX"></a>
  <a href="#许可证"><img src="https://img.shields.io/badge/license-AGPL--3.0-6E4AFF?style=flat-square" alt="AGPL-3.0"></a>
</p>

[音乐](#archoeramusic--把歌听完)　·　[启动器](#archoeracx--把游戏开起来)　·　[规矩](#一些不成文的规矩)　·　[联系](#联系与贡献)

</div>

---

## 我们在做什么

这里目前摆着两件作品：一件用来听歌，一件用来开游戏。看起来毫不相干，骨子里却是同一种做法。

| 项目 | 一句话 |
| :--- | :--- |
| 🎵 **[ArchoeraMusic](https://github.com/ArchoeraC/ArchoeraMusic)** | 开源、多端、面向本地与在线音乐的混合架构播放器 |
| ⛏️ **[ArchoeraCX](https://github.com/ArchoeraC/ArchoeraCX)** | 开源、多端、面向 Minecraft: Java Edition 的混合架构启动器 |

**共同底色**

- **界面** —— Flutter 一套代码，桌面三端一致
- **重活** —— C / C++ / C# / Rust / Go / Zig 原生模块，进程内 FFI 直连
- **干净** —— 拒绝大运行时
- **克制** —— 不要求管理员 / root，数据留在你自己机器上

## ArchoeraMusic —— 把歌听完

> 开源、多端、面向本地与在线音乐的混合架构播放器

<p>
  <a href="https://github.com/ArchoeraC/ArchoeraMusic/releases"><img src="https://img.shields.io/github/v/release/ArchoeraC/ArchoeraMusic?label=release&color=2E7D32&style=flat-square" alt="release"></a>
  <a href="https://github.com/ArchoeraC/ArchoeraMusic/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPL--3.0--or--later-2E7D32?style=flat-square" alt="license"></a>
  <a href="https://github.com/ArchoeraC/ArchoeraMusic"><img src="https://img.shields.io/badge/platform-Linux%20%7C%20Windows%20%7C%20macOS-555?style=flat-square" alt="platform"></a>
</p>

<p align="center">
  <a href="https://betastudio2.github.io/ArchoeraMusic/"><img src="https://raw.githubusercontent.com/ArchoeraC/ArchoeraMusic/main/site/assets/img/home.webp" width="680" alt="ArchoeraMusic 主界面"></a><br>
  <sub>主界面 · 点图前往宣传页</sub>
</p>

- **在线** —— 连接**主流音乐源**，提供在线服务，也能安安静静只听本地
- **本地** —— 本地音乐库扫描与元数据刮削、多平台下载
- **引擎** —— 内置统一 C 音频引擎：EQ / 响度归一化 / 限幅器 / FFT 频谱 / 变速变调 / Opus 转码管线
- **串流** —— 可选 Subsonic 兼容服务端，并聚合 Subsonic / Jellyfin 流媒体服务器
- **底线** —— 不塞广告、不做遥测、不搞付费解锁；安装包默认 per-user，不要管理员

<details>
<summary><b>发布产物</b>（点开看看）</summary>

| 平台 | 格式 |
| :--- | :--- |
| Linux | tar.gz · AppImage · deb · rpm · Arch pkg · Flatpak · NixOS |
| Windows | 便携 zip · 安装器 |
| macOS | arm64 tar.gz |

全部产物附 `.sig1` 分离签名、`SHA256SUMS` 与 SBOM。

</details>

**入口**：[仓库](https://github.com/ArchoeraC/ArchoeraMusic) · [下载](https://github.com/ArchoeraC/ArchoeraMusic/releases) · [宣传页](https://betastudio2.github.io/ArchoeraMusic/) · [架构设计](https://github.com/ArchoeraC/ArchoeraMusic/blob/main/docs/architecture.md) · [自编译手册](https://github.com/ArchoeraC/ArchoeraMusic/blob/main/docs/user-build-from-source.md) · [疑难解答](https://github.com/ArchoeraC/ArchoeraMusic/blob/main/docs/troubleshooting.md)

## ArchoeraCX —— 把游戏开起来

> 开源、多端、面向 Minecraft: Java Edition 的混合架构启动器

<p>
  <a href="https://github.com/ArchoeraC/ArchoeraCX/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPL--3.0--only-3C8527?style=flat-square" alt="license"></a>
  <a href="https://github.com/ArchoeraC/ArchoeraCX"><img src="https://img.shields.io/badge/status-%E5%BC%80%E5%8F%91%E7%89%88-E67E22?style=flat-square" alt="开发版"></a>
  <a href="https://github.com/ArchoeraC/ArchoeraCX"><img src="https://img.shields.io/badge/platform-Linux%20%7C%20Windows%20%7C%20macOS-555?style=flat-square" alt="platform"></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/ArchoeraC/ArchoeraCX/main/app/assets/branding/archoera_icon_512.png" width="96" alt="ArchoeraCX">
</p>

> [!WARNING]
> **开发版**：目前仅通过 GitHub 发布，功能不完整，可能损坏实例或配置数据；请勿用于正式环境或重要实例。

- **实例** —— SQLite 索引 + `instance.json` 权威元数据，原版安装 / 启动，Java 自动扫描
- **加载器** —— Fabric / Quilt / Forge / NeoForge 安装与修复；Modrinth 与本地 `.mrpack` 整合包
- **登录** —— Microsoft 登录（Authorization Code + PKCE，loopback）与离线启动
- **下载** —— Rust `DownloadPlan` 执行器：哈希校验、原子落盘、分片续传、进度与取消
- **体验** —— AppShell + 明暗主题、系统主题色、中英文 i18n，安装与下载统一走后台任务

**分层很硬**：Flutter 只管 UI，C++20 做生命周期与路由，C# NativeAOT 独占 API / 业务 / SQLite，Rust 只执行下载计划。构建、测试与数据目录见 [构建手册](https://github.com/ArchoeraC/ArchoeraCX/blob/main/docs/12-build-and-test.md)。

**入口**：[仓库](https://github.com/ArchoeraC/ArchoeraCX) · [文档索引](https://github.com/ArchoeraC/ArchoeraCX/blob/main/docs/README.md) · [架构设计](https://github.com/ArchoeraC/ArchoeraCX/blob/main/docs/10-architecture-design.md) · [发行与下载策略](https://github.com/ArchoeraC/ArchoeraCX/blob/main/docs/09-distribution-and-download-policy.md)

> 本项目与 Mojang Studios、Microsoft 无关联，不分发游戏本体或资源文件，也不提供绕过正版验证的服务。
> NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.

## 一些不成文的规矩

| 原则 | 我们怎么做 |
| :--- | :--- |
| **不塞广告** | 没有广告 SDK、开屏、横幅与推广位 |
| **不做遥测** | 不埋点、不上报使用数据、不接云端崩溃 SaaS |
| **不搞付费解锁** | 功能不靠付费上锁，完整使用不需要一分钱 |
| **最小权限** | 运行时不要管理员 / root，不写系统目录，不装服务与驱动 |
| **数据在本地** | 凭据进系统密钥环或保险库，token 不跨边界、不进日志 |
| **开源是底色** | 依照 License 自由使用、学习、修改与再分发；分发时保留声明并标注修改 |
| **不搬「预制菜」** | 不复制其它启动器 / 播放器的代码与素材，第三方依赖逐项登记许可 |
| **说人话** | 不踩一捧一，不做不公平比对 |

## 许可证

| 项目 | 许可证 | 说明 |
| :--- | :--- | :--- |
| 🎵 ArchoeraMusic | **AGPL-3.0-or-later** | 允许商业使用，不提供闭源商业授权 |
| ⛏️ ArchoeraCX | **AGPL-3.0-only** | 遵守 AGPL 义务即可自由使用、修改与再分发 |

两个项目均**不提供闭源商业授权**；第三方依赖与内嵌运行库见各自的 `THIRD-PARTY-NOTICES.md`。

> AGPL 不是摆设：分发或提供网络服务时，请开放源码、保留声明并标注你的修改。

> [!CAUTION]
> 偷？自己拿去闭源？超市你！

## 联系与贡献

| 渠道 | 说明 |
| :--- | :--- |
| [ArchoeraMusic Issues](https://github.com/ArchoeraC/ArchoeraMusic/issues) | 缺陷、崩溃日志与建议，记得脱敏 |
| [ArchoeraCX Issues](https://github.com/ArchoeraC/ArchoeraCX/issues) | 同上；开发版的问题也欢迎反馈 |
| `SECURITY.md` | 安全漏洞走私密渠道，**不要**公开讨论细节 |
| [CONTRIBUTING.md](https://github.com/ArchoeraC/ArchoeraMusic/blob/main/CONTRIBUTING.md) | Music 接受 PR，合入前需接受贡献者授权 |

代码贡献：ArchoeraMusic 接受 PR（先读贡献规范并接受贡献者授权）；ArchoeraCX **不接受外部代码贡献**，欢迎 Issue 与文档纠错。

---

<div align="center">

*ArchoeraC 是一家不太正经的小作坊，但做出来的东西是正经的（骗你的只是作者闲得没事干用来浪费token的）。*

*这里是 ArchoeraC，很不高兴为您服务 awa*

<sub>© ArchoeraC · 如有雷同，纯属巧合</sub>

</div>
