# Overview

This repository contains the statistical analysis code used in the paper “**Geographical Disparities in Navigating Rejection in Science Drive Disparities in its File Drawer**", by <ins>Hong Chen, Chris Rider, David Jurgens and Misha Teplitskiy</ins>.

The code provided here reproduces the primary analyses, figures, and tables included in the paper.

This is the abstract of our paper:
> Scientific progress relies on making research contributions public, typically through journal publication, enabling others to build on them. However, publishing often requires overcoming one or more rejections. This study examines how scientists' differential responses to manuscript rejection shape both published knowledge and the “file drawer” of unpublished research. Analyzing 126K manuscripts rejected by 62 STEM journals published by the Institute of Physics Publishing, we document several new empirical facts. Controlling for manuscript quality (proxied by peer review recommendations) and comparing authors from Western and non-Western countries, we find that authors based in Western countries are 5.9% more likely to publish rejected manuscripts elsewhere, publish 25 days faster, revise 6% less, and change co-authors 11.6% less. Although exploratory surveys of rejected authors are inconclusive, our empirical analyses implicate geographic differences in access to procedural knowledge – how to interpret feedback, revise a manuscript, and resubmit elsewhere. Post-rejection outcomes are better when corresponding authors are likely to have better access to procedural knowledge, such as prior publishing experience and Western co-authors. These findings imply that the “file drawer” contains a disproportionate number of ideas from non-Western countries, partly due to disparities in procedural knowledge.

# Repository Structure

- data/: Directory for anonymized data files used in the analysis (upon request).
- scripts/: Contains necassary scripts to reproduce statisticaly analysis
- README.md: Instructions for reproducing the analyses and a brief overview of the project.

# Requirements and Reproducibility

The code is organized in jupyeter notebook to allow for quick reproduction of the study’s statistical analysis and  result visualization.

A full list of dependencies can be found in environment.yml. To set up the environment with the necessary packages, follow these steps:

'''
conda env create -f environment.yml
conda activate [environment_name]
'''
