Background

This repository applies a Python Matplotlib to visualize real-world pharmaceutical data. The data is sourced from Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pharmaceuticals specialize in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.


The analysis used complete data from their most recent animal study in two datasets in CSV format. Data set one is Mouse_metadata.csv, which includes 249 mice identified data with SCC tumor growth were treated through various drug regimens, and their Sex, Age_months, and Weight (g) were identified. The other dataset is the Study_results.csv file which includes the study results in each columns Mouse I, Timepoint, Tumor Volume (mm3), and Metastatic Sites.

The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. The analysis also generated all the tables and figures needed for the study's technical and top-level summary report. For this analysis, both datasets were imported, merged, cleaned, and the aggregate data displayed into Python Pandas data frames, visualized in Matplotlib, and other libraries used to make a statistical analysis. The project is conducted in Jupyter notebook to showcase and communicate the analysis report the following link is created: Jupyter Notebook Viewer.

Observable Trends

The bar graph showed that the Drug Regimen Capomulin has the maximum mice number (230), and Zoniferol has the smaller number of mice (182). By removing duplicates, the total number of mice is 248. The total count of mice by gender also showed that 124 female mice and 125 male mice.
The correlation between mouse weight and average tumor volume is 0.84. It is a strong positive correlation; the average tumor volume also increases when the mouse weight increases.
The regression analysis helped us understand how much the average tumor volume (dependent variable) will change when the weight of mice changes (independent variables). The R-squared value is 0.70, which means 70% of the model fits the data, which is pretty good to predict the data from the model. Higher R-squared values represent more minor differences between the observed data and the fitted value. 70% of the model explains all of the variations in the response variable around its mean.
From the selected treatments Capomulin and Ramicane reduce the size of tumors better.
