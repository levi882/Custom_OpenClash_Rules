<h1 align="center">🚀 OpenClash + SmartDNS 综合优化方案<br>⠀⠀&<br>🧩 全分组防泄漏与 BT/PT 兼容增强规则</h1>

<p align="center">
	<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/levi882/Custom_OpenClash_Rules_SmartDNS_BTPT?style=flat">
	<img alt="GitHub contributors" src="https://img.shields.io/github/contributors/levi882/Custom_OpenClash_Rules_SmartDNS_BTPT?style=flat">
	<img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/t/levi882/Custom_OpenClash_Rules_SmartDNS_BTPT?style=flat">
	<a href="https://github.com/levi882/Custom_OpenClash_Rules_SmartDNS_BTPT/wiki">
		<img src="https://img.shields.io/badge/wiki-online-blue?style=flat&logo=bookstack" alt="Wiki">
	</a>
</p>
<p align="center"><b>✨ 让你的 OpenClash 与 SmartDNS 协同工作得更优雅、更高效 ✨</b></p>

---

## 📚 目录
- [📖 项目简介](#-项目简介)
- [🧠 功能亮点](#-功能亮点)
- [🛠️ 使用说明](#%EF%B8%8F-使用说明)
- [📘 Wiki 与原版配合](#-wiki-与原版配合)
- [⚠️ 特别声明](#%EF%B8%8F-特别声明)
- [🤝 致谢与来源](#-致谢与来源)
- [📝 许可协议](#-许可协议)

---

## 📖 项目简介

> **基于 Aethersailor 的 [Custom_OpenClash_Rules](https://github.com/Aethersailor/Custom_OpenClash_Rules) 二次拓展版本**  
> 本项目整合了 SmartDNS 与 BT/PT 下载兼容方案，使 OpenClash 运行更加稳定、高效与智能。

本方案适用于：
- ✅ 使用 OpenWrt / iStoreOS 的用户  
- ✅ 希望通过 SmartDNS 实现 CN/Non-CN 精准分流
- ✅ 需要广告过滤+隐私保护
- ✅ 需要兼容 qBittorrent / Transmission / PT Tracker 的环境  
- ✅ 希望一站式配置透明代理 + DNS 加速的用户  

---

## 🧠 功能亮点

### 🧩 1. SmartDNS 深度整合
- 支持 DoH / DoT 混合上游
- 实现 CN / Non-CN 分组测速与缓存优选
- 支持 fallback 与 proxy-server-nameserver 策略
- 兼容 SmartDNS UI 与 OpenClash Dashboard 调试

### 🌀 2. BT/PT 下载兼容优化
- 提供 `GeoSite:category-public-tracker` 独立规则组  
- 解决 Fake-IP 导致 Tracker 不通或连接中断的问题  
- 自动识别 Tracker 域名直连 / 代理分流策略  
- 适配 qBittorrent、Transmission、aria2 等主流客户端  

### 🧠 3. 高可定制分流体系
- 新增 SmartDNS 与 Clash 联动的规则模板
- 支持自动同步上游 GEO 数据与直连名单
- 兼容 IPv6 + Fake-IP 双栈环境
- 结构清晰、便于二次开发或自定义扩展  

---

## 🛠️ 使用说明

> 本项目配置兼容原版 Wiki，增加了 SmartDNS 与 Tracker 支持章节。

详细教程请参见 Wiki：

- 🔹 原项目 Wiki（配合使用）：  
  👉 [https://github.com/Aethersailor/Custom_OpenClash_Rules/wiki](https://github.com/Aethersailor/Custom_OpenClash_Rules/wiki)
- 🔹 本项目 Wiki：  
  👉 [https://github.com/levi882/Custom_OpenClash_Rules_SmartDNS_BTPT/wiki](https://github.com/levi882/Custom_OpenClash_Rules_SmartDNS_BTPT/wiki)  


> 📘 **建议：**
> 先阅读 Aethersailor 原项目 Wiki 了解基础配置，再参考本仓库 Wiki 进行增强与扩展设置。  
> 这两个项目可以配合使用，互为补充。

---

## ⚠️ 特别声明

1. 本项目仅供研究、交流与教学用途。  
2. 不保证所有内容的合法性、完整性或时效性。  
3. 请在 24 小时内删除本项目相关内容。  
4. 使用本项目产生的任何后果与本项目维护者无关。  
5. 本项目为非盈利性质，允许转载与修改，请保留原项目与本仓库链接。

---

## 🤝 致谢与来源

本项目感谢以下优秀开源项目与作者：

- [Aethersailor/Custom_OpenClash_Rules](https://github.com/Aethersailor/Custom_OpenClash_Rules) — 原始框架与 Wiki 结构  
- [vernesong/OpenClash](https://github.com/vernesong/OpenClash) — OpenWrt 核心插件  
- [pymumu/smartdns](https://github.com/pymumu/smartdns) — 高性能本地 DNS 转发器  
- [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo) — Clash 核心  
- [asdlokj1qpi233/subconverter](https://github.com/asdlokj1qpi233/subconverter) — 订阅转换后端  

---

## 📝 许可协议

[![](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/deed.zh)
> 本项目采用 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.zh) 协议  
> 欢迎二次开发与分享，请保留原项目链接。

---
