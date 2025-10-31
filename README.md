# Manuscript template

![Typst](https://img.shields.io/badge/typst-239DAD.svg?style=for-the-badge&logo=typst&logoColor=white)
[![Static
Badge](https://img.shields.io/badge/Quarto-74AADB.svg?style=for-the-badge&logo=Quarto)](https://quarto.org)

This is a Typst-for-Quarto template for academic manuscripts.

**What's the motivation?** I'm not a fan of the manuscript style that centers
the title, puts authors in a column grid, and then crams all that onto the first
page with the introduction. I prefer a separate title page. It's also nice to
include keywords and the target journal, so co-authors and others know how to
evaluate the paper.

Also, this whole typst thing is pretty awesome. May we never write LaTeX again!

## Installing

``` bash
quarto use template kbvernon/typst-manuscript
```

This will install the format extension and create an example qmd file that you
can use as a starting place for your document.

## Example

You can find an example of the rendered template here:
[template.pdf](template.pdf).

## Caveat Emptor

I didn't really design this with the intention that anyone would use it but me,
which is why I hardcoded nearly everything into *typst-template.typ*.