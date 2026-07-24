# ETNA Labs — Brand Guide

> 依据：`LOGOS/Etna Brand VISUAL IDENTITY 2026 Jul 最新/`
> 源文件：`ETNA Visual identity-B.pdf`（15 页）、`AI矢量/`、`png/`、`etna type/`
> 版本：2026 年 7 月　｜　本文档整理于 2026-07-10

本 guide 中标注 **[源文件]** 的内容直接来自设计稿；标注 **[建议]** 的内容是为落地补充的规范，源文件未定义，需设计确认。

---

## 1. 品牌标志 Logo

### 1.1 标志构成

标志由字标 ETNA、副标 Labs、以及可选 tagline 三部分构成。

字母 **A** 被替换为埃特纳火山（Mount Etna）的山形：山体轮廓加一个实心的火山口/熔岩块。这是整套识别系统里唯一的图形元素，也是标志不可替换的核心——**任何情况下不得用普通字母 A 代替。**

### 1.2 三种标准组合（Lockup）

| 组合 | 说明 | 使用场景 |
|---|---|---|
| **竖版** | ETNA 上 / Labs 下 | 头像、印章、方形版位 |
| **横版** | ETNALabs 单行连写 | 网站页眉、邮件签名、文档页脚 |
| **横版 + tagline** | ETNALabs / Deep Conviction. Long View. | 名片、PPT 首页、封面 |

每种组合各有 **红 / 黑 / 白** 三个色版。

### 1.3 现有资产清单

`LOGOS/Etna Brand VISUAL IDENTITY 2026 Jul 最新/png/`

| 文件 | 组合 | 颜色 |
|---|---|---|
| `...-B-16.png` | 竖版 | 红 |
| `...-B-17.png` | 竖版 | 黑 |
| `...-B-18.png` | 竖版 | 白 |
| `...-B-19.png` | 横版 | 红 |
| `...-B-20.png` | 横版 | 黑 |
| `...-B-21.png` | 横版 | 白 |
| `...-B-25.png` | 横版 + tagline | 红 |
| `...-B-26.png` | 横版 + tagline | 黑 |
| `...-B-27.png` | 横版 + tagline | 白 |

> ✅ **三种组合均齐备红 / 黑 / 白三色版（共 9 个文件）。** 2026-07 版补齐了红色竖版（B-16）。
> ⛔ **字标 + tagline（ETNA + tagline、不含 Labs，源文件 B-22/23/24）不作为标准组合使用，已从本 guide 移除。** 磁盘上的这三个导出文件请勿再取用。
> 矢量源：`AI矢量/ETNA Visual identity-B转曲.ai`（已转曲，可直接交付印厂）。

---

## 2. 安全距离 Clear Space **[源文件]**

标志四周必须留出 **X** 的空白，X 内不得出现任何文字、图形、图片边缘或版心线。

```
        ┌─────── X ───────┐
        │  ┌───────────┐  │
        X  │   LOGO    │  X        X = 1/2 × lockup 高度
        │  └───────────┘  │
        └─────── X ───────┘
```

**X = 标志（含 tagline，如有）总高度的一半。**

这是从矢量文件里实测出来的——各标准组合实测该比值均为 0.50（例如 91/183.55、71.08/143.36、65/129.78）。设计稿的图示只标了 "X" 而没写死定义，所以这里给出的是实测结论。

计算示例：横版标志放置高度为 40px 时，四周留白 ≥ 20px。

---

## 3. 最小尺寸 Minimum Size **[源文件]**

**印刷：标志高度不小于 6mm。**（源文件在两个 lockup 的右侧竖直标注了 6mm）

**[建议]** 屏幕端最小高度 **24px**（6mm ≈ 22.7px @96dpi，向上取整到 24 便于栅格对齐）。低于此尺寸时，火山口的实心块会与 A 的山体轮廓糊在一起，失去辨识度。

---

## 4. 色彩 Color

### 4.1 主色板 **[源文件]**

源文件的色彩页仅定义了三个值：

| | HEX | RGB | 用途 |
|---|---|---|---|
| **Etna Red** | `#C43426` | `196, 52, 38` | 品牌主色。标志、强调、CTA |
| **Black** | `#000000` | `0, 0, 0` | 正文、单色印刷 |
| **White** | `#FFFFFF` | `255, 255, 255` | 反白、留白 |

> Etna Red 已用取色器在 `png/ETNA Visual identity-B-19.png` 上验证，实测 `rgba(196, 52, 38, 255)`，与 PDF 中标注的 `#C43426` 一致。

### 4.2 印刷转换

✅ **品牌方确认：以 `#C43426` 作为品牌红的唯一色值定义。** 不另行指定独立的 CMYK 与 Pantone 规格，印刷时由该 hex 换算。

换算结果取决于印厂的 ICC profile 与纸张——涂布纸与非涂布纸出来的数值并不相同。直接换算的参考值约为 **C0 M74 Y81 K23**，仅供估算，**交付时一律以 `#C43426` 为准**，由印厂按其色彩管理流程转换。首次上机仍建议打样确认实际观感。

### 4.3 中性色阶 **[建议]**

源文件没有定义中性色。以下是为网页与文档系统补充的建议，基于 Etna Red 的暖调偏移：

| Token | HEX | 用途 |
|---|---|---|
| `--ink` | `#191715` | 正文 |
| `--muted` | `#6D6860` | 次要文字 |
| `--line` | `#D8CEC2` | 分隔线、描边 |
| `--bg` | `#F4F0EA` | 页面底色 |
| `--paper` | `#FFFDF9` | 卡片、浮层 |

### 4.4 扩展应用色板 **[品牌应用规范｜2026-07-24 确认]**

本节是在源文件红 / 黑 / 白三色基础上，为研究报告、演示文稿、网站、图表与数字产品补充的应用色板。它不改变 §4.1 的 Logo 色彩规范：

- **Logo 仍然只能使用 Etna Red、Black 或 White 三种标准色版。**
- 扩展色不得进入 Logo，也不得替代 Etna Red 成为品牌识别色。
- 三个核心应用色并非三个并列主色；必须按下表保持清晰层级。

#### 4.4.1 核心应用色

| Token | 名称 | HEX | 层级与语义 | 典型用途 |
|---|---|---|---|---|
| `--etna-red` | **Etna Red** | `#C43426` | 品牌锚点；conviction、已确认的核心判断、最高优先级 | 品牌识别、关键结论、重点数字、CTA |
| `--deep-mineral` | **Deep Mineral** | `#596455` | 结构色；long view、稳定结构、长期趋势 | 市场、人才、生态、组织、长期研究 |
| `--mineral-blue` | **Mineral Blue** | `#65798A` | 信息色；analysis、技术、数据、系统 | AI、机器人、算力、模型、基础设施、对照数据 |

Etna Red 应始终是最少但最醒目的色彩。Deep Mineral 和 Mineral Blue 可以承担较大面积；同一页面通常只选择其中一种作为主要章节色，另一种只作为数据或信息辅助，避免三个颜色同时争夺视觉层级。

#### 4.4.2 临时与低优先级辅助色

| Token | 名称 | HEX | 语义 | 使用限制 |
|---|---|---|---|---|
| `--mineral-sage` | **Mineral Sage** | `#A7B1A2` | 暂定分类、观察中、低优先级背景 | 不用于核心结论、正文小字或 CTA |
| `--mist-blue` | **Mist Blue** | `#B5C0C7` | 临时数据、预测、尚未确认的信息 | 不用于品牌大色块、Logo 或主要标题 |

临时状态不能只依赖颜色表达，必须同时标注 `Draft`、`Preliminary`、`Forecast`、`Estimate`、`待验证` 等文字，或配合纹理 / 图标，保证信息无障碍与打印可读性。

#### 4.4.3 White 与 Warm Paper 的分工

**总原则：White 承载信息，Warm Paper 承载环境。**

| Token | 名称 | HEX | 语义 | 使用场景 |
|---|---|---|---|---|
| `--white` | **White** | `#FFFFFF` | 事实、正文、当前信息、确定性 | 数据图表、表格、正文阅读区、卡片、表单、正式文件 |
| `--bg` | **Warm Paper** | `#F4F0EA` | 背景、叙事、长期语境、编辑感 | 报告封面、章节过渡、研究栏目、引言、页面外围背景 |

当两者同时出现时，默认层级为：

```text
Warm Paper 页面 / 区域背景
└── White 内容卡片
    ├── 正文
    ├── 图表
    └── 数据表格
```

White 是高信息密度区域的默认底色。Warm Paper 不用于密集表格、小字号图表、表单、多层卡片内部或需要最高对比度的正文页面。白色与米色之间的切换必须对应明确的章节或内容层级，不得作为随机交替的装饰色。

白色内容卡片放在 Warm Paper 上时，优先使用细边框而不是明显阴影：

```css
background: #FFFFFF;
border: 1px solid #D8CEC2;
```

#### 4.4.4 建议比例

通用页面建议以中性色为主：

| 色彩角色 | 建议面积比例 |
|---|---:|
| White / Warm Paper 等中性背景 | 55–65% |
| Deep Mineral | 15–20% |
| Mineral Blue | 10–15% |
| Etna Red | 5–8% |
| Mineral Sage / Mist Blue | 合计不超过 5% |

不同载体可按信息密度调整 White 与 Warm Paper：

| 场景 | White | Warm Paper |
|---|---:|---:|
| 官网首页 | 60–70% | 20–30% |
| 研究文章 | 50–60% | 30–40% |
| 数据报告 | 70–80% | 10–20% |
| 品牌介绍册 | 40–50% | 40–50% |
| Dashboard / 工具 | 80–90% | 0–10% |

#### 4.4.5 标准设计 Token

```css
:root {
  /* Brand anchor */
  --etna-red: #C43426;

  /* Core application colors */
  --deep-mineral: #596455;
  --mineral-blue: #65798A;

  /* Provisional / low-priority information */
  --mineral-sage: #A7B1A2;
  --mist-blue: #B5C0C7;

  /* Neutral system */
  --ink: #191715;
  --muted: #6D6860;
  --line: #D8CEC2;
  --bg: #F4F0EA;
  --white: #FFFFFF;
  --paper: #FFFDF9;
}
```

给 Agent 或设计系统调用时，必须同时保留 token 的语义，不得仅提取 HEX 后任意互换用途。

### 4.5 ⚠️ 现有实现与规范不符

`Etna Website/app/globals.css:40` 当前定义为：

```css
--brand: #c45a48;   /* ← 与品牌红 #C43426 不一致 */
```

`#c45a48` 明显更浅更粉。网站、邮件签名生成器、名片工具都在用这个值。**需要统一改为 `#C43426`**，或者由设计明确 `#c45a48` 是否是有意为之的网页专用浅色版本（若是，应写进本文档的色板）。

建议的 token 定义：

```css
:root {
  --brand:      #C43426;  /* Etna Red — 品牌主色 */
  --brand-dark: #8F2620;  /* [建议] hover / pressed 态 */
  --brand-tint: #FBEDEB;  /* [建议] 浅底、选中态 */
}
```

---

## 5. 字体 Typography

`etna type/` 目录提供了两个字体文件。注意其中一个的文件名有误导性：

| 文件名 | 实际字体 | 角色 |
|---|---|---|
| `finSans-Regular-7 2.ttf` | **Josefin Sans Regular** v2.000 | 展示字体 |
| `Avenir Next.ttc` | **Avenir Next**（12 字重） | 西文正文 |

> `finSans-Regular-7 2.ttf` 的内部 name table 显示 family 为 `Josefin Sans`。文件名 "finSans" 会误导使用者去找一个并不存在的字体，建议重命名为 `JosefinSans-Regular.ttf`。
> Josefin Sans 是 Google Fonts 开源字体（OFL 授权），可自由用于网页与印刷。

### 5.1 层级 **[建议]**

| 层级 | 字体 | 说明 |
|---|---|---|
| **Logotype** | 定制字形 | ETNA 四个字母（含火山 A）为定制绘制，**不可用任何字体重新排版**，只能调用矢量文件 |
| **Display / tagline** | Josefin Sans Light–Regular | 几何无衬线，低 x-height，标志的同源气质。用于大标题、tagline |
| **西文正文 / UI** | Avenir Next Regular / Medium | 长文可读性优于 Josefin Sans |

Josefin Sans 的 x-height 很低、字怀开阔，**只适合大字号**。小于 16px 的正文一律用 Avenir Next。

### 5.2 Web fallback **[建议]**

```css
--font-display: "Josefin Sans", "Avenir Next", ui-sans-serif, sans-serif;
--font-sans:    "Avenir Next", Inter, ui-sans-serif, system-ui, sans-serif;
```

Avenir Next 是 **商业授权字体**（macOS 随系统附带，但网页嵌入需单独购买 webfont 授权）。网页端若无授权，用 Inter 作为替代，不要直接 `@font-face` 引用 `.ttc`。

---

## 6. Tagline

> **Deep Conviction. Long View.**

⚠️ **源文件中的排版是 `Deep Conviction.Long View.` —— 句号后缺一个空格。**

四个带 tagline 的 PNG（22/23/25/26）全部如此。这看起来像字距设置时的疏漏而非有意为之。请设计确认：如果是失误，需要修正矢量源并重新导出全部带 tagline 的资产。在修正前，**所有正文与网页中出现的 tagline 一律写作 `Deep Conviction. Long View.`（带空格）**。

---

## 7. 禁用规范 Don'ts **[建议]**

源文件未包含禁用页。以下为标准约束：

- ❌ 不得拉伸、压缩、倾斜标志——等比缩放
- ❌ 不得替换标志颜色（红/黑/白三色以外）
- ❌ 不得为标志添加描边、阴影、渐变、外发光
- ❌ 不得旋转标志
- ❌ 不得重排 lockup 内部元素的相对位置与大小
- ❌ 不得把火山 A 换成普通字母 A
- ❌ 不得在花色照片或低对比背景上直接放标志——加纯色底或半透明遮罩
- ❌ 不得侵入 clear space

### 背景适配

| 背景 | 使用色版 |
|---|---|
| 白 / 浅色底 | 红版（首选）或黑版 |
| 黑 / 深色底 | 白版 |
| Etna Red 底 | 白版 |
| 照片 | 白版 + 深色遮罩（不透明度 ≥ 40%） |

---

## 8. 待办 / 需设计确认

1. ~~补一个红色竖版 logo 的 PNG 导出~~ — 已补齐（B-16 竖版红），资产完整（§1.3）
2. ~~确定 CMYK 与 Pantone 值~~ — 已确认以 `#C43426` 为唯一色值定义，不另设规格（§4.2）
3. **确认 tagline 的句号空格**是失误还是有意（§6）
4. **统一网站品牌红**：`globals.css` 的 `#c45a48` → `#C43426`（§4.5）
5. **重命名字体文件** `finSans-Regular-7 2.ttf` → `JosefinSans-Regular.ttf`（§5）
6. **确认 Avenir Next 的 webfont 授权**，否则网页端改用 Inter（§5.2）
