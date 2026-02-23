# OpenClaw 共享知识库

这是 OpenClaw 的外挂知识库文件夹，支持 iCloud 同步 + Git 双备份。

## ✅ 已配置功能

### 1. iCloud 同步（实时）
- 文件夹位于 iCloud Drive
- 在 iPhone/iPad/其他 Mac 上自动同步
- 编辑后立即同步到所有设备

### 2. Git 版本控制
- 已初始化 Git 仓库
- 支持版本历史和回滚
- 可推送到 GitHub/GitLab 远程备份

## 📁 目录结构

```
OpenClaw-Knowledge/
├── ai/              # AI/机器学习相关资料
├── daily/           # 日常笔记、想法
├── projects/        # 项目文档
├── resources/       # 资源收藏、链接
├── tech/            # 技术笔记
├── vfx/             # 特效相关资料
└── README.md        # 本文件
```

## 💻 从其他设备访问

### Mac/iPad/iPhone（iCloud）
1. 打开「文件」App
2. 进入 iCloud Drive → OpenClaw-Knowledge
3. 直接编辑文件

### 任何设备（Git）
```bash
# 克隆到本地
git clone <仓库地址>

# 编辑后提交
git add .
git commit -m "更新笔记"
git push
```

## 🔗 GitHub 远程仓库

**已配置远程仓库：** https://github.com/yangdissy/openclaw-knowledge

### 从其他设备克隆
```bash
git clone https://github.com/yangdissy/openclaw-knowledge.git
```

### 更新到最新
```bash
cd ~/OpenClaw-Knowledge
git pull
```

### 推送本地更改
```bash
cd ~/OpenClaw-Knowledge
git add .
git commit -m "更新笔记"
git push
```

## 📝 使用建议

1. **日常记录**：用 iCloud 在各设备间快速同步
2. **重要版本**：用 Git 提交，保留历史
3. **远程备份**：推送到 GitHub，任何地方可访问

## 🚀 快速开始

在任意设备添加文件到对应目录，OpenClaw 会自动学习！

支持的格式：
- `.md` - Markdown（推荐）
- `.txt` - 纯文本
- 代码文件 `.py`, `.js` 等

---
*创建于 2026-02-23 | 同步方式: iCloud + Git*
