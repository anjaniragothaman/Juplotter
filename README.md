# Juplotter
__Vizualization tool built using ipywidgets and Jupyter notebook for data exploration__


This code assumes that you have installed anaconda and have python version 3.6 (when the code/document was written) and you use this on Jupyter notebook.

Link to download anaconda:
[MacOS](https://www.anaconda.com/download/?lang=en-us#macos) | [Windows](https://www.anaconda.com/download/#windows)

__Input data: xlsx sheet__
_Data arrangement requirements_:
* Colum 1 - Observation ID
* A column with header 'Dx' - typically has the diagnosis classification
 * Dx can be coded either as a numeric or string
 * If coded as numeric, the code will ask for the corresponding meaning per code 
* If longitudianl data is present, it is best to store each timepoint observation as a row
