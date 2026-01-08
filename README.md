# A Gentle Introduction to Relativistic Dynamics And Electromagnetism

This is a long paper (or short book) on relativistic dynamics and electromagnetism that I’ve been working on for some time, written in LaTeX. Feel free to download the [PDF](https://drive.google.com/file/d/0BzbijOFcLYkTSWJ5R0s5U1ZMYWM/view?usp=sharing&resourcekey=0-VMvPOHPxyPgNhBhy-7ZcDQ). Disclaimer: I am not a physicist.

Note to self: when making changes to the List of Symbols (or when building the PDF for the first time after a fresh install, before the git-ignored `nomencl`-related `.nlo` and `.nls` files have been generated), compiling the PDF requires first running `pdflatex` on the document, then running the terminal command below, and finally running `pdflatex` again.

```bash
makeindex mass-energy-equivalence.nlo -s nomencl.ist -o mass-energy-equivalence.nls
```
