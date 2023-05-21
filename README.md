> :warning: During 2023 this repo is planned to be restructured and tidied up.
> A number of notebooks are currently lacking commentary and will be updated gradually.

# Petrophysics-Python-Series
This series of Jupyter Notebooks take you through various aspects of working with Python and Petrophysical data.
A number of the notebooks are accompanied by either a Blog Post or a Medium article.

**Check out the binder button below** if you want to run these notebooks without needing to download them or install Python.  

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andymcdgeo/Petrophysics-Python-Series/master)  

For citation please use: McDonald, A., 2021, Python and Petrophysics Notebook Series. https://github.com/andymcdgeo/Petrophysics-Python-Series
[![DOI](https://zenodo.org/badge/256027932.svg)](https://zenodo.org/badge/latestdoi/256027932)


## Series Contents:

1. Loading and Displaying Well Data  - [Medium Link](https://andymcdonaldgeo.medium.com/loading-and-displaying-well-log-data-b9568efd1d8)
2. Displaying a Well Plot with matplotlib  
3. Displaying histograms and crossplots  
4. Displaying core data and deriving a regression  
5. Petrophysical Calculations  
6. Displaying Formations on Log Plots  
7. Working with LASIO
8. Curve Normalization - [Medium Link](https://towardsdatascience.com/petrophysics-gamma-ray-normalization-in-python-9a67a335dbd)
9. Visualising Data Coverage - Multi Well - [Medium Link](https://towardsdatascience.com/visualising-well-data-coverage-using-matplotlib-f30591c89754)
10. Exploratory Data Analysis with Well Log Data - [Medium Link](https://towardsdatascience.com/exploratory-data-analysis-with-well-log-data-98ad084c4e7)
11. Deriving a Porosity - Permeability Relationship - [Medium Link](https://towardsdatascience.com/porosity-permeability-relationships-using-linear-regression-in-python-eef406dc6997)
12. Enhancing Log Plots With Plot Fills - [Medium Link](https://towardsdatascience.com/enhancing-visualization-of-well-logs-with-plot-fills-72d9dcd10c1b)
13. Displaying LWD Image Data - [Medium Link](https://andymcdonaldgeo.medium.com/displaying-logging-while-drilling-lwd-image-logs-in-python-4babb6e577ba)
14. Displaying Lithology Data on a Well Log Plot Using Python [Medium Link](https://andymcdonaldgeo.medium.com/displaying-lithology-data-using-python-and-matplotlib-58b4d251ee7a)
15. Loading Multiple LAS Files [Medium Link](https://towardsdatascience.com/loading-multiple-well-log-las-files-using-python-39ac35de99dd)
16. Adding Formation Data to a Log Plot [Medium Link](https://towardsdatascience.com/adding-formation-data-to-a-well-log-plot-3897b96a3967)
17. Working with DLIS Files Using DLISIO - [Medium Link]()
18. How to use Unsupervised Learning to Cluster Well Log Data using Python - [Medium](https://towardsdatascience.com/how-to-use-unsupervised-learning-to-cluster-well-log-data-using-python-a552713748b5)
19. Exploring Well Log Data Using the Welly Python Library - [Medium Link](https://andymcdonaldgeo.medium.com/exploring-well-log-data-using-the-welly-python-library-5e808cd3137b)
20. Creating a Core Data Dashboard Using Matplotlib's subplot2grid functionality - [Medium Link](https://towardsdatascience.com/scatterplot-creation-and-visualisation-with-matplotlib-in-python-7bca2a4fa7cf)
21. Identifying Outliers in Well Log Data Using Boxplots in Matplotlib - [Medium Link](https://andymcdonaldgeo.medium.com/creating-boxplots-of-well-log-data-using-matplotlib-in-python-34c3816e73f4) 


## Data Sets Used

Data for each workbook can be found with this repo's Data sub folder.

All data has been obtained from publicly accessible data repositories. Details for the origins of each file is presented below.

#### Equinor Volve Dataset
- 15_9-19.csv
- 15_9-19A-CORE.csv
- 15-9-19_SR_COMP.LAS
- 15_19_F1B_WLC_PETRO_COMPUTED_INPUT_1
- VolveWells.csv

Information on the Volve dataset can be found at:
https://www.equinor.com/en/what-we-do/norwegian-continental-shelf-platforms/volve.html

#### NLOG - Netherlands Well Log and Data Repository
- L0509WellData.csv
- L0509_comp.las
- P11-A-02_Composite_MEM_Image_NF.las
- P11-A-02_SURV.csv
- NLOG_LIS_LAS_7857_FMS_DSI_MAIN_LOG.DLIS

Dutch offshore and onshore well data can be accessed from:
https://nlog.nl/en

#### Force 2020 XEEK
- xeek_train_subset.csv

Data was provided by the FORCE Machine Learning competition with well logs and seismic 2020”  
Bormann P., Aursand P., Dilib F., Dischington P., Manral S. 2020. 2020 FORCE Machine Learning Contest. https://github.com/bolgebrygg/Force-2020-Machine-Learning-competition

FORCE: Machine Predicted Lithology
https://xeek.ai/challenges/force-well-logs/overview

## Suggestions
If you have any suggestions of what you would like to see, please raise a new issue and I will put something together.
