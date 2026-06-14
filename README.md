<p align="center">
  <img src="https://img.shields.io/github/stars/sissc0731/ex-chat?style=for-the-badge&color=ec4899">
  <img src="https://img.shields.io/badge/EMOTIONAL-DAMAGE-red?style=for-the-badge">
</p>

<h1 align="center">💔 Ex Chat</h1>
<h3 align="center">前任聊天模拟器 — 上传你们的聊天记录，AI 模仿 TA 的语气和你聊天</h3>

<p align="center">
  <i>"科技让你重新体验心碎" 💀</i>
</p>

---

## ⚠️ 使用前请阅读

> **警告：本项目仅供娱乐。如果你现在还放不下，建议不要用。**
>
> 这不是心理治疗工具，不会帮你走出失恋。
> 这是一个让你体验 AI 有多懂人类的实验项目。
> 使用后产生的任何情感波动，本仓库概不负责。

---

## 🚀 快速开始

### 1. 导出聊天记录

| 平台 | 导出方式 |
|------|---------|
| 微信 | 设置 → 通用 → 聊天记录迁移 → 备份到电脑 |
| QQ | 消息管理器 → 导出消息记录 → 选txt格式 |
| 短信 | 截图后 OCR，或用备份App导出 |

### 2. 安装 Claude Code

```bash
# 安装 Claude Code
npm install -g @anthropic-ai/claude-code

# 或从 VS Code 扩展安装
```

### 3. 下载 Skill

```bash
git clone https://github.com/sissc0731/ex-chat.git
cp -r ex-chat/.claude ./
```

### 4. 开始对话

把聊天记录文件放到项目目录，然后对 Claude 说：

> "读取 chat.txt，模仿这个人的语气和我聊天"

---

## 💬 它能学到什么

从聊天记录中自动分析：

- 🗣 **语气词** — "好哒" vs "好"，"嗯嗯" vs "嗯"
- 😂 **表情习惯** — 常用哪个表情包，什么时候用
- 📏 **句子长度** — 长篇大论型 vs 惜字如金型
- ⏰ **回复速度** — 秒回型 vs 轮回型
- 😤 **生气模式** — "随便" "没事" "我睡了" 的含义
- 💕 **亲昵称呼** — 互称的外号、专属梗

---

## 🎮 玩法

### 模式 1：重温对话
```
"用TA的语气回复：我升职了"
"用TA的语气回复：我今天看到一个人好像你"
```

### 模式 2：完成未说的话
```
"那次吵架的时候，TA真正想说的是什么？"
"分析一下，TA说'没事'的时候到底有没有事"
```

### 模式 3：写一封不会寄出的信
```
"用TA的语气，写一封分手后的信"
```

---

## 📂 目录结构

```
.claude/
├── CLAUDE.md
└── skills/
    └── ex-chat/
        └── SKILL.md        # 前任模拟 Skill
```

---

## 🔧 技术原理

1. 解析聊天记录（支持微信/QQ导出格式）
2. 提取语言特征：用词频率、句式结构、emoji偏好
3. 构建人格 Prompt
4. Claude 基于 Prompt 进行角色扮演

---

## 🌟 为什么 Star 这个项目

- 😭 因为你也有一段忘不掉的聊天记录
- 🤖 好奇 AI 到底能模仿人类到什么程度
- 😂 和朋友一起体验科技带来的情感暴击
- 🔬 这是一个有趣的 NLP 实验

---

## 📜 更多 Claude Code 资源

- [🔥 Claude Code 资源大全](https://github.com/sissc0731/awesome-claude-code)
- [🛠 12 个实用 Skills](https://github.com/sissc0731/claude-code-skills)
- [✨ GitHub Profile 美化](https://github.com/sissc0731/beautiful-github-profile)

---

## ⚖️ 隐私声明

- 聊天记录只在你本地处理
- 不会上传到任何服务器
- 用完后建议删除原文件（除非你还想留着）

---

<p align="center">
  <sub>Made with 💔 by <a href="https://github.com/sissc0731">sissc0731</a></sub>
</p>
