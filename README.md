# 元空间 · Yuan Space

**yuanspace** 是元空间的开源执行器（桌面端），目前 2.0 开发中，尚未发布可用版本。

元空间是一个 AI 创作工作台：主站 [yuan.space](https://yuan.space)，线上服务运行于 [yuantanzhang.cn](https://yuantanzhang.cn)。

## 它是什么

执行器是装在你自己电脑上干活的那一端：接收任务、调用工具、产出结果。它从设计上就是双模式：

- **本地模式**：不登录，自己配置 API，数据和任务都在本机，适合自己动手能力强的用户。
- **联网模式**：登录元空间账号，连接官方服务。采集/抓取这类能力只在联网模式提供，走官方服务、按积分计费。

## 开源范围

- 本仓库（执行器、插件机制、示例）以 **Apache License 2.0** 开源。
- 元空间的后端——账号、积分与计费、支付、抓取服务、社区数据——不开源，不在本仓库内。执行器通过公开接口与官方服务通信。

## 状态

2.0 开发中。本仓库先行占位，代码随 2.0 节奏陆续进入；当前请勿据此评估可用性。

---

# yuanspace

The open-source executor (desktop) of **Yuan Space**, an AI creation workspace. Version 2.0 is under development; no usable release yet.

- **Local mode**: no account needed, bring your own API keys, everything runs on your machine.
- **Online mode**: sign in with a Yuan Space account to use official services; capture/fetch features are online-only and billed in credits server-side.

The executor, its plugin mechanism and examples are released under the **Apache License 2.0**. The Yuan Space backend (accounts, credits and billing, payments, capture services, community data) is not open source and is not part of this repository.
