# Journal club: Brady (2023), "Poverty, not the poor"

Slides for a 10-minute journal club presentation of

> Brady, D. (2023). Poverty, not the poor. *Science Advances*, 9(34), eadg1469.
> https://doi.org/10.1126/sciadv.adg1469

- `slides/poverty_not_the_poor.qmd` — the deck (Quarto revealjs, self-contained html)
- `index.qmd`, `_quarto.yml` — a minimal site around it, rendered to `docs/` and served by GitHub Pages at https://janpfander.github.io/journal_club_poverty/
- `slides/figures/` — the paper's figures, extracted from the PDF (Fig. 1–9)
- `references.bib` — written by `zotero_bib.py cite`, never by hand

Render:

```sh
quarto render
open docs/slides/poverty_not_the_poor.html
```

Commit `docs/` to publish.

Press `S` in the browser for speaker notes. The deck style follows the
`quarto-presentations` skill in `~/.claude/skills/`.
