# dargstack brand

## Idea

The name carries the system: `darg` is the dark part, the machine layer nobody wants to hand-edit; `stack` is what you actually reason about, layers one on top of the other, each one only the difference from the one below.

The mark shows exactly two levels. Development is the base bar, sitting in the dark, carrying the full width of the system. Production is the shorter bar on top: not a copy, just the part that changes.

## Tagline

"Ship the diff, skip the myth", with the subhead "Deployment automation for Docker Swarm."

## Mark

| File | Use |
| --- | --- |
| `dargstack-mark-primary.svg` / `.png` | Default, on dark/graphite backgrounds |
| `dargstack-mark-inverted.svg` / `.png` | On paper/light backgrounds |
| `dargstack-mark-monotone.svg` / `.png` | Single tone (uses `currentColor` in the SVG), for stamps and favicons below 24px |

### Construction

Built on a 64-unit square. Two bars, 14 units tall, 4 units apart: a 48-wide base and a 36-wide overlay inset 12 units from the left. The base is development; the overlay is production, sitting on top and covering only part of it.

Clear space equals one bar height (14 units) on all sides. Minimum size 16px; below 24px drop to the single-tone variant.

Never add a third bar, align the two bars flush, re-tint them, rotate the mark, or place it on a photo without a solid plate behind it.

## Wordmark

Always lowercase, always one word, set in IBM Plex Mono Bold with -3% tracking. It is a command you type, not a company name.

Never "DargStack", "Dargstack", or "darg-stack". Never italic. Never letterspaced open.

## Palette

| Name | Hex | Use |
| --- | --- | --- |
| void | `#0E1113` | page ground |
| graphite | `#16191C` | surface, cards |
| slate | `#2B3238` | base layer, rules |
| signal | `#4A7BB0` | the one accent |
| signal light | `#A8CBEC` | accent text on dark |
| ink | `#E6EAED` | primary text |

Status: ok `#6FAE82`, warn `#D3A758`, error `#CF8B7C`, dim `#6B767E`

## Type

- **IBM Plex Mono**: wordmark, code, labels, all CLI surfaces
- **Archivo**: headlines, body, documentation prose (Regular 400 body, Medium 500 lead paragraphs, SemiBold 600 headlines)

## Voice

Direct, technical, unhurried. State the mechanism, then the consequence. Full sentences, one idea per line, the README already sounds right.

> "Production files contain only differences from development."

> "dargstack does not replace docker stack."

No adjectives it can't prove.

## Social assets

| File | Size | Use |
| --- | --- | --- |
| `dargstack-readme-header.png` | 1280x320 | README header |
| `dargstack-social-card.png` | 1280x640 | Social card / OpenGraph image |
