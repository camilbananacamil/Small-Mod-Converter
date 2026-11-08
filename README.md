# 🚀 Small-Mod-Converter (小型模组转换器)

> **⚠️ 免责声明 (Disclaimer):**
> 本项目目前处于 **测试阶段 (Testing Phase)**。
> **仅支持 Minecraft 1.21.1 版本**，且为了服务器稳定，**仅支持上传不大于 20MB 的模组**。
> 本工具生成的源码需要借助 IntelliJ IDEA 进行最终编译。请勿将本工具用于商业倒卖，开源不易，且用且珍惜。

An AI-powered Minecraft mod loader converter based on Python, DeepSeek API, and Gradle. It helps you seamlessly translate mods between Fabric, Forge, and NeoForge. (Currently in testing phase, only supports 1.21.1 and files ≤ 20MB).

基于 Python、DeepSeek API 和 Gradle 的 AI 驱动 Minecraft 模组跨平台转换器。帮你把模组在 Fabric、Forge 和 NeoForge 之间无缝转换。

---

## ✨ 核心特性 (Features)
- **AI 智能翻译**：接入 DeepSeek 大模型，自动重写跨平台的 Java 代码。
- **工业级编译**：放弃容易出错的纯 Python 编译，无缝调用官方 Gradle MDK 环境，确保生成的源码符合 IDEA 工程规范。
- **极客开源**：无任何后门与暗桩，API Key 本地运行，用完即焚。
- **自动更新**：自带热更新引擎，每次启动自动检测最新版本。

## 🛠️ 使用指南 (Quick Start)

1. 下载并安装 [JDK 21](https://adoptium.net/)。
2. 准备你的 DeepSeek API Key（前往 [DeepSeek 开放平台](https://platform.deepseek.com/) 免费申请）。
3. 下载本仓库 Release 中的 `ruanjian.exe`。
4. 打开软件，填入 Key，拖入你要转换的 `.jar` 模组。
5. 选择目标加载器，点击“开始转换”。
6. 转换完成后，前往桌面找到生成的 `SourcePack.zip`，解压并丢进 IDEA 中点击 `Build` 即可。

## ☕ 支持作者 (Sponsor)
如果这个工具为你节省了几天几夜的时间，欢迎请我喝杯咖啡：
[爱发电链接](https://afdian.com/a/camil0908)

## 📺 关注作者
B 站：@吃甜食的卡米尔

