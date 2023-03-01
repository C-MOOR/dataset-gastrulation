<img src="https://github.com/C-MOOR/c-moor.github.io/blob/master/img/cmoor_logo.png" height=120>

# Analyzing Gastrulation scRNA-seq Using R

- [Introduction to scRNA-seq](#introduction-to-scrna-seq)
- [Overview of mouse gastrulation scRNA-seq data](#overview-of-mouse-gastrulation-scrna-seq-data)
- [Evaluate the metadata for the cells in the scRNA-seq gastrulation dataset](#evaluate-the-metadata-for-the-cells-in-the-scrna-seq-gastrulation-dataset)
- [Evaluate one individual sample to get a feel for the gastrulation gene expression dataset](#evaluate-one-individual-sample-to-get-a-feel-for-the-gastrulation-gene-expression-dataset)
- [Use the full gastrulation dataset to explore hypotheses](#use-the-full-gastrulation-dataset-to-explore-hypotheses)
- [Subset certain cell populations for further analysis from the full gastrulation dataset](#subset-certain-cell-populations-for-further-analysis-from-the-full-gastrulation-dataset)

## Introduction to scRNA-seq
  - Introducing scRNA-seq [[slides](https://docs.google.com/presentation/d/1eGY6k9cklSrb1NkT4c2Q3Uo3m_Zhs-xw07q_jXjQGuY/edit#slide=id.p1)]
  - Introducing scRNA-seq Data and R Notebooks (Assignment / Discussion) [[assignment](https://docs.google.com/document/d/12uwz7L-W0wZwwcFdWRr3yPZ1ISnnXOM4-1de9OY2B_M/edit#heading=h.9g3iu0iw5wkd)][[Rmd](https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/rmd/mouse_gastrulation.Rmd)][[html](http://htmlpreview.github.io/?https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/html/mouse_gastrulation.html)]

## Overview of mouse gastrulation scRNA-seq data
  - [Pijuan-Sala et al. (Nature 2019)](https://pubmed.ncbi.nlm.nih.gov/30787436/) generated scRNA-seq data during mouse gastrulation. In this module, we will learn to analyze this data ourselves using R.

<figure><img src="https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/images/41586_2019_933_Fig1_HTML.webp" style="width:70%"><figcaption align = "center"><b>Fig. 1: A single-cell resolution atlas of mouse gastrulation and early organogenesis. a, Overview of embryonic developmental time points sampled, alongside corresponding Theiler stages (TS9–TS12) and Downs and Davies stages. Numbers indicate days post-fertilization. PrS, pre-streak; ES, early streak; MS, mid-streak; LS, late streak; OB, neural plate no bud; EB, neural plate early bud; LB, neural plate late bud; EHF, early headfold; LHF, late headfold; 1–7S, 1–7 somites. b, Representative images of sampled embryos. Scale bars, 0.25 mm. c, Uniform manifold approximation and projection (UMAP) plot showing all the cells of the atlas (116,312 cells). Cells are coloured by their cell-type annotation and numbered according to the legend below. Def., definitive; ExE, extra-embryonic; prog., progenitor. d, Fraction of cell type per time point, displaying a progressive increase in cell-type complexity throughout our sampling. Figure and legend from Pijuan-Sala et al. (Nature 2019).</b></figcaption></figure>

## Evaluate the metadata for the cells in the scRNA-seq gastrulation dataset
  - Explore Mouse Gastrulation Metadata (Assignment / Discussion) [[r-notebook](https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/rmd/gastrulation_Meta_230202.Rmd)][[html](https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/html/gastrulation_Meta_230202.html)]

## Evaluate one individual sample to get a feel for the gastrulation gene expression dataset
  - Explore Mouse Gastrulation Data
    - Part 1 (Assignment / Discussion) [[r-notebook](https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/rmd/061622_mouse_gastrulation.Rmd)]
    - Part 2 (Assignment / Discussion) [[r-notebook](https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/rmd/061722_mouse_gastrulation_part2.Rmd)]
    - Part 3 (Assignment / Discussion) [[r-notebook](https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/rmd/062322_mouse_gastrulation_part3.Rmd)]

## Use the full gastrulation dataset to explore hypotheses
  - Explore Full Mouse Gastrulation Dataset (Assignment / Discussion) [[r-notebook](https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/rmd/Intro_full_gastrulation.Rmd)][[html](https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/html/Intro_full_gastrulation.nb.html)]

## Subset certain cell populations for further analysis from the full gastrulation dataset
  - Gastrulation Subsetting and Cross-Modal Plotting (Assignment / Discussion) [[r-notebook](https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/rmd/full_gastrulation_Subset.Rmd)][[html](https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/html/full_gastrulation_Subset.nb.html)]

## Perform pathway analysis on the enriched genes in your cell subset
  - Pathway Analysis (Assignment / Discussion) [[r-notebook]](https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/rmd/230202_Pathway.Rmd)][[html](https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/html/230202_Pathway.nb.html)]
  - Example: Neuroactive Ligand-Receptor Interaction
<img src="https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/images/hsa04080.pathview.png" height=500>
<img src="https://github.com/C-MOOR/dataset-gastrulation/blob/main/r-notebooks/images/hsa04080.png" height=500>

## Getting Help

Join the conversation in our [Slack](https://c-moor.slack.com) or [Discourse forums](https://help.c-moor.org)!

<hr>

C-MOOR is supported in part by [Carnegie Science Venture Grant](https://carnegiescience.edu/CSVgrants#section2) and [NSF DUE Award #2021013](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2021013)

<img src="https://github.com/C-MOOR/c-moor.github.io/blob/master/img/Carnegie_EMB_logo.png" height=35> <img src="https://github.com/C-MOOR/c-moor.github.io/blob/master/img/Clovis_logo_wide.jpg" height=35> <img src="https://github.com/C-MOOR/c-moor.github.io/blob/master/img/JHU_logo.jpg" height=35> <img src="https://idies.jhu.edu/wp-content/uploads/2020/03/cropped-IDIES_logo-500px.png" height=35>
