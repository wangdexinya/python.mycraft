# python.mycraft

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-brightgreen)

一个基于 Python 开发的轻量级 Minecraft 相关工具/复刻项目，旨在通过 Python 实现 Minecraft 核心玩法或辅助功能。

## 👨‍💻 作者
eggy_aurora

## 📋 项目介绍
python.mycraft 是一个面向 Minecraft 爱好者和 Python 开发者的开源项目，核心目标是：
- 用 Python 语言复现 Minecraft 的核心游戏逻辑
- 提供易于扩展和二次开发的代码架构
- 帮助开发者学习游戏开发和 Python 进阶编程

## 🛠️ 环境要求
- Python 3.8 及以上版本
- 推荐操作系统：Windows/Linux/macOS

## 🚀 安装步骤
1. 克隆本仓库
```bash
git clone https://github.com/wangdexinya/mycraft-python.git
cd python-mycraft/
```end

2.安装第三方拓展包（使用阿里云镜像加速）
```bash
pip install pygame ursina perlin_noise psutil -i https://mirrors.aliyun.com/pypi/simple/

3.运行项目
```python
python run

## 📁 项目结构
python-mycraft/
├── mycraft/          # 核心代码目录
│   ├── game_core.py       # 游戏主逻辑
│   ├── save_system.py      # 世界生成与存档
│   ├── main_menu.py     # 主菜单
│   ├── pause_menu.py     # 游戏内暂停菜单
│   └── run     # 启动文件
├── requirements.txt  # 依赖清单
└── README.md         # 项目说明文档

## 🤝 贡献名单
- wangdexinya(eggy_aurora)

## 📄 许可证
- 本项目采用 MIT 许可证 - 详见 LICENSE 文件。

## 👨‍💻 作者
wangdexinya(eggy_aurora)
- 邮箱：1636647891@qq.com
- GitHub：https://github.com/wangdexinya
