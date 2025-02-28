# B4B-Assistant

[English](README_EN.md) | 简体中文

B4B Assistant 是一个 BACK 4 BLOOD(喋血复仇) 游戏的卡组管理工具。它可以帮助玩家方便地导入、导出和管理游戏卡组。

## 主要功能
注意：目前暂不支持英文

* 📋 剪贴板导入卡组
* 📷 OCR扫描导入卡组
* 💾 保存和管理自定义卡组
* 🎮 一键导入卡组到游戏
* 📤 分享卡组功能（支持导出分享文本）

## 使用说明

1. 将游戏设置为无边框窗口模式
2. 在游戏中打开卡组界面
3. 点击软件中的"导入游戏"按钮
4. 等待OCR识别完成（可能需要几秒钟时间）

注意：OCR识别可能需要一定时间，请耐心等待。


## 编译说明

如果你想自行编译该项目：

1. 运行 `deploy.py` 文件，将自动使用 nuitka 进行编译
2. 如需生成本地化文件，运行 `translate.py` 导出 ts 文件

对于开发者：代码中需要本地化的字符串请使用 `self.tr()`。

## 致谢

本项目使用了以下开源项目：

* [PyQt-Fluent-Widgets](https://github.com/zhiyiYo/PyQt-Fluent-Widgets) - 美观的 Fluent Design 风格 PyQt 组件
* [RapidOCR](https://github.com/RapidAI/RapidOCR) - 高效的 OCR 识别引擎

## 软件截图
![alt text](AppData/images/image.png)
![alt text](AppData/images/image-1.png)

## 版本更新日志

### v0.1.0 (2025-01)
* ✨ 首次发布
* 🎮 支持剪贴板导入卡组
* 📷 支持OCR扫描导入卡组
* 💾 支持保存和管理自定义卡组
* 🎮 支持一键导入卡组到游戏
* 📤 支持分享卡组功能（支持导出分享文本）