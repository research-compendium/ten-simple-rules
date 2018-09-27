# Ten simple rules for publishing a research compendium

A sketch for an article, contributions welcome!

## Motivation & challenges

"Ten simple rules..." articles are quite popular series of articles at [PLOS](https://www.plos.org/).
Find them all at https://collections.plos.org/ten-simple-rules or [via Google Scholar](https://scholar.google.de/scholar?q=ten%20simple%20rules%20for).

As a sister-article to the preprint "How to Read a Research Compendium" ([`arXiv:1806.09525`](https://arxiv.org/abs/1806.09525)) targeting readers (and indirectly authors), this article **supports authors** in making sure their research compendium is soundly structured and composited.
As a side effect, it might be helpful for journals/editors who need to write author guidelines.

**Questions and challenges**:

- [Is this possible to do across all domains, data types, and programming languages?](#2)
- How to relate to language or domain specific articles (that might be much more useful for authors), such as [this one for R](https://doi.org/10.1080/00031305.2017.1375986)?
- [Should _Philip E. Bourne_ become a co-author?](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003858#s6)

And of course, regularly check if the manuscript is in line with [_"Ten Simple Rules for Writing a PLOS Ten Simple Rules Article"_](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003858#s6).

## Technical

The document is an [R Markdown](https://rmarkdown.rstudio.com/) file best edited with [RStudio](https://www.rstudio.com/products/RStudio/).

You can render an HTML preview in R with

```r
rmarkdown::render("manuscript.Rmd")
```

## Contributions

Contributions are more than welcome, they are much needed!
This article can only "fly" if it has valuable content, is witty and well-written, and builds upon wide experience - none of which is possible without collaboration.

You can start by checking out the current draft in `manuscript.Rmd`, see if there are [issues](https://github.com/research-compendium/ten-simple-rules/issues) to reply to or, even better, to solve, or have a go at the "challenges and questions" above.

If you want to update the manuscript file, please fork this repository, make your changes, and send a pull request to the `master` branch.

## License

This manuscript is published and contributions fall under a Creative Commons Attribution 4.0 International ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)) license.

![CC BY 4.0 button](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)
