# A Gentle Introduction to Relativistic Dynamics And Electromagnetism

This is a long paper (or short book) on relativistic dynamics and electromagnetism that I’ve been working on for some time, written in LaTeX. Feel free to download the [PDF](https://drive.google.com/file/d/0BzbijOFcLYkTSWJ5R0s5U1ZMYWM/view?usp=sharing&resourcekey=0-VMvPOHPxyPgNhBhy-7ZcDQ). Disclaimer: I am not a physicist.

Note to self: the `nomencl` package is used to create the List of Symbols, so compiling the PDF requires first running `pdflatex` on the document, then running the terminal command below, and finally running `pdflatex` again.

```bash
makeindex mass-energy-equivalence.nlo -s nomencl.ist -o mass-energy-equivalence.nls
```
