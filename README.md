# ETNA Labs — Brand Assets & Guide

> Canonical repository for Etna brand assets. This README is the asset index and quick reference.
> Design version: July 2026　｜　Primary color: `#C43426`

The authoritative usage specification is [`BRAND_GUIDE.md`](./BRAND_GUIDE.md). Content marked **[Source]** comes directly from the design files. Content marked **[Recommended]** is added implementation guidance not defined in the source.

---

## 0. Brand Guide & Agent Entry Point

Before creating or editing any Etna website, report, presentation, chart, document, or visual asset, read [`BRAND_GUIDE.md`](./BRAND_GUIDE.md) in full.

For agents and automated design systems:

1. Treat `BRAND_GUIDE.md` as the single source of truth for logo, color, typography, and usage rules.
2. Preserve both the HEX values and the semantic role of every design token; do not interchange colors based on appearance alone.
3. Use only Etna Red, black, or white logo assets. Extended application colors must never be applied to the logo.
4. If this README, an implementation, or an older asset conflicts with `BRAND_GUIDE.md`, follow `BRAND_GUIDE.md`.

Quick links:

- [Complete brand guide](./BRAND_GUIDE.md)
- [Logo PNGs](./logos/png)
- [Fonts](./fonts)

---

## 1. Logo

<img src="https://raw.githubusercontent.com/hannahhoo47/Etna-Asset/main/logos/png/etna-horizontal-red.png" width="440" alt="ETNALabs">

### 1.1 Construction

The logo is made up of the ETNA wordmark and the "Labs" subtitle. The letter **A** is replaced by the silhouette of Mount Etna: a solid red triangle (the mountain) with a white notch at the top (the crater as negative space, which also forms the crossbar of the A). This is the only graphic element in the identity and the immutable core of the mark — **never substitute a plain letter A.**

### 1.2 Standard Lockups

| Lockup | Description | Use |
|---|---|---|
| **Vertical** | ETNA over Labs | Avatars, seals, square placements |
| **Horizontal** | ETNALabs on one line | Website header, email signature, document footer |

Each lockup comes in **red / black / white**. Red versions:

| Vertical | Horizontal |
|:--:|:--:|
| <img src="https://raw.githubusercontent.com/hannahhoo47/Etna-Asset/main/logos/png/etna-vertical-red.png" width="200"> | <img src="https://raw.githubusercontent.com/hannahhoo47/Etna-Asset/main/logos/png/etna-horizontal-red.png" width="260"> |

### 1.3 Asset List

All PNGs live in [`logos/png/`](https://github.com/hannahhoo47/Etna-Asset/tree/main/logos/png) (6 files — 2 lockups × red / black / white, transparent background):

| File | Lockup | Color |
|---|---|---|
| [`etna-vertical-red.png`](https://github.com/hannahhoo47/Etna-Asset/blob/main/logos/png/etna-vertical-red.png) | Vertical | Red |
| [`etna-vertical-black.png`](https://github.com/hannahhoo47/Etna-Asset/blob/main/logos/png/etna-vertical-black.png) | Vertical | Black |
| [`etna-vertical-white.png`](https://github.com/hannahhoo47/Etna-Asset/blob/main/logos/png/etna-vertical-white.png) | Vertical | White |
| [`etna-horizontal-red.png`](https://github.com/hannahhoo47/Etna-Asset/blob/main/logos/png/etna-horizontal-red.png) | Horizontal | Red |
| [`etna-horizontal-black.png`](https://github.com/hannahhoo47/Etna-Asset/blob/main/logos/png/etna-horizontal-black.png) | Horizontal | Black |
| [`etna-horizontal-white.png`](https://github.com/hannahhoo47/Etna-Asset/blob/main/logos/png/etna-horizontal-white.png) | Horizontal | White |

> Legacy assets used by the live tool (**do not delete** — `index.html` hotlinks them):
> [`Etnalabs_redback.png`](https://github.com/hannahhoo47/Etna-Asset/blob/main/Etnalabs_redback.png) ·
> [`EtnaLabs_horizontal_trans.png`](https://github.com/hannahhoo47/Etna-Asset/blob/main/EtnaLabs_horizontal_trans.png) ·
> [`EtnaLabs_vertical_trans.png`](https://github.com/hannahhoo47/Etna-Asset/blob/main/EtnaLabs_vertical_trans.png)

---

## 2. Clear Space **[Source]**

Keep clear space of **X** on all sides of the logo. No text, graphics, image edges, or layout margins may enter it.

```
        ┌─────── X ───────┐
        │  ┌───────────┐  │
        X  │   LOGO    │  X        X = 1/2 × lockup height
        │  └───────────┘  │
        └─────── X ───────┘
```

**X = half the total height of the logo.** Measured from the vector files, this ratio is 0.50 for every standard lockup (e.g. 91/183.55, 71.08/143.36, 65/129.78).

Example: at a placed height of 40px, keep ≥ 20px of clear space on all sides.

## 3. Minimum Size

- **[Source]** Print: minimum logo height **6mm**.
- **[Recommended]** Screen: minimum height **24px** (6mm ≈ 22.7px @96dpi). Below this, the crater notch merges with the mountain outline and the mark loses legibility.

---

## 4. Color — Quick Reference

The official logo palette contains three colors:

| Color | HEX | Use |
|---|---|---|
| **Etna Red** | `#C43426` | Primary brand color, logo, emphasis, CTA |
| **Black** | `#000000` | Logo, monochrome applications |
| **White** | `#FFFFFF` | Reversed logo, whitespace |

`#C43426` is the sole authoritative definition of Etna Red. Print conversions depend on the printer's ICC profile and paper; do not treat a converted CMYK value as a separate brand color specification. See [`BRAND_GUIDE.md` §4.2](./BRAND_GUIDE.md#42-印刷转换).

### 4.1 Extended Application Palette

These colors extend the official palette for reports, presentations, websites, charts, and digital products. They do not replace Etna Red and must never recolor the logo.

| Token | Name | HEX | Semantic role |
|---|---|---|---|
| `--etna-red` | **Etna Red** | `#C43426` | Brand anchor; conviction and confirmed key conclusions |
| `--deep-mineral` | **Deep Mineral** | `#596455` | Structure; long-term trends, markets, talent, and ecosystems |
| `--mineral-blue` | **Mineral Blue** | `#65798A` | Analysis; technology, data, AI, robotics, and infrastructure |
| `--mineral-sage` | **Mineral Sage** | `#A7B1A2` | Provisional categories and low-priority context |
| `--mist-blue` | **Mist Blue** | `#B5C0C7` | Forecast, estimate, or information pending confirmation |

Etna Red is the least-used but most prominent color. Deep Mineral and Mineral Blue are structural application colors, not additional brand primaries. Mineral Sage and Mist Blue must not communicate provisional status by color alone; pair them with labels such as `Draft`, `Forecast`, `Estimate`, or `Preliminary`.

### 4.2 Neutral Surfaces

| Token | Name | HEX | Use |
|---|---|---|---|
| `--ink` | Ink | `#191715` | Body text |
| `--muted` | Muted | `#6D6860` | Secondary text |
| `--line` | Line | `#D8CEC2` | Dividers, strokes |
| `--bg` | **Warm Paper** | `#F4F0EA` | Narrative environment and section background |
| `--white` | **White** | `#FFFFFF` | Facts, reading, charts, tables, and interactive content |
| `--paper` | Paper | `#FFFDF9` | Cards and elevated surfaces |

**Rule:** White carries information; Warm Paper carries environment. When both appear, use Warm Paper as the outer page or section background and White for the information-dense inner surface. Full usage ratios and constraints are in [`BRAND_GUIDE.md` §4.4](./BRAND_GUIDE.md#44-扩展应用色板-品牌应用规范2026-07-24-确认).

---

## 5. Typography

Font files live in [`fonts/`](https://github.com/hannahhoo47/Etna-Asset/tree/main/fonts).

| Font | File | Role | License |
|---|---|---|---|
| **Josefin Sans** | [`fonts/JosefinSans-Regular.ttf`](https://github.com/hannahhoo47/Etna-Asset/blob/main/fonts/JosefinSans-Regular.ttf) | Display | OFL (open source) |
| **Alimama FangYuanTi VF** | [`fonts/AlimamaFangYuanTiVF-Thin.ttf`](https://github.com/hannahhoo47/Etna-Asset/blob/main/fonts/AlimamaFangYuanTiVF-Thin.ttf) | Chinese | Free for commercial use |
| **Avenir Next** | — (not included) | Latin body / UI | ⚠️ Proprietary Apple font — not distributed with this repo |

> The design file `finSans-Regular-7 2.ttf` is actually **Josefin Sans** (confirmed via its internal name table); renamed to `JosefinSans-Regular.ttf` in this repo.

### Hierarchy **[Recommended]**

| Level | Font | Notes |
|---|---|---|
| **Logotype** | Custom | The four ETNA letters (including the volcano A) are custom-drawn — **never reset in any font**; use the vector files only |
| **Display** | Josefin Sans | Geometric sans, low x-height, same character as the logo. Large sizes only |
| **Latin body / UI** | Avenir Next Regular / Medium | Better long-form legibility than Josefin Sans |
| **Chinese** | Alimama FangYuanTi VF | Rounded geometric, matches Josefin Sans |

Josefin Sans is for large sizes only; use Avenir Next for body text below 16px. On web, fall back to Inter where you don't have an Avenir Next webfont license.

---

## 6. Don'ts **[Recommended]**

- ❌ Don't stretch, compress, or skew the logo — scale proportionally
- ❌ Don't recolor the logo (red / black / white only)
- ❌ Don't add strokes, shadows, gradients, or glows
- ❌ Don't rotate the logo
- ❌ Don't rearrange the position or size of elements within a lockup
- ❌ Don't replace the volcano A with a plain letter A
- ❌ Don't place the logo directly on busy photos or low-contrast backgrounds — add a solid fill or semi-transparent scrim
- ❌ Don't intrude into the clear space

### Background Pairing

| Background | Version |
|---|---|
| White / light | Red (preferred) or black |
| Black / dark | White |
| Etna Red | White |
| Photo | White + dark scrim (opacity ≥ 40%) |
