# Anaphora and Ambiguity - An Analysis of Disagreement in Anaphoric Annotation

This repository is a companion page for the Master's thesis, containing the supplementary material and necessary appendices to replicate and reproduce the study and its results.

The study was carried out by Lukas Beiske, University of Konstanz, Department of Linguistics, 2024.

## Quick Links

* [Rule Based Process Script (R)](scripts/RuleBasedFramework.Rmd)
* [Descriptive Statistics Script with visualisations (HTML)](scripts/DescriptiveStatisticsVisual.html)

## Study Design

![study-design](documentation/study-design.png)

## Note

In order to run the R scripts and perform the rule based process, the necessary Corpora (i.e., ARRAU and PD) need to be loaded. To do so, customize the paths as in the example below:

```r
#path to input folders with XML files
folders_xml <- c("../Statistics/data/ARRAU/RST",
                 "../Statistics/data/ARRAU/Trains_91",
                 "../Statistics/data/PD/gutenberg",
                 "../Statistics/data/PD/wiki")
```

## Repository Structure
This repository is organised along to the study design.

```
AnaphoricAmbiguity_MAThesis
    .
    |
    |--- documentation/
        |
        |--- study-design.pdf
                The used methodlogy in the theis.
    |--- scripts/
        |
        |--- test.md
                The used methodlogy in the theis.
        |--- test.md
                The used methodlogy in the theis.
    |--- figures/
        |
        |--- test.md
                The used methodlogy in the theis.
                    
```
