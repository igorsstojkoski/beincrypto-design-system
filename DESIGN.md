[DESIGN.md](https://github.com/user-attachments/files/26965295/DESIGN.md)---
version: alpha
name: BeInCrypto
description: Visual identity for BeInCrypto — a leading crypto media and data platform. Covers editorial surfaces, product UIs, and InMarkets.

colors:
  # Neutrals
  neutral-950: "#0A0A0A"
  neutral-900: "#111111"
  neutral-850: "#1A1A1A"
  neutral-800: "#222222"
  neutral-750: "#2E2E2E"
  neutral-700: "#3A3A3A"
  neutral-500: "#7A7A7A"
  neutral-450: "#7A7A7A"
  neutral-400: "#B3B3B3"
  neutral-300: "#E6E6E6"
  neutral-200: "#F0F0F0"
  neutral-150: "#F5F5F5"
  neutral-100: "#F8F8F8"
  neutral-50: "#FAFAFA"
  neutral-0: "#FFFFFF"

  # Brand / Primary
  primary: "#C8F026"
  primary-lime: "#C8F026"

  # Semantic — Positive (gains, uptrends, success)
  positive-300: "#A8F060"
  positive-400: "#6DC832"
  positive-500: "#3A9E1A"
  positive-600: "#1E7010"

  # Semantic — Negative (losses, downtrends, warnings)
  negative-300: "#FF7070"
  negative-400: "#E83232"
  negative-500: "#A81414"

  # Semantic — Warning
  warning-300: "#FFB060"

  # Extended palette (covers only)
  cover-green: "#0BA24B"
  cover-cyan: "#2CDEFF"
  cover-blue: "#080CED"
  cover-purple: "#DD51F8"
  cover-violet: "#5339E5"
  cover-red: "#F7374B"

typography:
  # Geist — BeInCrypto editorial & product (default)
  hero-1:
    fontFamily: Geist
    fontSize: 96px
    fontWeight: 700
    lineHeight: 102px
  hero-2:
    fontFamily: Geist
    fontSize: 64px
    fontWeight: 700
    lineHeight: 72px
  hero-3:
    fontFamily: Geist
    fontSize: 46px
    fontWeight: 700
    lineHeight: 58px
  heading-1:
    fontFamily: Geist
    fontSize: 38px
    fontWeight: 600
    lineHeight: 46px
  heading-2:
    fontFamily: Geist
    fontSize: 30px
    fontWeight: 600
    lineHeight: 38px
  heading-3:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: 600
    lineHeight: 32px
  heading-4:
    fontFamily: Geist
    fontSize: 20px
    fontWeight: 600
    lineHeight: 28px
  heading-5:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: 600
    lineHeight: 24px
  subtitle-1:
    fontFamily: Geist
    fontSize: 30px
    fontWeight: 500
    lineHeight: 38px
  subtitle-2:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: 500
    lineHeight: 32px
  subtitle-3:
    fontFamily: Geist
    fontSize: 20px
    fontWeight: 500
    lineHeight: 28px
  subtitle-4:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: 500
    lineHeight: 24px
  subtitle-5:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: 500
    lineHeight: 22px
  subtitle-6:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: 500
    lineHeight: 20px
  paragraph-1:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: 400
    lineHeight: 32px
  paragraph-2:
    fontFamily: Geist
    fontSize: 20px
    fontWeight: 400
    lineHeight: 28px
  paragraph-3:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
  paragraph-4:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: 400
    lineHeight: 22px
  paragraph-5:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: 400
    lineHeight: 20px

  # Noto Sans — InMarkets product
  inmarkets-base:
    fontFamily: Noto Sans
    fontSize: 14px
    fontWeight: 400
    lineHeight: 22px
  inmarkets-xsm:
    fontFamily: Noto Sans
    fontSize: 10px
    fontWeight: 400
    lineHeight: 12px
  inmarkets-sm:
    fontFamily: Noto Sans
    fontSize: 12px
    fontWeight: 400
    lineHeight: 20px
  inmarkets-lg:
    fontFamily: Noto Sans
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
  inmarkets-xl:
    fontFamily: Noto Sans
    fontSize: 20px
    fontWeight: 400
    lineHeight: 28px
  inmarkets-heading-1:
    fontFamily: Noto Sans
    fontSize: 38px
    fontWeight: 600
    lineHeight: 46px
  inmarkets-heading-2:
    fontFamily: Noto Sans
    fontSize: 30px
    fontWeight: 600
    lineHeight: 38px
  inmarkets-heading-3:
    fontFamily: Noto Sans
    fontSize: 24px
    fontWeight: 600
    lineHeight: 32px
  inmarkets-heading-4:
    fontFamily: Noto Sans
    fontSize: 20px
    fontWeight: 600
    lineHeight: 28px
  inmarkets-heading-5:
    fontFamily: Noto Sans
    fontSize: 16px
    fontWeight: 600
    lineHeight: 24px

  # Instrument Serif — Brand accent typeface
  accent:
    fontFamily: Instrument Serif
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px

rounded:
  xs: 2px
  sm: 4px
  DEFAULT: 6px
  md: 8px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  ms: 16px
  md: 20px
  lg: 24px
  xl: 32px
  xxl: 40px
  xxxl: 48px

components:
  button-primary:
    backgroundColor: "{colors.neutral-900}"
    textColor: "{colors.neutral-0}"
    typography: "{typography.subtitle-5}"
    rounded: "{rounded.DEFAULT}"
    padding: 8px 16px
  button-primary-hover:
    backgroundColor: "{colors.neutral-800}"
  button-secondary:
    backgroundColor: "{colors.neutral-0}"
    textColor: "{colors.neutral-900}"
    typography: "{typography.subtitle-5}"
    rounded: "{rounded.DEFAULT}"
    padding: 8px 16px
  button-ghost:
    backgroundColor: transparent
    textColor: "{colors.neutral-900}"
    typography: "{typography.subtitle-5}"
    rounded: "{rounded.DEFAULT}"
    padding: 8px 16px
  card:
    backgroundColor: "{colors.neutral-0}"
    textColor: "{colors.neutral-900}"
    rounded: "{rounded.md}"
    padding: "{spacing.lg}"
  card-sponsored:
    backgroundColor: "{colors.neutral-200}"
    textColor: "{colors.neutral-900}"
    rounded: "{rounded.md}"
    padding: "{spacing.lg}"
  input:
    backgroundColor: "{colors.neutral-0}"
    textColor: "{colors.neutral-900}"
    typography: "{typography.paragraph-4}"
    rounded: "{rounded.sm}"
    padding: 8px 12px
    height: 36px
  input-sm:
    backgroundColor: "{colors.neutral-0}"
    textColor: "{colors.neutral-900}"
    typography: "{typography.paragraph-5}"
    rounded: "{rounded.xs}"
    padding: 4px 8px
    height: 28px
  badge-positive:
    backgroundColor: "{colors.positive-300}"
    textColor: "{colors.neutral-900}"
    typography: "{typography.subtitle-6}"
    rounded: "{rounded.xs}"
    padding: 2px 6px
  badge-negative:
    backgroundColor: "{colors.negative-300}"
    textColor: "{colors.neutral-0}"
    typography: "{typography.subtitle-6}"
    rounded: "{rounded.xs}"
    padding: 2px 6px
  badge-warning:
    backgroundColor: "{colors.warning-300}"
    textColor: "{colors.neutral-900}"
    typography: "{typography.subtitle-6}"
    rounded: "{rounded.xs}"
    padding: 2px 6px
---

## Overview

BeInCrypto is a crypto-native media and data platform that blends editorial journalism with real-time market intelligence. The visual identity is built on **clarity, trust, and precision** — qualities essential in the fast-moving world of digital assets.

The design language is clean and editorial-first: high-contrast neutrals form the backbone, with Lime (`#C8F026`) as the single energetic accent that signals action and brand presence. Typography is tight and hierarchical, favoring legibility at scale over decorative expression. The overall aesthetic is modern-functional — confident but never flashy.

Two distinct product contexts exist within the BeInCrypto family: the main editorial and product surfaces (using Geist), and the InMarkets data product (using Noto Sans for its superior rendering of dense numerical data). Both share the same color system and spacing scale.

## Colors

The color system is built on a deep neutral scale with semantic layers for financial data and a single brand accent.

- **Neutral scale (950–0):** The foundation of all UI surfaces. Dark neutrals (`#111111`, `#0A0A0A`) anchor text and navigation. Mid neutrals (`#7A7A7A`, `#B3B3B3`) handle secondary text, borders, and metadata. Light neutrals (`#F0F0F0`, `#FFFFFF`) define content backgrounds and dividers.
- **Primary / Lime (`#C8F026`):** The signature BeInCrypto accent. Used for brand moments, key CTAs, and interactive highlights. Never used for body text or decorative fills in editorial content.
- **Positive (green scale):** Reserved strictly for price gains, uptrends, and success states. Ranges from bright `#A8F060` (300) to deep `#1E7010` (600).
- **Negative (red scale):** Reserved for losses, downtrends, and destructive actions. Ranges from `#FF7070` (300) to `#A81414` (500).
- **Warning (`#FFB060`):** Used for caution states, stale data indicators, and alerts.
- **Extended palette (covers only):** Green, Cyan, Blue, Purple, Violet, and Red are used exclusively for editorial cover imagery and hero visuals — never in product UI components.

Semantic colors are applied sparingly to preserve editorial clarity. Decorative use of positive/negative colors outside of financial data contexts is not permitted.

## Typography

BeInCrypto uses three typefaces, each with a distinct role:

**Geist** is the primary typeface across all BeInCrypto editorial and product surfaces. Its geometric clarity and strong weight range support a broad typographic hierarchy from Hero display sizes down to fine-print paragraphs. SemiBold/Bold weights are used for headings; Regular/Medium for body and UI text.

**Noto Sans** is used exclusively within the InMarkets product. Its superior rendering of numerals and dense tabular data makes it the right choice for financial dashboards, price tables, and data-heavy components. The same size/line-height scale applies as Geist.

**Instrument Serif** is the brand accent typeface. Used selectively in editorial tags, pull quotes, graphic accents, and brand moments. It is never used for functional UI text or data display.

Hierarchy is defined through size and weight changes within each family — not by switching typefaces mid-component.

## Layout & Spacing

The spacing system is based on a 4px base unit, scaling from `4px` (xxs) to `48px` (xxxl). All layout decisions — margins, padding, gaps — should reference a value from this scale.

- **Content surfaces** use light backgrounds (Neutral 0) with generous whitespace to support reading and scanning.
- **Navigation and framing elements** use dark neutrals to create clear structural separation from content.
- **Control padding** (horizontal: 12px, compact: 8px) governs interactive elements like buttons and inputs.
- **Content padding** scales between SM and LG depending on the density of the surface.

## Elevation & Depth

Shadows are used to establish hierarchy and materiality without relying on color. Three levels are defined:

- **boxShadow (default):** `0 6px 16px 0 rgba(0,0,0,0.08), 0 3px 6px -4px rgba(0,0,0,0.12), 0 9px 28px 8px rgba(0,0,0,0.05)` — applied to overlapping surfaces such as cookie banners and floating panels.
- **boxShadowSecondary:** Same values as default — used on interactive floating components like dropdowns, float buttons, and cascader menus.
- **boxShadowTertiary:** `0 1px 2px 0 rgba(0,0,0,0.03), 0 1px 6px -1px rgba(0,0,0,0.02), 0 2px 4px 0 rgba(0,0,0,0.02)` — the subtlest shadow, used on forms, login/signup panels, and action panels.

Dark backgrounds should rely on border definition rather than shadows for layering.

## Shapes

BeInCrypto uses a restrained, functional rounding system. Corners are never decorative — they reflect the component's size and context.

- **xs (2px):** Segmented controls, arrow components, and elements requiring minimal rounding.
- **sm (4px):** Small input fields, buttons in small size, select components.
- **DEFAULT (6px):** Standard components — the most common border radius across the system.
- **md (8px):** Cards, modals, drawers, and larger container components.

Pill shapes (`border-radius: 9999px`) are reserved for tags and badge components only.

## Components

### Buttons
Primary buttons use `neutral-900` fill on light backgrounds for maximum contrast — reserved for key conversion actions (Subscribe, Sign Up, Connect Wallet). Ghost and secondary variants maintain the same rounding and typography but differ in fill treatment.

### Cards
Default cards use a white background with `rounded.md` (8px) corners. Sponsored or highlighted content uses `neutral-200` background to signal editorial distinction without breaking hierarchy.

### Inputs & Controls
Inputs use `rounded.sm` (4px) at standard size and `rounded.xs` (2px) at small size. All interactive controls reference the spacing token scale for consistent padding.

### Badges & Indicators
Financial badges (positive, negative, warning) use semantic colors and are the only components permitted to use the positive/negative color scale. Typography is always `subtitle-6` to maintain small, non-intrusive presence.

## Do's and Don'ts

- **Do** use Lime (`#C8F026`) only as an accent — never as a background fill for large surfaces.
- **Do** use positive/negative colors exclusively for financial data states (price changes, P&L, trends).
- **Do** keep Instrument Serif to accent moments — tags, pull quotes, graphic elements only.
- **Don't** use the extended cover palette (Green, Cyan, Blue, Purple, Violet, Red) in product UI components.
- **Don't** mix Geist and Noto Sans on the same surface — use Geist for editorial/product and Noto Sans for InMarkets only.
- **Don't** use contrasting colors for the logo against a visually busy or low-contrast background.
- **Don't** apply stroke effects to the logo or use old logo variants.
- **Don't** use decorative colors in editorial content — neutrals and semantic colors only.

