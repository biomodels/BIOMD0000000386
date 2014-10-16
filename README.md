# BIOMD0000000386: 

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000386.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000386.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000386 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**A quantitative comparison of Calvin–Benson cycle models**   
Anne Arnold, Zoran Nikoloski _Trends in Plant Science_ 2011 Oct 14.
[22001849](http://www.ncbi.nlm.nih.gov/pubmed/22001849) ,  
**Abstract:**   
The Calvin-Benson cycle (CBC) provides the precursors for biomass synthesis
necessary for plant growth. The dynamic behavior and yield of the CBC depend
on the environmental conditions and regulation of the cellular state. Accurate
quantitative models hold the promise of identifying the key determinants of
the tightly regulated CBC function and their effects on the responses in
future climates. We provide an integrative analysis of the largest compendium
of existing models for photosynthetic processes. Based on the proposed
ranking, our framework facilitates the discovery of best-performing models
with regard to metabolomics data and of candidates for metabolic engineering.

**Note:** Model of the Calvin cycle with focus on the RuBisCO reaction by Sharkey et al. (2007, [DOI:10.1111/j.1365-3040.2007.01710.x](http://dx.doi.org/10.1111/j.1365-3040.2007.01710.x) ). 

The parameter values are partly taken from Farquhar et al. (1980,
[DOI:10.1007/BF00386231](http://dx.doi.org/10.1007/BF00386231) ) and Medlyn et
al. (2002, [DOI:10.1046/j.1365-3040.2002.00891.x](http://dx.doi.org/10.1046/j.
1365-3040.2002.00891.x) ). The initial metabolite values are chosen from the
data set of Zhu et al. (2007,
[DOI:10.1104/pp.107.103713](http://dx.doi.org/10.1104/pp.107.103713) ). A
detailed description of all modifications is given in the model described by
Arnold and Nikoloski (2011,
[PMID:22001849](http://www.ncbi.nlm.nih.gov/pubmed/22001849) .


