# IWSM-MENSURA 2026 paper

This directory is the active CEUR-ART version of the paper. The previous
Springer LNCS project is preserved unchanged in `../original/`.

## Build

Run:

```sh
latexmk -pdf main.tex
```

The template requires the Libertinus font family. On Debian or Ubuntu it is
provided by `texlive-fonts-extra`.

## Submission checklist

- Use the one-column CEUR-ART layout; do not enable `twocolumn` or `hf`.
- Submit the generated PDF through the IWSM-MENSURA-2026 EasyChair portal.
- Regular papers must contain at least 10 standard pages, including references.
- Short papers must contain 5--9 standard pages, including references.
- Verify that the GenAI declaration lists every tool used by every author and
  its contribution using the CEUR-WS GenAI Usage Taxonomy.
- Keep the reproducibility link in the methodology and online appendix valid.
- Do not modify margins, type sizes, line spacing, or other CEUR-ART styling.

Official guidance:

- https://www.iwsm-mensura.org/2026-conference/call-for-paper/
- https://ceur-ws.org/HOWTOSUBMIT.html
- https://ceur-ws.org/GenAI/Policy.html
