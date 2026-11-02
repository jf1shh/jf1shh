# Brand guide

One look for everything public: LinkedIn, the CV, the GitHub READMEs and the portfolio page.
Dark and quiet, with one violet accent. It should feel like a night-time control room: calm, precise,
a little bit alive.

## Colors

| Name | Hex | Use |
|---|---|---|
| Ink | `#0D0B14` | Page backgrounds, body text on light pages |
| Deep indigo | `#1E1B4B` | Gradient mid-stop, cards on dark pages (matches `assets/banner.svg`) |
| **Violet** | `#7C3AED` | The one accent: name, headings, links, buttons, glows |
| Lavender | `#C4B5FD` | Soft highlights, hover states, text on dark backgrounds |
| Mist | `#F4F2FA` | Light pages, print documents |
| Spark | `#0EA5E9` | Rare second glow (used once in the banner); never for text or links |

Rules:
- Violet is the only accent. Lavender and Spark support it.
- Body text on dark: Mist at 90% opacity. On light: Ink.
- Check contrast before shipping. Violet on Ink passes for large text and UI. For small text on dark, use Lavender.
- Violet text on white is fine for headings and links (about 5.7:1) but not for small gray-on-violet text.

## Type

- **Headings and UI:** a clean sans (Inter, falling back to `system-ui`). Bold, tight letter spacing.
- **Code, numbers and eval scores:** a monospace (JetBrains Mono, falling back to `ui-monospace`).
- **CV:** moderncv "banking" in its default sans, with violet name and section headings.

## Motifs

- Network lines and nodes (the LinkedIn banner): thin lines, small glowing dots, violet on near-black.
- Soft radial glows in the corners, never a flat color block.
- Hairline borders at 14% white on dark surfaces.
- Evidence first: show real numbers (tests, eval scores, citations) in monospace.

## Voice

Plain, specific, honest. Say what was built, how it was checked and what its limits are.
No hype words. Claims tools are "advisory only"; assistants at Liberty Mutual were pilots and demos.
Facts to reuse verbatim: 17 years at Liberty Mutual, 11 as senior appraiser; building with AI since March 2026.

## Where it applies

| Surface | Status |
|---|---|
| LinkedIn banner and photo | Already on brand |
| `assets/banner.svg` (this repo) | On brand |
| CV master template | Violet `#7C3AED` accents |
| ClaimsRAG and harness READMEs | To do |
| Portfolio page | Live at https://jf1shh.github.io/ (repo `jf1shh/jf1shh.github.io`): Ink background, Violet/Lavender gradients, Spark rare |
| LinkedIn and profile README links to the portfolio | To do |
