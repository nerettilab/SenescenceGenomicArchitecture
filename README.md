# SenescenceGenomicArchitecture

Dalgarno et al. (In preparation)

High-resolution Hi-C reveals increased chromatin looping with senescence associated with hypomethylation and retrotransposon derepression

Code to create figures can be found in this Jupyter Notebook (analysis_and_figures.ipynb).

Data to create figures can be found on Zenodo ().

To install:
1. Clone the github repository, download data from Zenodo.
2. Setup the conda environment with: conda env create -f hic_env.yml. Make sure to edit the last line of the yml file accordingly. Activate the environment.
3. Install the required versions of cluster profiler in R by running: 
install.packages(pkgs = "https://www.bioconductor.org/packages/3.17/bioc/src/contrib/clusterProfiler_4.8.3.tar.gz", repos = NULL)
install.packages(pkgs = "https://www.bioconductor.org/packages/3.17/data/annotation/src/contrib/org.Hs.eg.db_3.17.0.tar.gz", repos = NULL)
install.packages(pkgs = "https://www.bioconductor.org/packages/3.17/data/annotation/src/contrib/GO.db_3.17.0.tar.gz", repos = NULL)
4. Set up R to run with jupyter: R -e ‘IRkernel::installspec()’
5. Set up bash to run with jupyter: python -m bash_kernel.install
