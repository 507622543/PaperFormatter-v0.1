# PaperFormatter

学术论文格式化工具 - 一键排版，支持多种学术规范。

## 功能特性

- 自动识别论文结构（标题、正文、图表标题、参考文献等）
- 支持多种排版规范（学术标准、IEEE、CNKI 等）
- 自动生成目录
- 图表编号自动修正
- 参考文献重排序
- 支持 AI 辅助识别（可选，需要 Ollama）

## 下载

前往 [Releases 页面](https://github.com/507622543/PaperFormatter-v0.1/releases) 下载对应平台的版本：

| 平台 | 文件 | 架构 |
|------|------|------|
| Windows | [`PaperFormatter-Windows.exe`](https://github.com/507622543/PaperFormatter-v0.1/releases/latest/download/PaperFormatter-Windows.exe) | x86_64 |
| Linux | [`PaperFormatter-Linux`](https://github.com/507622543/PaperFormatter-v0.1/releases/latest/download/PaperFormatter-Linux) | x86_64 |
| macOS | [`PaperFormatter-macOS`](https://github.com/507622543/PaperFormatter-v0.1/releases/latest/download/PaperFormatter-macOS) | ARM64 (Apple Silicon) |

## 使用方法

### Windows

双击 `PaperFormatter-Windows.exe` 运行。

### Linux

```bash
chmod +x PaperFormatter-Linux
./PaperFormatter-Linux
```

### macOS

```bash
chmod +x PaperFormatter-macOS
./PaperFormatter-macOS
```

> macOS 首次运行可能需要在「系统设置 → 隐私与安全性」中允许运行。

## 使用说明

1. 启动程序后，点击「选择文件」加载 .docx 论文文件
2. 选择排版规范（如「学术标准」「IEEE Transactions」等）
3. 点击「开始格式化」
4. 格式化完成后自动保存为新文件

## 支持的规范

- 学术标准（通用）
- IEEE Transactions
- IEEE Conference
- CNKI 学位论文
- 南京理工大学模板
- 西安科技大学模板

## 技术栈

- Python 3.12 + Tkinter
- python-docx + lxml
- Nuitka 编译为原生可执行文件
