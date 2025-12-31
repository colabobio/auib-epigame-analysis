# Analysis of AUIB epigame dataset

Analysis of the epigame data. First, download the data from the following zenodo repository:

https://zenodo.org/records/18108261

Then, tun the following Jupyter notebooks in order:

* 1-data-parsing
* 2-descriptive-statistics
* 3-data-models
* 4-network-analysis

## Creating conda environment

The file requirements.txt list all the packages needed by these notebooks. It is recommended to use conda to create an environment with all this packages. 

First, install miniconda (or anaconda):

https://docs.anaconda.com/free/miniconda/

Clone this repo:

```
git clone https://github.com/colabobio/auib-epigame-analysis.git
```

And the create the environment installing the listed requirements from the conda-forge channel:

```
cd auib-epigame-analysis
conda create --name auib --file requirements.txt --channel conda-forge
```