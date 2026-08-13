# makise-character-archive · 角色设定集

> A personal collection of popular & interesting character settings, curated by makise according to his tastes.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Last Updated](https://img.shields.io/badge/last%20updated-2026--08--13-blue.svg)

---

## 简介 / Introduction

**makise-character-archive** 是 makise 按个人兴趣收集整理的**角色设定集**——专门归档那些热门、有趣、值得扮演的角色。

每一份设定都遵循统一的 **「文件更新记录」** 规范，便于跨会话追踪版本、知识时间与修订历史；所有文档可直接作为本地 AI 角色扮演的设定底稿。

*makise-character-archive is a personal collection of popular and interesting character settings, gathered by makise according to his own tastes. Every document follows a standardized "File Update Log" so version, knowledge date and revision history stay traceable across sessions.*

---

## 目录结构 / Structure

```
makise-character-archive/
├─ README.md
├─ Wuthering Waves/          # 鸣潮
│   └─ 守岸人 (The Shorekeeper) — 完整角色设定文档 (v3.5).md
├─ Genshin Impact/           # 原神
├─ Honkai Star Rail/         # 崩坏：星穹铁道
├─ Arknights/                # 明日方舟
├─ Other Worlds/             # 非游戏 IP / 原创世界观
└─ Templates/                # 角色设定模板（复制即用的标准骨架）
    └─ 角色设定模板.md
```

> 各游戏目录当前为占位结构，待设定文档归入后填充。

---

## 文档规范 / Document Convention

每份设定文档建议包含以下章节：

1. 核心指令与扮演基调
2. 基础档案（名称 / 属性 / 武器 / 阵营 / 核心意象 / 专属誓言）
3. 世界观背景
4. 完整背景故事（含剧情节点与资料来源）
5. 性格与情感层次
6. 外貌
7. 语言风格
8. 战斗设定（如有）
9. 与用户的关系定位
10. 特殊交互机制
11. 红线（禁止项）
12. 版本适配备注
13. 示例对话

文末**必须追加**「文件更新记录」区块（模板见 `Templates/角色设定模板.md`），字段包括：

| 字段 | 说明 |
| --- | --- |
| 当前知识时间 | 设定整理时的日期（GMT+8） |
| 所属作品 / 世界观 | 游戏或原作名称 |
| 作品版本 | 对应的游戏 / 原作版本号 |
| 文件版本 | 文档自身版本（建议与作品版本对齐） |
| 设定来源 | 官方文本 / Wiki / 社区考据 等 |
| 维护者 | makise（整理人） |
| 最后修订 | 最近修改日期 |

并附 **修改记录（倒序）** 与 **核心定位速查**。

- **图片素材（鼓励携带）**：图片存放于设定文档同级的 `images/` 目录，用相对路径 `images/xxx.png` 引用，便于管理与清晰整理；命名建议 `<角色>-<用途>.<ext>`。

---

## 使用 / Usage

- 直接阅读各 `.md` 文件。
- 设定文档用于本地 AI 角色扮演，请严格遵循各文件「红线（禁止项）」约束回复风格。
- 新建角色请复制 `Templates/角色设定模板.md`，填写后移入对应游戏 / 世界观目录。

---

## 贡献 / Contributing

本项目为个人档案库，目前以单人维护为主。若你希望补充某一角色的设定：

1. Fork / 克隆本仓库
2. 在对应目录新建或更新 `.md` 文档
3. 补全「文件更新记录」
4. 提交 Pull Request（或告知维护者合并）

---

## 声明 / Disclaimer

- 本项目所有设定文档均为**非官方的二创 / 扮演用资料**，仅供个人学习与角色扮演使用，与各大游戏官方无关。
- 角色版权归各自作品所有方；如涉及侵权请联系移除。
- 文档中标注「非官方实装 / 社区推测」的内容不代表游戏正式设定。

---

## License

MIT License

Copyright (c) 2026 makise

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
