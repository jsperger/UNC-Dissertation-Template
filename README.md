# UNC Dissertation Template

This repository is a lightly updated version of recent dissertation templates. To quote an earlier author,

> [T]his repository is intended to serve as an open and evolving resource going forward. If you use this template for your own dissertation in future years, > please consider forking this repository or submitting a pull request with your changes so that it can stay up to date for future PhD students!

## Template Family Tree
[Brian G. Forester](https://github.com/bgforester/UNC-Dissertation-Template)
 [Chelsea Estancona](https://clestancona.wixsite.com/chelseaestancona)
 [Björn B. Brandenburg](https://people.mpi-sws.org/~bbb/)'s UNC dissertation [LaTeX template](https://www.cs.unc.edu/~bbb/)
 
# Changelog
## This repository
 - Replace deprecated package `times` with `mathptmx`. Remove deprecated package `textcomp` which has been incorporated into $\LaTeX$ and requires no replacement. 
## Dr. Forester
Updates following dissertation approval in March 2023:
- Updated `layout.tex` to include option for block centering chapter titles
- Updated `preamble.tex` and `references.tex` to include syntax for biblatex-chicago users
- Updated `macros.tex` to include option for restarting hypothesis counter at each chapter; useful if doing three-paper dissertation

## Dr. Estancona
Changes I've made to Björn's template include:
- Making main title standard font size
- Making all chapter, section, and sub(sub)section headings standard font size
- Centering the Table of Contents header
- Making footnotes only 1pt smaller than body text
- Placing chapter numbers and titles on the same line
- Setting 1" top margins for appendix headers
- Removing some of the more bespoke code related to terms and figures in his dissertation from `macros.tex`
- Switching from natbib to regular BibTeX
- Switching from `amsthm` the `ntheorem`
- Adding a comment function at the end of `macros.tex` to allow color highlighted notes set off by brackets in rendered PDFs
