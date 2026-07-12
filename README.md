# ETNA Labs — Brand Assets & Guide

> Brand visual asset repository. This README is the brand usage guide.
> Design version: July 2026　｜　Primary color: `#C43426`

Content marked **[Source]** comes directly from the design files. Content marked **[Recommended]** is added implementation guidance not defined in the source.

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

## 4. Color **[Source]**

The brand color spec defines three colors, with HEX and CMYK:

| Color | HEX | RGB | CMYK |
|---|---|---|---|
| **Etna Red** | `#C43426` | 196, 52, 38 | **C29 M92 Y95 K0** |
| **Black** | `#000000` | 0, 0, 0 | C0 M0 Y0 K100 |
| **White** | `#FFFFFF` | 255, 255, 255 | C0 M0 Y0 K0 |

> ℹ️ The red row in the source is labeled **"CMKY: 29 92 95 0"** — `CMKY` is a typo for `CMYK`; in standard order the value is **C29 M92 Y95 K0**.
> HEX is for screen, CMYK for print. Output still varies slightly by ICC profile and paper, so proof on the first print run.

### 4.1 Neutral Scale **[Recommended]**

The source does not define neutrals. Suggested set for web and documents, warm-shifted from Etna Red:

| Token | HEX | Use |
|---|---|---|
| `--ink` | `#191715` | Body text |
| `--muted` | `#6D6860` | Secondary text |
| `--line` | `#D8CEC2` | Dividers, strokes |
| `--bg` | `#F4F0EA` | Page background |
| `--paper` | `#FFFDF9` | Cards, surfaces |

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
