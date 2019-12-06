# Thesis MSc. Data Science and Society
## Accuracy Optimization of Social Touch Classification
Last updated: December 6, 2019

This document contains general information and instructions about the required files for the thesis "Accuracy optimization of social touch classificationthrough a CoST-HAART dataset aggregation". The study was conducted by Tomas Pittens.

### Content

- 1_preprocessing.ipynb
- 2_models.ipynb
- model_results.ipynb
- input
  - 

### Running the .IPYNB files

An IPYNB file is a notebook document used by Jupyter Notebook. To run the code in these documents, the file must be loaded into a Jupyter Notebook environment. Because some calculations require a GPU, it is advisable to use the free and online Google Colab environment (https://colab.research.google.com/). 

### Data

The CoST data is automatically imported into the IPYNB 1_preprocessing file via a hyperlink. However, this was not possible for the HAART dataset. The data (downloadable via http://www.cs.ubc.ca/labs/spin/data) must be unzipped and placed into a 'data' folder.

The preprocessing output is stored in this repository in the 'input' folder. This is because it will be used as input for the models in the 2_models.ipynb file.

### Installation

