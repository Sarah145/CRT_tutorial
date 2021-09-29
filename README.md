## Single-cell RNA-seq analysis workshop

This repository contains all the material needed for the scRNA-seq data analysis tutorial. Before the tutorial, run the following commands from the terminal to download all the necessary data and set up a conda environment with all the R packages we'll be using.

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

   