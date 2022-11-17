# Chemometric data analysis tutorials - LC-MS profiles from human urine biofluid study

This repository contains tutorials on multivariate analysis of metabolic profiling datasets: 
 - Discrimination of biological sex from urinary metabolic profiles using Partial Least Squares – Discriminant Analysis.ipynb: Discrimination of the urine biofluid metabolic profiles based on the participant's sex with PLS-DA models.
 - Discrimination of biological sex from urinary metabolic profiles using Random Forests.ipynb: Similar analysis of the above, but using a Random Forest Classifier instead
 
To run these tutorials download the contents of this repository and run the Jupyter Notebooks.

All the data required to run these notebooks is provided on the 'Data' folder. Detailed information about this cohort and other available phenotypic measurements can 
be found in Lovestone *et al*<sup>1</sup> and the ANMERGE repository<sup>2</sup>, which can be accessed
via the [Sage BioNetworks portal](https://doi.org/10.7303/syn22252881).
Information about the metabolic profiling experiments can be found in the study's 
MetaboLights entry - [MTBLS719](https://www.ebi.ac.uk/metabolights/MTBLS719).

## Installation instructions:
To run these tutorials, first download and install the latest Anaconda Python 3.x distribution available. 
The following packages also need to be installed:
 - plotly: Available via conda (open an Anaconda prompt and type "conda install plotly")
After installing plotly, either clone this repository or download as .zip file. Access the notebooks contents via the Jupyter notebook environment. 

All other dependencies required to run the tutorials (pyChemometrics toolbox) are bundled with the repository, and no specific installation is required. 

For more information on how to use Jupyter notebooks see [Using the Jupyter notebook](https://docs.anaconda.com/ae-notebooks/user-guide/basic-tasks/apps/jupyter/)

## References

    [1] Lovestone, S., Francis, P., Kloszewska, I., Mecocci, P., Simmons, A., Soininen, H., … Ward, M. (2009). AddNeuroMed - The european collaboration for the discovery of novel biomarkers for alzheimer’s disease. In Annals of the New York Academy of Sciences. https://doi.org/10.1111/j.1749-6632.2009.05064.x
    [2] Birkenbihl, C., Westwood, S., Shi, L., Nevado-Holgado, A., Westman, E., Lovestone, S., & Hofmann Apitius, M. (2020). ANMerge: A comprehensive and accessible Alzheimer’s disease patient-level dataset. MedRxiv. https://doi.org/10.1101/2020.08.04.20168229

