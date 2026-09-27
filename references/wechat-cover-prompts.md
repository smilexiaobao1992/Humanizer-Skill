# 公众号封面图设计标准与 Prompt 提示词工程规范

微信公众号封面的视觉冲击力直接决定了文章的打开率（CTR）。本指南规定了爆款历史人性类公众号封面的设计原则、尺寸布局规范与 AI 绘图 Prompt 模板。

---

## 1. 尺寸与版面安全区法则

- **头条大图官方比例**：**2.35:1**（推荐像素尺寸：`900 x 383` 或 `1080 x 460`）。
- **小图/信息流裁切安全区**：
  微信在部分好友会话、历史列表或卡片流中，会将 2.35:1 的图片**居中裁剪为 1:1 正方形**。
  - **核心视觉主体（人物眼睛、主要面部特写、核心戏剧冲突点）必须锁定在水平与垂直居中的 50% 核心区域内**。
  - 两侧左右 25% 区域仅放置环境虚化背景、光影氛围或次要元素。

---

## 2. 视觉美学风格推荐

历史人性与帝王权谋类爆款文章，严禁使用廉价网剧截图或劣质扁平卡通。建议采用以下三种高调性风格之一：

1. **电影暗黑写实（Cinematic Noir & Historical Realism）**：
   - 强烈明暗对比（Chiaroscuro）、伦勃朗光、雨夜、烛光、阴影中半明半暗的脸孔，极度深沉压抑的人性悬疑感。
2. **新中式重彩水墨厚涂（Neo-Chinese Impasto Oil & Ink Wash）**：
   - 兼具古典东方水墨的意境流淌与西方古典油画厚重有力的笔触，充满刀锋般的历史沧桑。
3. **戏剧性舞台大特写（Theatrical Close-Up & Tense Lighting）**：
   - 聚焦人物的面部肌肉抽动、冷酷眼神、手握刀剑或颤抖的酒杯等关键道具。

---

## 3. 爆款 Prompt 万能生成公式

```text
[主体人物与核心冲突动作] + [表情/微神态细节与情绪张力] + [服饰/道具考究] + [环境场景与光影] + [艺术媒介与画风] + [色彩基调与质感] + [构图比例与参数]
```

### 标准示例（以《曹操偏爱人妻/宛城之夜》为例）：

- **英文 Prompt（Midjourney / SD / DALL-E）**：
  > `Cinematic wide shot, historical Chinese drama masterpiece. In a dimly lit Han dynasty military tent illuminated by flickering warm candlelight, Cao Cao, a middle-aged warlord with cold, calculating, arrogant eyes and a dark chaotic beard in heavy dark iron armor, looking down from the shadows. Beside him sits a beautiful, dignified noble widow in exquisite Hanfu silk, her face half-shadowed, complex expression of melancholy, grief, and silent pride. Tension in the air, intense psychological drama, Rembrandt lighting, deep shadows, cinematic noir, 8k resolution, photorealistic film grain, moody color grading --ar 16:9`

- **中文视觉拆解说明**：
  > 画面定格在宛城中军大帐。昏黄烛光摇曳，曹操半边脸没入黑暗，眼神里满是吞噬一切的野心与算计；另一侧是华服少妇邹氏，面容清丽却眼神空洞凄凉。光影割裂两人，刀剑暗光与薄纱交错，营造出危险、暧昧又充满血腥预兆的人性博弈场面。
