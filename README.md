# Journal club: Brady (2023), "Poverty, not the poor"

Slides for a 10-minute journal club presentation of

> Brady, D. (2023). Poverty, not the poor. *Science Advances*, 9(34), eadg1469.
> https://doi.org/10.1126/sciadv.adg1469

- `index.qmd` — the deck (Quarto revealjs, self-contained html), rendered to `docs/index.html` and served by GitHub Pages at https://janpfander.github.io/journal_club_poverty/
- `figures/` — the paper's figures, extracted from the PDF (Fig. 1–9)
- `references.bib` — written by `zotero_bib.py cite`, never by hand

Render:

```sh
quarto render
open docs/index.html
```

Commit `docs/` to publish.

Press `S` in the browser for speaker notes. The deck style follows the
`quarto-presentations` skill in `~/.claude/skills/`.
