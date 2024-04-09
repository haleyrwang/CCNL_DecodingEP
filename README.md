# CCNL_DecodingEP
This repository contains code and data created in support of my project "Decoding Early Psychoses: Unraveling Stable Microstructural Features Associated with Psychopathology Across Independent Cohorts". All code was written in Python. 

## Prerequisites
Before you begin, ensure you have met the following requirements:

- Python 3.x installed
- Jupyter Notebook or JupyterLab installed

### Libraries Used
This project depends on several Python libraries. Ensure you have the following installed:

NumPy: For numerical computing.
Pandas: For data manipulation and analysis.
Matplotlib: For creating static, interactive, and animated visualizations in Python.
SciPy: For scientific and technical computing.
Scikit-learn: For machine learning and data mining.
NiBabel: For reading and writing neuroimaging data.
Seaborn: For making statistical graphics.

You can install all dependencies by running:
pip install numpy pandas matplotlib scipy scikit-learn nibabel seaborn


## Project Structure
The project is structured to follow a specific analysis workflow, especially for the HCPEP and MEND cohorts. Here's how to navigate through the notebooks in the recommended order:

### For Primary Cohort (HCPEP) Analysis:
- [HCPEP_PLS.ipynb](https://github.com/haleyrwang/CCNL_DecodingEP/blob/main/Code/HCPEP_PLS.ipynb): Starts with the Partial Least Squares (PLS) analysis for the EP dataset. This notebook is the entry point for understanding the primary patterns and relationships within the EP cohort data.
- [HCPEP_post_hoc.ipynb](https://github.com/haleyrwang/CCNL_DecodingEP/blob/main/Code/HCPEP_post_hoc.ipynb): Follows the PLS analysis with post-hoc assessments to delve deeper into the findings from the PLS analysis, focusing on the EP dataset.
- [HCPEP_figures.ipynb](https://github.com/haleyrwang/CCNL_DecodingEP/blob/main/Code/HCPEP_figures.ipynb): Generates visualizations and figures for the HCPEP study. This notebook is utilized after the PLS and post-hoc analyses to visually represent the findings.

### For Replication Cohort (MEND) Analysis:
Parallel to the EP/HCPEP analysis, the MEND study follows a similar pattern:
- [MEND_PLS.ipynb](https://github.com/haleyrwang/CCNL_DecodingEP/blob/main/Code/MEND_PLS.ipynb): Conducts the Partial Least Squares (PLS) analysis for the MEND dataset, serving as the foundation for understanding the dataset's key components.
- [MEND_post_hoc.ipynb](https://github.com/haleyrwang/CCNL_DecodingEP/blob/main/Code/MEND_post_hoc.ipynb): Provides a deeper dive into the MEND dataset findings, following up on the PLS analysis with post-hoc investigations.
- [MEND_figures.ipynb](https://github.com/haleyrwang/CCNL_DecodingEP/blob/main/Code/MEND_figures.ipynb): Creates figures and visual representations for the MEND study, showcasing the results from both the PLS and post-hoc analyses.

### Cross Cohort (External Validation) Analysis Steps:
After completing the specific study analyses for both EP/HCPEP and MEND, the project continues with the following steps that apply across the datasets:
- [Generate_overlay.ipynb](https://github.com/haleyrwang/CCNL_DecodingEP/blob/main/Code/Generate_overlay.ipynb): This notebook is used for generating overlay images for visualization purposes. It's typically run after the individual study analyses are completed.
- [Tract_classification.ipynb](https://github.com/haleyrwang/CCNL_DecodingEP/blob/main/Code/tract_classification.ipynb): Classifies tractography data based on predefined criteria. This notebook is useful for further detailed analysis following the overlay generation.
- [Cross_cohort_figures.ipynb](https://github.com/haleyrwang/CCNL_DecodingEP/blob/main/Code/cross_cohort_figures.ipynb): Generates figures comparing different cohorts across the studies. This final step allows for cross-comparison and broader insights across the datasets.
- [Clinical_group_differences.ipynb](https://github.com/haleyrwang/CCNL_DecodingEP/blob/main/Code/clinical_group_differences.ipynb): Although not part of the direct flow for EP/HCPEP or MEND analysis, this notebook is essential for analyzing clinical differences between various groups within the dataset, offering additional context and insights.


## Folder Structure
- The [Code](https://github.com/haleyrwang/CCNL_DecodingEP/tree/main/Code) folder contains all the code used to run the analyses and generate the figures.
- The [Data](https://github.com/haleyrwang/CCNL_DecodingEP/tree/main/Data) folder contains all the data used to run the analyses, including preprocessed DTI metrics from both HCP-EP and MEND datasets. If you use any of the processed DTI data, please cite this paper. The PLS outputs are not included due to file size.

## Contact
For any questions regarding the study, you can reach me at haleywang@ucla.edu.


