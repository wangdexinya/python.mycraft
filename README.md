# python.mycraft

![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)
![License](https://img.shields.io/github/license/wangdexinya/python.mycraft)
![Status](https://img.shields.io/badge/status-active-brightgreen)

一个基于 Python 开发的轻量级 Minecraft 复刻项目，旨在通过 Python 实现 Minecraft 核心玩法或辅助功能。

## 👨‍💻 作者
- eggy_aurora

## 📋 项目介绍
python.mycraft 是一个面向 Minecraft 爱好者和 Python 开发者的开源项目，核心目标是：
- 用 Python 语言复现 Minecraft 的核心游戏逻辑
- 提供易于扩展和二次开发的代码架构
- 帮助开发者学习游戏开发和 Python 进阶编程

## 🛠️ 环境要求
- Python 3.8 及以上版本
- 推荐使用系统：Windows10+/Windows-server-2015+/Linux/macOS-10+

## 🚀 安装步骤
1. 克隆本仓库
```bash
git clone https://github.com/wangdexinya/mycraft-python.git
```

2.安装第三方拓展包（使用阿里云镜像加速）
```bash
pip install pygame ursina perlin_noise psutil -i https://mirrors.aliyun.com/pypi/simple/
```

3.运行项目
```python
cd python-mycraft/
python run
```

## 📁 项目结构
```files
python-mycraft/
├── mycraft/          # 核心代码目录
│   ├── assets/      # 资源文件夹
│   ├── game_core.py       # 游戏主逻辑
│   ├── save_system.py      # 世界生成与存档
│   ├── main_menu.py     # 主菜单
│   ├── pause_menu.py     # 游戏内暂停菜单
│   └── run     # 启动文件
└── README.md         # 项目说明文档
```

## 🎮 基本操作
- W/A/S/D：前后左右移动
- 空格：跳跃
- 鼠标：视角控制
- 左键：破坏方块
- 右键：放置方块
- ESC 或者Q ：暂停游戏 / 返回主菜单
- 1~4键：切换手持方块

## 前景规划
目前已经做好的:

- [x] 地图生成
- [x] 移动、跳跃
- [x] 放置、挖掘方块
- [x] 主菜单
- [x] 存档、加载功能
- [x] 完善
- [x] 添加彩蛋
- [x] 适配窗口缩放


下面是一些...呃......生存....测试的.....畅..想 `~o~)/`：

- [ ] 生命值、体力值
- [ ] 建立自己的社区
- [ ] 添加mod
- [ ] 死亡(这个阔以)
- [ ] 添加物品栏
- [ ] 添加合成系统
- [ ] 增加更多物品，如水、岩浆
- [ ] 添加粒子效果!(蒸的阔以吗)
- [ ] 转为.exe文件(尝试过，失败了[恼])
- [ ] 将项目更名为 "Minecraft"(不可能)

## 🤝 贡献名单
- wangdexinya(eggy_aurora)

## 📄 许可证
- 本项目采用 MIT 许可证 - 详见 LICENSE 文件。

## 👨‍💻 作者
wangdexinya(eggy_aurora)
- 邮箱：1636647891@qq.com
- GitHub：https://github.com/wangdexinya
- 哔哩哔哩：https://space.bilibili.com/3461582916946644
- 第一期宣传视频：[第一期宣传视频](https://www.bilibili.com/video/BV1UJFDzrEeY)

## 开源目标(暂未达成开源目标)
- 前提：第一期宣传视频点赞破5000
- 合作制作!
- 提供建议
- (纯粹就是想开源)
- 制造伟大的社区(要有开源精神)!
