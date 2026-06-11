# SmartRun (快速启动)

> Windows 桌面快捷启动工具 — 快速启动程序、打开网址、管理分组、定时提醒、基金查询、阅读助手、FAQ 问答

---

## 系统要求

- **操作系统**：Windows 10 / Windows 11
- **运行时**：[.NET 10.0 Desktop Runtime](https://dotnet.microsoft.com/zh-cn/download/dotnet/10.0)（x64）
- 首次运行前请安装 .NET 10.0 运行时，否则双击 `smartrun.exe` 无反应

## 快速开始

1. 安装 [.NET 10.0 Desktop Runtime](https://dotnet.microsoft.com/zh-cn/download/dotnet/10.0)
2. 双击 `smartrun.exe` 启动
3. 默认热键：`Alt + A` 切换窗口显示/隐藏
4. 首次启动会创建示例数据，方便体验

## 功能一览

| 功能 | 说明 |
|------|------|
| 🚀 快捷启动 | 支持 exe、url、lnk 拖放管理，分组分类 |
| 🔔 定时提醒 | 支持每天、每周、每月、每年、工作日、节假日提醒 |
| 📈 基金查询 | 添加基金代码，实时查看净值估算 |
| 📖 阅读助手 | 分段落阅读文本，记录阅读进度 |
| ❓ FAQ 问答 | 录入常用问答/代码片段，快速检索复制 |
| 📸 截图 | 截图并保存到本地 |
| ⌨️ 全局热键 | 自定义快捷键 |

## 键盘快捷键

| 快捷键 | 功能 |
|--------|------|
| `Alt + A` | 切换窗口显示/隐藏 |
| `Alt + X` | 截图 |
| `Alt + T` | 切换窗口置顶 |

可在「设置」中自定义热键。

## 数据存储

所有数据保存在 `Data/` 目录下：

```
Data/
├── shortcuts/shortcuts.xml     # 快捷方式分组
├── faq/faq.csv                 # FAQ 问答库
├── faq/codes.csv               # 常用代码片段
├── funds/fund.xml              # 基金代码
├── reminders/reminder.xml      # 定时提醒
├── reading/book.json           # 阅读书单
├── reading/                    # 阅读文本文件
└── screenshot/                 # 截图保存目录
```

数据均为纯文本格式（XML/CSV/JSON），可直接编辑。**首次启动时如数据文件不存在，会自动创建示例数据。**

## 提示

- 以管理员身份运行时，拖放功能可能受限，建议普通用户权限运行
- 如需开机自启动，首次以管理员身份运行一次即可
- 所有本地数据不会上传，请放心使用

---

**SmartRun v3.0** · [项目主页](https://github.com/bigsinger/smartrun_wpf)
