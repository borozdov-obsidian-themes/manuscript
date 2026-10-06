# Borozdov Manuscript

A theme from the Borozdov collection. Two faces — light **Onionskin**, an editorial
manuscript on warm linen, and dark **Inkblot**, the same page under lamplight. A
whisper-weight serif carries the title and headings, the platform's own sans carries the
body, and one sage green spark is the only saturated colour in the system.

![Borozdov Manuscript in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/manuscript/main/screenshots/light.png)

![Borozdov Manuscript in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/manuscript/main/screenshots/dark.png)

## Principles

- **A manuscript, not a magazine.** Manuscript Serif — upright, unhurried — sets the title
  and the three largest headings; the two smallest headings and all body text stay in the
  platform's own sans, the way a page's marginalia stay plainer than its title.
- **One sage spark.** Sage green appears only in small, functional doses: links, the caret,
  tag outlines, blockquote rules and the plain note callout's tinted wash. It never fills a
  button.
- **Linen, not shadow.** Cards step from canvas to fog to linen with a soft 3px corner;
  nothing casts a shadow. The main button fills solid charcoal — never the sage — and turns
  sage only on hover; plain buttons are 3px-cornered outlines.
- **A ledger's table.** Tables draw their own hairline frame and inner grid, ruled like a
  page in a notebook rather than boxed like a spreadsheet.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as flat linen cards with soft 3px corners; the plain note tinted with the sage
  wash
- Blockquotes in the manuscript serif, a size up, behind a sage rule
- Tables ruled like a ledger page, with a linen header and a hairline frame
- Tags as thin sage outlines, never filled
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Ember**. Install Borozdov Ember under Settings → Appearance → Themes → Manage, then the
[Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and choose
**Manuscript** under Style Settings → Borozdov Ember → Variant. The variant brings this
theme's palette, type and corners; its own layout, and its embedded font if it has one,
come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/manuscript/releases/latest)
into `<vault>/.obsidian/themes/Borozdov Manuscript/`, then choose Borozdov Manuscript under
Settings → Appearance → Themes.

## Font

Manuscript Serif is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License
1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of Erewhon
(© 2014–2021 Michael J. Sharpe, itself based on Andrey V. Panov's Heuristica and, further
back, Adobe's Utopia), renamed because a modified copy may not use the original's Reserved
Font Name. One weight, for the title and the three largest headings only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Onionskin» — редакционная
рукопись на тёплой льняной бумаге, и тёмный «Inkblot» — та же страница при свете лампы.
Шёпот-антиква несёт заголовок и подзаголовки, рубленый шрифт платформы — основной текст,
а один шалфейный акцент — единственный насыщенный цвет в системе. В каталоге тема живёт вариантом Borozdov Ember: установите Borozdov Ember и плагин Style Settings, затем выберите Manuscript в Style Settings → Borozdov Ember → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
