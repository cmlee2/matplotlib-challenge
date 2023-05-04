# matplotlib-challenge

For this challenge, I was tasked with screening data regarding tumor development in mice while factoring in different drug regimens. 

For this challenge, multiple graphs were created, including:

    - Bar Charts
    - Pie Charts
    - Box Plots
    - Line Plots
    - Scatter Plots

Furthermore, multiple summary statistics were calculated, including:
    - Mean
    - Median
    - Variance
    - Standard Deviation
    - Standard Error
    - IQR
    - Outliers

For this assignment, assistance was gathered from stack overflow with creating truth-values in python:

    - outliers = final_volume_df.loc[(final_volume_df["Tumor Volume (mm3)"]>=upper_bound) | (final_volume_df["Tumor Volume (mm3)"]<=lower_bound),:]

Assistance was gathered from pandas for use of the duplicated command:

    - duplicated = merged_df[merged_df.duplicated(['Mouse ID' , 'Timepoint'], keep = False)]