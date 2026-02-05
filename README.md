# AquaType 🌊

> **Think in Chinese, Communicate in English**

AquaType 帮助你在日常交流中逐步养成英语表达的习惯。输入中文想法，即时转换为地道英文，让语言学习自然融入工作与生活。

## 🎯 设计理念

- **无缝融入日常** - 在任何应用中随时唤起，不打断工作流
- **即时反馈** - 看到自己的想法如何用英文表达，潜移默化学习
- **降低门槛** - 先用母语思考，再看英文结果，减少表达焦虑
- **养成习惯** - 坚持使用，逐渐培养英语思维

## ✨ 功能特点

- 💧 **水滴透明界面** - 清透玻璃质感的悬浮窗口
- ⌨️ **快捷输入** - 输入中文，按 Enter 即可翻译
- 📋 **自动粘贴** - 翻译完成后自动粘贴到目标窗口
- 📌 **窗口置顶** - 可切换置顶/取消置顶
- 🔧 **托盘常驻** - 关闭窗口最小化到托盘，双击恢复

## 📦 安装

```bash
pip install -r requirements.txt
```

**依赖项：**
- PyQt5
- openai
- pynput
- pyperclip
- keyboard

## ⚙️ 配置

编辑 `config.json` 文件：

```json
{
  "api_base": "https://your-api-endpoint.com/v1",
  "api_key": "your-api-key-here",
  "model": "gpt-3.5-turbo"
}
```

## 🚀 使用方法

1. **启动程序**
   ```bash
   python main.py
   ```

2. **在悬浮窗中输入中文**

3. **按 Enter 或点击"翻译"按钮**
   - 自动翻译成英文
   - 自动粘贴到之前的窗口

4. **快捷键**
   - `Enter` - 翻译并粘贴
   - `Esc` - 隐藏窗口
   - `📌` - 切换置顶

5. **托盘操作**
   - 双击托盘图标 - 显示窗口
   - 右键托盘 - 退出程序

## 📁 项目结构

```
├── main.py              # 程序入口 + UI
├── translator.py        # OpenAI API 翻译
├── config.json          # 配置文件
└── requirements.txt     # 依赖清单
```

## 🎨 界面预览

- 1/3 屏幕宽度的水滴透明悬浮条
- 位于屏幕顶部居中
- 清透的蓝白配色

## ⚠️ 注意事项

- 需要安装虚拟环境中的依赖：`pip install -r requirements.txt`
- 确保 `config.json` 中的 API 配置正确
- 某些安全软件可能拦截键盘操作，请添加信任

## 📄 License

MIT License
