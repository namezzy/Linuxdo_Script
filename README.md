# 🧩 Linuxdo 保活优化版（面板控制）

![Tampermonkey](https://img.shields.io/badge/Tampermonkey-UserScript-blue?logo=googlechrome)
![Version](https://img.shields.io/badge/version-0.5.0-brightgreen)
![License](https://img.shields.io/badge/license-MIT-lightgrey)
![Status](https://img.shields.io/badge/status-active-success)

> 🦾 一个用于 [Linux.do](https://linux.do) 的自动化保活脚本  
> 自动浏览、自动点赞、可视化统计面板 + 启动/停止/暂停控制，一站式挂机利器 🚀

---

## 📖 目录
- [✨ 功能特性](#-功能特性)
- [🧰 安装方法](#-安装方法)
- [🖥️ 使用说明](#️-使用说明)
- [⚙️ 配置参数](#-配置参数)
- [📸 界面预览](#-界面预览)
- [🧾 更新日志](#-更新日志)
- [🧑‍💻 作者](#-作者)

---

## ✨ 功能特性

| 功能 | 说明 |
|------|------|
| 👀 自动浏览 | 模拟用户行为自动浏览帖子，滚动停留避免被识别为机器人 |
| 💖 自动点赞 | 智能识别高热度帖（浏览量 > 500）并自动点赞 |
| 📊 实时统计 | 面板实时显示运行时长、浏览数、点赞数 |
| 🕹️ 面板控制 | 支持“开始 / 停止 / 暂停 / 恢复”，无需刷新页面 |
| 📦 数据持久化 | 本地保存浏览量和点赞数（GM_setValue） |
| 🪶 可移动悬浮窗 | 面板可拖拽移动并支持最小化 |
| 🛡️ 防卡死机制 | 自动检测运行状态，防止重复执行或长时挂起 |

---

## 🧰 安装方法

1. 安装浏览器扩展 👉 [Tampermonkey](https://www.tampermonkey.net/)
   - 适用于 Chrome / Edge / Firefox / Safari 等浏览器。

2. 访问 [Linux.do](https://linux.do)

3. 安装脚本  
   在 Tampermonkey 中点击 **“添加新脚本”**，粘贴以下代码：  
   或直接访问：
   ```bash
   https://github.com/<你的用户名>/linuxdo-helper/raw/main/linuxdo-helper.user.js
