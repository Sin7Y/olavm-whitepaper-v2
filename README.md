# OlaVM Whitepaper V2

## Build
Please use `xelatex` to build document, if `reference.bib` is changed, please execute:
```shell
xelatex main.tex && biber main && xelatex main.tex && xelatex main.tex
```