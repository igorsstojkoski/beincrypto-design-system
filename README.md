# BeInCrypto Design System

A machine-readable design system specification for BeInCrypto, built on the [DESIGN.md](https://github.com/google-labs-code/design.md) format by Google Labs.

`DESIGN.md` gives AI coding agents a persistent, structured understanding of BeInCrypto's visual identity — so every agent, tool, and codebase produces UI that looks and feels on-brand.

---

## What's inside

- **Colors** — full neutral scale, Lime brand accent, semantic positive/negative/warning colors, and extended cover palette
- **Typography** — Geist (editorial & product), Noto Sans (InMarkets), and Instrument Serif (accent)
- **Spacing** — 4px base unit scale from `4px` to `48px`
- **Border radius** — xs through md, with component context
- **Shadows** — three elevation levels for layering and depth
- **Components** — buttons, cards, inputs, and financial badges with full token references
- **Do's and Don'ts** — logo rules, color misuse, typeface mixing

---

## Usage

Point any AI coding agent at `DESIGN.md` to apply BeInCrypto's visual identity automatically.

You can also validate the file using the DESIGN.md CLI:

```bash
npx @google/design.md lint DESIGN.md
```

Or export tokens to Tailwind or DTCG format:

```bash
npx @google/design.md export --format tailwind DESIGN.md
npx @google/design.md export --format dtcg DESIGN.md
```

---

## Contributing

To update the design system, edit `DESIGN.md` directly. Token changes should reflect updates in Figma variables. Prose sections should explain the *why* behind any token changes, not just the values.
