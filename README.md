create mamba environment 

```bash
mamba env create -f popgenDL_crashcourse.yml
```

make edits to `popgenDL_crashcourse.qmd`

```bash
quarto render popgenDL_crashcourse.qmd -o index.html
```

send PRs to gh-pages

