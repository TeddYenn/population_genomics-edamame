---
title: "Population Genomics"
subtitle: "For Selection Footprints in Edamame"
author: "Yen-Hsiang (Teddy) Huang"
date: "2025-04-14"
knit: "bookdown::render_book"
site: bookdown::bookdown_site
output: bookdown::bs4_book
documentclass: book
bibliography: [book.bib]
biblio-style: apalike
link-citations: true
links-as-notes: true
colorlinks: true
github-repo: TeddYenn/GWAS_RICE
cover-image: 
url: https://github.com/TeddYenn/population_genomics-edamame
description: "A guide to selection footprints analysis for enhancing productivity in Taiwanese edamame through core collection framework"
editor_options: 
  markdown: 
    wrap: 72
---



# Welcome! {#sec-welcome-to-gwas-tutorial .unnumbered}

```{=html}
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-LKV6J2QECN"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-LKV6J2QECN');
</script>
```
#### 📢 **Key message:** {.unnumbered}

> Our core collection-based pipeline unveils distinctive selection
> patterns between vegetable and grain soybeans, identifying selection
> footprints and favorable alleles in vegetable soybeans, and guiding
> genomic insights for enhanced breeding strategies.

#### 📍 **Keywords:** {.unnumbered}

> vegetable soybean, population structure, diversity and
> differentiation, genomic scans, core collection, selection footprint.

------------------------------------------------------------------------

#### **⚠️ NOTE: Some data in this book is unpublished; therefore, certain results may be uncompleted, simulated, and some plots may appear blurred.** {.unnumbered}

This work by Yen-Hsiang (Teddy) Huang is licensed under a [GNU General
Public License](https://www.gnu.org/licenses/gpl-3.0.html.en).

# Preface {.unnumbered}

This GitHub page presents an academic-style report and *hands-on R &
PLINK instructions (TO BE DONE)* on the analysis of selection footprints
in Taiwanese edamame, conducted as part of my Master's research under
the supervision of Dr. Chung-Feng Kao. Although the study was completed
and produced valuable insights, constraints related to the availability
of the genotypic data have rendered the work ineligible for formal
publication. 😢

This book was written in [RStudio](http://www.rstudio.com/ide/) using
[bookdown](http://bookdown.org/). The
[website](https://teddyenn.github.io/GWAS_RICE/) is hosted via GitHub
under [TeddYenn's repository.](https://github.com/TeddYenn)

If you have any questions or suggestions, feel free to reach out via
email at [teddyhuangyh\@gmail.com](mailto:teddyhuangyh@gmail.com) (Teddy
Huang).

## Outline {.unnumbered}

-   **Chapter** \@ref(sec-introduction) **Introduction**
-   **Chapter** \@ref(sec-materials-and-methods) **Materials and
    methods**
-   **Chapter** \@ref(sec-results) **Results**
-   **Chapter** \@ref(sec-discussion) **Discussion**
-   **Chapter** \@ref(sec-reference) **Reference**

## Acknowledgements {.unnumbered}

I am deeply grateful for the contributions, support, and perspectives of
individuals and organizations that have helped move this project
forward.
