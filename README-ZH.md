<h1 align='center'>
  <image src='assets/Application Icon.png' width='128' />
  <br/>
  Cirrus
  <br/>
  <a href="https://github.com/brandonw3612/Cirrus/blob/main/LICENSE">
    <img alt="GitHub" src="https://img.shields.io/github/license/brandonw3612/Cirrus">
  </a>
  <br/>
  <a href="https://github.com/brandonw3612/Cirrus/blob/main/README.md">
    <img alt="GitHub ReadMe English" src="https://img.shields.io/badge/README-English-lightgray?logo=github">
  </a>
  <a href="https://github.com/brandonw3612/Cirrus/blob/main/README-ZH.md">
    <img alt="GitHub ReadMe Chinese" src="https://img.shields.io/badge/README-中文-lightgray?logo=github">
  </a>
  <br/>
</h1>

Cirrus（前身为 LyricEase）是一款网易云音乐第三方客户端。Cirrus 基于最新的 WinUI 框架构建，旨在为 Windows 11 平台提供现代原生的用户体验。

## 构建

目前该项目处于活跃开发阶段。我们尚未提供官方预编译版本，但你可以使用此仓库自行构建项目。请注意，该项目尚处于早期阶段，代码库可能不稳定。

### 前置要求

请确保你的设备已按照 [Microsoft 文档](https://learn.microsoft.com/en-us/windows/apps/get-started/start-here) 的建议安装了以下工具并进行了配置：

- 已启用 **开发者模式**。
- 已安装 **[Visual Studio 2026](https://visualstudio.microsoft.com/downloads/)**，并包含 **Windows App SDK** 工作负载。
- 已安装 **[.NET 10 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/10.0)**。

### 构建提示

- 如果你想为项目做出贡献，请在 `Debug` 配置下构建。
- 如果你只是想使用该软件，请在 `Release` 配置下创建应用程序包。这需要一个签名证书来对包进行签名，你可以自行创建，也可以从受信任的证书颁发机构获取。我们已使项目支持 NativeAOT，预计生成的安装包体积更小，性能表现也更好。

## 许可与商业用途

本项目采用 Apache License 2.0 协议授权 — 详见 [LICENSE](LICENSE) 文件。
根据 Apache-2.0 协议，你被允许使用、复制、修改和分发本软件（包括用于商业目的），前提是你必须遵守协议条款（例如，保留版权声明并包含必要的声明）。

作者请求：项目作者恳请在未经明确许可的情况下，不要将本软件用于商业产品或服务。此请求并非法律限制，也不会更改 Apache-2.0 协议本身。如果你计划将本项目用于商业产品，请联系维护者讨论许可事宜或获取明确的商业授权。

## 贡献

欢迎参与贡献！在提交 Issue 或 Pull Request 之前，请阅读本仓库的[贡献指南](CONTRIBUTING.md)。贡献指南解释了如何报告 Bug、提议功能、运行构建和测试以及准备 Pull Request。

快速贡献步骤：

- Fork 本仓库并创建一个特性分支（例如 `feat/<名称>` 或 `fix/<名称>`）。
- 保持你的分支与上游默认分支同步。
- 在提交 PR 前，请在本地运行构建和测试（具体命令请参阅 `CONTRIBUTING.md`）。
- 开启一个 PR 并关联任何相关的 Issue。

## 社区

我们也欢迎你订阅以下 Telegram 频道和讨论组，以获取最新消息、参与讨论或寻求帮助。

<a href="https://t.me/project_cirrus">
  <img alt="Telegram" src="https://img.shields.io/badge/Telegram-频道-lightblue?style=flat&logo=telegram&logoColor=white&labelColor=blue">
</a>
<br/>
<a href="https://t.me/project_cirrus">
  <img alt="Telegram" src="https://img.shields.io/badge/Telegram-讨论组-lightblue?style=flat&logo=telegram&logoColor=white&labelColor=blue">
</a>