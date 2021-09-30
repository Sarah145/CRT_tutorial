## Single-cell RNA-seq analysis workshop

This repository contains all the material needed for the scRNA-seq data analysis tutorial. Download the repository either by clicking the green 'Code' button above or by cloning it  from the command line using `git clone https://github.com/Sarah145/CRT_tutorial`.  

**If you're running Ubuntu** and have conda installed you can use the .yml file to create a conda environment which should have all the necessary packages installed. 

1. Clone this repository and navigate into it

   ```bash
   git clone https://github.com/Sarah145/CRT_tutorial
   cd CRT_tutorial
   ```

   :watch: < 2mins

   

2. Create conda environment (assuming you have [Anaconda](https://www.anaconda.com/distribution/#download-section) installed) from the .yml file and activate it

   ```bash
   conda env create -f scRNA_tutorial.yml
   conda activate scRNA_tutorial
   ```

   :watch: 5-10 mins

   

3. Start an R studio session within this environment

   ```bash
   rstudio
   ```

   

**If you're running Windows**, I have no idea whether the conda approach will work but if you just open Rstudio and install the following R packages, hopefully everything will run smoothly!

- tidyverse (CRAN)
- Seurat (CRAN)
- clustree (CRAN)
- ggsignif (CRAN)
- clusterProfiler (Bioconductor)
- org.Hs.eg.db (Bioconductor)
- ggrepel (CRAN)
- patchwork (CRAN)