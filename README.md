# US Arrests Analysis: Clustering US States based on Crime Rates

This project focuses on the analysis of crime statistics across US states using clustering techniques in R.

## Introduction

The dataset originates from the 50 states of the USA, capturing crime statistics per 100,000 residents. The purpose of this analysis is to group US states into clusters based on similarities in their crime rates. 

## Objectives

- Explore the dataset to understand its structure and the patterns it contains.
- Implement K-Means clustering to categorize states into three distinct groups: low, medium, and high crime rates.
- Apply hierarchical clustering to group states and investigate the difference in results from K-means clustering.
- Evaluate the effects of scaling variables on the clustering results.

## Technologies Used

- **Language**: R
- **Libraries**: dplyr, ggplot2, knitr

## Steps to Reproduce

1. **Set up your environment**:
   - Ensure R and RStudio are installed.
   - Install the necessary R packages (`dplyr`, `ggplot2`, `knitr`).
   
2. **Download the dataset** (`usarrests.csv`).
   
3. **Run the R Markdown script**:
   - Set your working directory to the location containing the dataset.
   - Load the required libraries.
   - Execute the embedded R code chunks within the R Markdown document.

## Results

- Explored the dataset using functions like `dim()`, `str()`, `colnames()`, `head()`, and `tail()`.
- Applied K-means clustering to categorize states into three clusters representing low, medium, and high crime rates.
- Hierarchical clustering, both with and without scaling the variables, was applied. Results indicated differences in cluster composition based on the methodology and scaling.
  
## Conclusion

The analysis successfully categorized US states based on their crime statistics. The clustering provides insights for policymakers to understand the crime patterns and devise strategies accordingly. Scaling the variables before clustering demonstrated its importance in achieving a more balanced and meaningful clustering solution.

---

To reproduce the analysis:

1. Ensure that R and RStudio are installed.
2. Clone/download the repository.
3. Open the R Markdown file in RStudio.
4. Install the required packages.
5. Set the working directory to the location of the `usarrests.csv` file.
6. Execute the R Markdown file to generate the report.
