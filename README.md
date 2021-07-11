# mw-miallot2021

This repository contains code for the analyses from the review "Metabolic landscapes in sarcomas". The workflow is written as a [Snakemake](https://snakemake.readthedocs.io/en/stable/) wokflow which retrieve [TCGA](https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga) datasets that are then analysed in a [Bookdown](https://bookdown.org/yihui/bookdown/) report. It can be compiled on a Linux environment with conda installed, following these instructions:

```
git clone git@github.com:guillaumecharbonnier/mw-lib.git
git clone git@github.com:guillaumecharbonnier/mw-miallot2021.git
mw-miallot2021/src/bash/run_snakemake_bookdown.sh
```

Please open an issue on [github](https://github.com/guillaumecharbonnier/mw-miallot021/issues) if you have any questions.
