# 🐵 MonkeyType AutoTyper Bot

![Version](https://img.shields.io/badge/version-2.2-green.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Tampermonkey](https://img.shields.io/badge/Tampermonkey-Script-orange.svg)

一个为 MonkeyType 打字练习网站设计的智能自动打字机器人脚本。模拟人类打字行为，支持可配置的打字速度、准确率和错误模拟。

## ✨ 功能特点

### 🎯 核心功能
- **智能打字模拟**：自动检测并输入下一个字符
- **速度控制**：两种模式选择（基础WPM/高级延迟）
- **错误模拟**：真实的人类打字错误（跳过、重复、相邻键错误）
- **快捷键控制**：一键开始/停止（默认：ArrowRight）

### ⚙️ 参数配置
- **打字速度**：10-150 WPM 或自定义延迟范围
- **准确率**：50%-100% 可调节
- **单词暂停**：单词间额外延迟设置
- **模式切换**：基础模式（简单）与高级模式（精细控制）

### 🎨 用户界面
- 现代化悬浮控制面板
- 实时状态显示
- 设置自动保存
- 一键重置默认设置

## 📦 安装方法

### 方法一：直接安装（推荐）
1. 确保已安装用户脚本管理器：
   - [Tampermonkey](https://www.tampermonkey.net/)（Chrome/Firefox/Edge）
   - [Violentmonkey](https://violentmonkey.github.io/)
   - [Greasemonkey](https://www.greasespot.net/)（仅Firefox）

2. 点击安装链接：[MonkeyType AutoTyper Bot.user.js](#)

### 方法二：手动安装
1. 复制 [脚本代码](monkeytype-autotyper-bot.js)
2. 打开用户脚本管理器 → 添加新脚本
3. 粘贴代码并保存

## 🚀 使用方法

### 基本操作
1. 访问 [MonkeyType](https://monkeytype.com/)
2. 页面右侧会出现控制面板
3. 调整所需参数（速度、准确率等）
4. 按 **右箭头键 (→)** 开始/停止自动打字
