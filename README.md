# Beamer Themes Collection

A collection of 17 original LaTeX Beamer presentation themes — covering a range of styles from minimal and academic to bold and playful. Each theme is packaged as a standalone zip containing its `.sty` file, a demo deck, a README, and a compiled preview PDF.

All themes are by **Priyansh Saxena**.

## Previews

Compiled PDF previews for every theme live in [`previews/`](previews/) — open one to see the theme in action before downloading its zip.

## Themes

| Theme | Description |
|---|---|
| [backyardbuild-beamer-theme.zip](backyardbuild-beamer-theme.zip) | A sunny summer-cartoon theme with a sky, sun, fence and grass title slide, sketchbook-grid content slides, tilted build-part cards, sticky notes, and a mission-file closing slide. |
| [chiselled-beamer-theme.zip](chiselled-beamer-theme.zip) | A prehistoric cartoon theme with a volcano title slide, sandstone content slides, carved stone tablets, a cave-painting timeline, and a campfire closing slide. |
| [commit-beamer-theme.zip](commit-beamer-theme.zip) | A light git-history theme where frame titles carry commit hashes, bullets are added lines, and section slides check out new branches. |
| [dotmaze-beamer-theme.zip](dotmaze-beamer-theme.zip) | A neon maze-chase arcade theme with a dot-eating footer, corridor diagrams, pellet cards for key ideas, and bug cards for common mistakes. |
| [epoch-beamer-theme.zip](epoch-beamer-theme.zip) | A dark training-dashboard theme with run-status title slides, training-log footers, checkpoint section slides, and metric/chart cards. |
| [gridcell-beamer-theme.zip](gridcell-beamer-theme.zip) | A light spreadsheet theme with a formula-bar title, column/row grid framing, cell-style frame titles, and sheet-tab section markers. |
| [insertcoin-beamer-theme.zip](insertcoin-beamer-theme.zip) | A retro arcade theme with CRT scanlines, a climbing score HUD, boss-fight and power-up slides, and a GAME OVER closing slide. |
| [jaali-beamer-theme.zip](jaali-beamer-theme.zip) | A Mughal-geometry theme built from patterns only, with arch-framed titles, star tiles, gold-framed content, and a lattice (jaali) closing slide. |
| [neoncoast-beamer-theme.zip](neoncoast-beamer-theme.zip) | An 80s Miami-sunset theme with a striped sunset title slide, a glowing perspective grid floor, a "now playing" footer, and neon cards. |
| [preprint-beamer-theme.zip](preprint-beamer-theme.zip) | A light academic theme for paper-reading sessions, with serif type, numbered sections, abstracts, captioned figures, and numbered equations/references. |
| [reviewed-beamer-theme.zip](reviewed-beamer-theme.zip) | A light pull-request theme with a PR-header title slide, red/green code diffs, review-comment callouts, and a Merged closing slide. |
| [schematic-beamer-theme.zip](schematic-beamer-theme.zip) | A blueprint theme with white linework on grid paper, an architect's title block, sheet numbers, and TikZ styles for dimension lines and callouts. |
| [sidescroller-beamer-theme.zip](sidescroller-beamer-theme.zip) | A side-scrolling platformer theme with a pixel-cloud sky, a score/coins/stage HUD, a level-select agenda map, and a COURSE CLEAR closing slide. |
| [stacked-beamer-theme.zip](stacked-beamer-theme.zip) | A falling-block puzzle theme with a block-well title slide, a filling side HUD, and LINE CLEAR cards for takeaways. |
| [tabline-beamer-theme.zip](tabline-beamer-theme.zip) | A dark code-editor theme with section-based file tabs, gutter line numbers, and a status bar carrying branch/section/slide count. |
| [tiles-beamer-theme.zip](tiles-beamer-theme.zip) | A flat tile-based theme with oversized titles, a mosaic title slide, numbered section tiles, and a `\tile` macro for custom layouts. |
| [traceback-beamer-theme.zip](traceback-beamer-theme.zip) | A dark log/stack-trace theme with breadcrumb frame titles, INFO/WARN/ERROR/FIX tagged points, and a code-0 exit closing slide. |

## Using a theme

Each zip contains a complete, standalone LaTeX project:

```
<theme-name>/
├── beamertheme<Name>.sty   # the theme
├── main.tex                # demo deck — copy this to start a new talk
├── main.pdf                # compiled preview
├── latexmkrc                # tells latexmk/Overleaf to use XeLaTeX
├── fonts/                   # optional custom fonts
└── README.md                # theme-specific docs, palette, macros
```

1. Download and unzip the theme you want.
2. Compile with XeLaTeX (recommended) — locally via `latexmk main.tex`, or on Overleaf by uploading the zip directly and setting **Menu → Compiler → XeLaTeX**.
3. See each theme's own `README.md` (inside the zip) for its specific macros, palette, and font setup.

## License

Licensed under [CC BY-NC 4.0](LICENSE.md) — free to use and adapt with attribution, **non-commercial use only**. For commercial licensing, contact hi@priyanshsaxena.com.

These are original designs, not affiliated with or endorsed by any company, game, show, or product they may evoke.
