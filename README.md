# VIP Video Parser (VIP追剧神器)

![Python Version](https://img.shields.io/badge/python-3.6%2B-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

一个基于 Python Tkinter 编写的轻量级桌面端小工具。通过调用第三方视频解析接口，实现视频流媒体链接的快速解析与浏览器重定向跳转。

## ✨ 功能特点 (Features)

* **轻量级 GUI**：基于 Python 内置库 `tkinter` 开发，无需安装复杂的第三方依赖，即开即用。
* **多接口支持**：内置 8 个备用的第三方视频解析 API 接口，可通过下拉菜单自由切换，防止单接口失效。
* **便捷导航**：提供爱奇艺、腾讯视频、优酷视频三大主流平台的快捷直达按钮。
* **智能链接处理**：自动检测并补全 `https://` 前缀，并对输入的视频 URL 进行安全的 `urllib.parse.quote` 编码，避免特殊字符导致解析失败。
* **跨平台**：得益于 Python 和 Tkinter 的特性，支持在 Windows、macOS 和 Linux 上运行。

## 🛠️ 环境要求 (Prerequisites)

* **Python 3.6** 或更高版本。
* 依赖库：`tkinter`, `webbrowser`, `urllib.parse`（均为 Python 标准库，无需通过 `pip` 额外安装）。
  > **注意**：部分 Linux 发行版可能需要手动安装 tkinter 系统包（例如 Ubuntu: `sudo apt-get install python3-tk`）。

## 🚀 使用方法 (Usage)

1. 克隆本仓库到本地：
   ```bash
   git clone [https://github.com/你的用户名/你的仓库名.git](https://github.com/你的用户名/你的仓库名.git)
