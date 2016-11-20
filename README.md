# bookdown minimal template

This is a bookdown minimal template for Japanese language. This based [rstudio/bookdown-demo](https://github.com/rstudio/bookdown-demo) repository. 

## modified points

- set "pandoc args" for Japanese heading.
- set "latex_engine: lualatex".
- set "output_dir" to "docs".
- set font "IPAGothic" into "pdf_book".

## Notice

If you want use multibyte text on ggplot2 by "bookdown::pdf_book()", you might set Rchunk Option 'dev="cairo_pdf"'. Because pdf_book set 'dev="pdf()"' as a default value. 

## contact

Please mention to [@kazutan](https://twitter.com/kazutan) or issue the this repository.