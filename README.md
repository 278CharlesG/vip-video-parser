# VIP Video Parser

![Python Version](https://img.shields.io/badge/python-3.6%2B-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

这是一个适用于国内主流视频平台的，基于 Python Tkinter 编写的轻量级桌面端小工具，通过调用第三方视频解析接口来实现浏览器重定向跳转以绕过VIP会员检测，仅供于参考，交流，及学习使用。

##  功能特点

* **轻量级**：基于 Python 内置库 `tkinter` 开发，无需安装复杂的第三方依赖，即开即用。
* **第三方接口支持**：内置 8 个备用的第三方视频解析 API 接口，可通过下拉菜单自由切换，防止单接口失效。
* **平台导航**：提供爱奇艺、腾讯视频、优酷视频三大主流平台的快捷直达按钮。
* **链接处理**：自动检测并补全 `https://` 前缀，并对输入的视频 URL 进行安全的 `urllib.parse.quote` 编码，避免特殊字符导致解析失败。
* **跨平台**：得益于 Python 和 Tkinter 的特性，支持在 Windows、macOS 和 Linux 上运行。

##  环境要求

* **Python 3.6** 或更高版本。
* 依赖库：`tkinter`, `webbrowser`, `urllib.parse`。

##  使用方法

1. 克隆本仓库到本地：
   ```bash
   git clone [https://github.com/你的用户名/你的仓库名.git](https://github.com/你的用户名/你的仓库名.git)
2. 打开对应平台，进入您想绕过的视频网页界面
3. 复制该界面的浏览器地址并黏贴到程序内
4. 选择可支持的解析接口
5. 留下您的意见与建议
