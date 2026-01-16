# 🗺️ 图寻辅助脚本

> **声明**：本脚本仅供地理知识学习、复盘分析使用。请勿在排位赛等竞技场景中使用，维护良好的游戏环境。

[![Generic badge](https://img.shields.io/badge/Version-1.0-green.svg)](https://tuxun.fun)
[![QQ](https://img.shields.io/badge/QQ-Join-blue.svg)]([https://t.me/tuxunScript](https://qm.qq.com/cgi-bin/qm/qr?k=OlfV_hqd2kMBskEBU0fGmcs1sOyzNISW&jump_from=webapi&authKey=c/lT+eQELbfJSC1flJVTgUjSUfJPMyqWLYhAjt/gAg0sEfL8wqlAfBYzxwxyZLVd))
[![Telegram](https://img.shields.io/badge/Telegram-Join-blue.svg)](https://t.me/tuxunScript)

## 📖 简介

这是一个专为 [图寻 (tuxun.fun)](https://tuxun.fun) 设计的辅助脚本。本脚本主打**极简**与**隐蔽**。它不会在页面上添加任何按钮或面板，而是将获取到的地理位置信息静默输出到浏览器控制台 (Console) 中，极大降低了被检测的风险，同时保持界面清爽。

## ✨ 核心特性

*   **🕵️‍♂️ 极致隐蔽**：不在页面插入任何 DOM 元素，完全无痕运行，通过 Proxy 代理拦截数据。
*   **📍 精准定位**：
    *   **高德模式**：集成高德地图 API，国内位置可精确到街道/村庄（需配置 Key）。
    *   **OSM 模式**：无需 Key，基于 OpenStreetMap，覆盖全球。
*   **🖥️ 控制台输出**：所有信息仅在 F12 控制台显示，字体清晰，支持一键复制。
*   **🚀 极速响应**：采用防抖机制，移动位置后自动更新信息。

## 📥 安装与使用

访问我们的 **[官方发布页](https://txs.de5.net/)** 查看详细教程。


## ⚙️ 配置指南 (高德 API)

为了获得最准确的国内位置信息，建议配置高德地图 API Key：

1.  前往 [高德开放平台](https://console.amap.com/dev/index) 注册账号。
2.  创建新应用，添加 Key。
3.  **注意**：服务平台必须选择 **【Web服务】** (不是 Web端 JSAPI)。
4.  进入游戏，脚本首次运行会提示输入 32 位 Key。

## 🎮 快捷键说明

| 按键 | 功能 | 说明 |
| :--- | :--- | :--- |
| **F12** | 打开控制台 | **必须操作**，否则看不到信息 |
| **I** | 刷新位置 | 手动重新获取当前位置信息 |
| **R** | 重置设置 | 清除保存的 Key 和配置，重新初始化 |  

💬 QQ群: 1080091589
✈️ TG: t.me/tuxunScript# tuxunScript
