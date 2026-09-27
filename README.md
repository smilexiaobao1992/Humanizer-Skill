# Humanizer-Skill

> **微信公众号深度爆款文案去 AI 味、过 AIGC 检测与电影级封面生成工程 (WeChat Article Humanizer V2.0)**

[![Humanizer-zh](https://img.shields.io/badge/Powered%20By-Humanizer--zh%2031%20Rules-blue.svg)](https://github.com/op7418/Humanizer-zh)
[![Skill Spec](https://img.shields.io/badge/Agent-Skill%20Spec%20V2.0-brightgreen.svg)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()

---

## 📖 项目简介 (Overview)

**Humanizer-Skill** 是一套专为 **AI 智能体（Google Antigravity / Claude Code / Cursor / Roo Code / Windsurf 等）** 打造的高质量微信公众号深度内容生成与去 AI 味重构规范。

本项目深度融合了 **[Humanizer-zh](https://github.com/op7418/Humanizer-zh) 语言学级的 31 项去 AI 痕迹显微镜诊断标准** 与 **移动端高完读率深度叙事机制**。

核心目标是：**在严守事实保真与篇幅自律的前提下，彻底粉碎机械 AI 感、毒鸡汤断言与教条套话，制造高突发度（Burstiness）与高困惑度（Perplexity）以绕过腾讯朱雀等 AIGC 检测器，并生成极具视觉张力的 2.35:1 电影级头条封面方案。**

---

## 🎯 传统 AI 写作的四大“死穴”与解决方案

| 传统 AI 写作死穴 | 读者的真实感受 | Humanizer-Skill 终极解法 |
| :--- | :--- | :--- |
| **【F30 套话开篇】**<br>“在当今快节奏的社会中……”、“在华夏历史的长河中……” | 一眼看出是 AI 生成的命题作文，3 秒划走 | **电影分镜冷开场**：直接将特写镜头推到极端困境、生理冷汗、命悬一线的第一现场。 |
| **【F26 极端毒鸡汤断言】**<br>“嗓门最大的人最早被淘汰”、“低头示弱拿到了全部” | 武断虚假、营销号既视感，读者产生本能抗拒 | **成人利益与心理博弈**：拆解防御本能、权力结构与长远得失，摒弃一棍子打死。 |
| **【F04/F17 僵硬 PPT 提纲】**<br>通篇充斥 `### 1. 2. 3.`，碎化情绪 | 像在读工作汇报或学生答辩，阅读心流全碎 | **剧情幕次自然推进**：将大纲骨架熔铸进波澜起伏的历史现场与真实对话中。 |
| **【AIGC 检测秒封】**<br>句式等长工整、词汇平滑预测概率高 | 被腾讯朱雀或平台算法识别为“低质/AI伪原创” | **长短句剧烈离散方差**：极短单字句撞击文白典故，极致拉大突发度与困惑度。 |

---

## 🚀 核心工作流 (Workflow)

```text
[原始文案 / 小红书笔记 / 选题大纲]
       ↓
【Step 1】保真边界与篇幅锚定（确定字数区间，不无脑膨胀，严守史实与逻辑）
       ↓
【Step 2】31项语言学诊断手术（查禁词、化解“进行+动词”、碎长定语、除假对比与假破折号）
       ↓
【Step 3】公众号深度叙事重构（电影切片开场 + 利益人性暗牌 + 生理痛感注血肉）
       ↓
【Step 4】算法过检调优（高突发度长短句差 + 文白口语混搭 + 破坏大模型连贯预测）
       ↓
【Step 5】爆款包装交付（2.35:1 官方宽屏封面方案 + 3组高点击标题矩阵 + 评论区情绪留白）
```

---

## 📦 仓库架构 (Repository Structure)

```text
Humanizer-Skill/
├── README.md                                    # 规范总览与使用指南（本文档）
├── SKILL.md                                     # 智能体核心指令定义规范（Agent System Prompt）
├── references/                                  # 核心诊断库与工具对照表
│   ├── humanizer-zh-31-rules.md                 # 31 项去 AI 味语言学病理诊断速查表
│   ├── ai-smell-banned-words.md                 # AI 味违禁词库与过检对照表
│   └── wechat-cover-prompts.md                  # 2.35:1 宽屏封面设计与 Midjourney Prompt 万能库
└── examples/                                    # 实战案例与范文库
    ├── 01_公众号去AI味与爆款改写规范指南.md        # 完整宏观方法论与媒介降维拆解
    ├── 02_实战范文_曹操偏爱人妻深度长文.md         # 小红书大纲重构为 2,200 字深度爆款范文
    └── 03_实战范文_汉武帝晚年血色深渊特稿.md       # 3,700 字重大历史宫闱清洗史诗特稿范文
```

---

## 🔍 Humanizer-zh 31 项去 AI 痕迹显微镜速查

本项目完整继承了 [Humanizer-zh](https://github.com/op7418/Humanizer-zh) 的 31 项语言学诊断体系，划分为 6 大病理模块：

1. **中文本土化 6 大顽疾（必杀）**：
   * `F01` 滥用“的”字连环长定语
   * `F02` 机械化“进行+动词”机器腔（“进行全面优化” ➔ “全面优化了”）
   * `F03` 滥用被动语态（“尊严被彻底剥夺” ➔ “生生撕碎了他的尊严”）
   * `F08` 虚浮四字成语与排比堆砌（“波澜壮阔、荡气回肠”）
   * `F30` 套话开篇（“在……背景下 / 在当今快节奏时代”）
   * `F31` 套话强行升华收尾（“总而言之、让我们拭目以待”）
2. **结构与信息流套路**：
   * `F04` 结构完全对称（等长三段论）
   * `F05` 过渡词泛滥（“首先、此外、总的来说”）
   * `F17` PPT 式生硬骨架编号
3. **句法与词汇污染**：
   * `F06` 机械双动词串联
   * `F09` 大词空词拔高（“赋能、闭环、底层逻辑、抓手”）
   * `F12` 幽灵主语（缺失主谓导致长句失焦）
4. **语气与虚假对比**：
   * `F24` 假对比（“不是……而是……”）
   * `F25` 假设问与假对立（“世人总以为……可其实……”）
   * `F26` 极端绝对化判断（“嗓门最大的往往最早淘汰”、“低头示弱拿到了全部”）
   * `F28` 虚假升华与鸡汤说教
5. **认知与概念降噪**：
   * `F23` 标志性 AI 营销短语（“一语道破了天地间最反直觉的制胜密码”）
   * `F27` 宇宙级夸大词汇（“终极秘密、颠覆千古”）
6. **标点与排版防伪**：
   * `D18` 滥用万能破折号（频繁打 `——` 假停顿）
   * `D19` 满屏黑体字加粗污染（一篇文章仅限 2~3 处核心金句加粗）

*(更详尽的诊断标准与修改对照，请查阅 [`references/humanizer-zh-31-rules.md`](./references/humanizer-zh-31-rules.md))*

---

## 🎨 官方 2.35:1 宽屏单封面工程

微信公众号头条大图在移动端呈现具有严苛的裁切机制：

```text
+-------------------------------------------------------------+
|                                                             |
|                 2.35:1 微信头条宽屏展示区                     |
|                                                             |
|           +-------------------------------------+           |
|           |                                     |           |
|           |         核心主体 50% 保护区           |           |
|           |      (被裁剪为 1:1 正方形时保留)       |           |
|           |                                     |           |
|           +-------------------------------------+           |
|                                                             |
+-------------------------------------------------------------+
```

* **官方推荐比例**：`2.35:1`（标准像素：`1080 x 460 px`）；
* **中心 50% 安全保护区**：核心人物面部与视觉焦点严格锁定在画面正中央，防止在微信聊天列表、转发卡片被系统自动截为 `1:1` 方块时发生“断头”惨剧；
* **视觉美学**：优先输出电影暗黑写实（Cinematic Noir）与新中式青绿/重彩水墨（Neo-Chinese Impasto），配备全套中英 Midjourney / SD 提示词。

---

## 💻 快速安装与使用指南 (Installation)

### 1. 在 Google Antigravity (AGY) 中使用
将本项目克隆或放置到当前工作区的 `.agents/skills/` 目录下即可直接生效：
```bash
git clone git@github.com:smilexiaobao1992/Humanizer-Skill.git .agents/skills/wechat-article-humanizer
```

### 2. 在 Claude Code / Claude Desktop 中使用
在你的系统提示词或 `CLAUDE.md` 中引用本项目：
```markdown
Read and strictly adhere to the guidelines in [SKILL.md](./SKILL.md) and [references/humanizer-zh-31-rules.md](./references/humanizer-zh-31-rules.md) for all Chinese writing and article rewrites.
```

### 3. 在 Cursor / Roo Code / Windsurf 中使用
直接将 `SKILL.md` 添加为自定义 Rule 或 System Instructions，即可让 AI 编写出兼具文学痛感与零 AI 痕迹的深度好文。

---

## 📄 开源协议与致谢 (License & Acknowledgement)

* 本项目基于 **[MIT License](./LICENSE)** 开源。
* 特别致谢 **[Humanizer-zh](https://github.com/op7418/Humanizer-zh)** 创立的中文语言学去 AI 味显微镜体系！
