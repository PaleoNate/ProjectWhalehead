# Project Whalehead

## Introduction

Project Whalehead (arbitrarily named for the shoebill genus) is a GitHub repository for a project comparing phylogenetic outputs of Bayesian and parsimony analysis of morphological character matrices using stratigraphic congruence metrics. The authors are April Wright and Graeme Lloyd and the repository also serves as supplementary information for the published version.

## What is here?


* Data
** RevBayesOutput MISSING
* Ages
* Figures
* R
* man
* rb_scripts
* vignettes
* DESCRIPTION
* NAMESPACE
* Outline.md
* README.md
* TableS1.md
* refs.bib




## Data sources

Primary data source: [graemetlloyd.com](http://www.graemetlloyd.com/matr.html) (as at 05/07/19).

This includes:

1. #NEXUS file (character-taxon matrix inclusive of ASSUMPTIONS block).
2. Sample of most parsimonious trees.
3. XML files with dependency and taxonomic reconciliation data.

But does not include:

1. Temporospatial data for tips (to come from [paleobiodb.org](https://paleobiodb.org/#/)).
2. Bayesian inference posterior samples.

## Data filtering

Following Wright et al. (2016) the following filtering was applied:

1. Text.
2. Text.
3. Text.

Plus:

1. Removing data sets with polymorphisms.
2. Removing data sets with molecular components.

## Age data

GRAEME TO ADD.

## Bayesian inference settings

APRIL TO ADD.

## References

Wright, A. M., Lloyd, G. T. and Hillis, D. M., 2016. Modeling character change heterogeneity in phylogenetic analyses of morphology through the use of priors. Systematic Biology, 65, 602-611.
