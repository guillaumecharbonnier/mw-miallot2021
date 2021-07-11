# mw-miallot2021

This repository contains code for the analyses from the review "Metabolic landscapes in sarcomas". The workflow is written as a Bookdown report.

The workflow is written as a Snakemake wokflow which retrieve TCGA datasets that are then analysed in a Bookdown report. It can be compiled on a Linux environment with conda installed, following these instructions:

```
git clone git@github.com:guillaumecharbonnier/mw-lib.git
git clone git@github.com:guillaumecharbonnier/mw-belhocine2021.git
mw-miallot2021/src/bash/run_snakemake_bookdown.sh
```

Please open an issue on [github](https://github.com/guillaumecharbonnier/mw-miallot021/issues) if you have any questions.
