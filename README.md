# Eat & Tell: A Randomized Trial of Random-Loss Incentive to Increase Dietary Self-Tracking Compliance

This repository contains the Jupyter notebook used for reproducing the results published in our [Digital Health 2018 paper](https://www.researchgate.net/publication/323956409_Eat_Tell_A_Randomized_Trial_of_Random-Loss_Incentive_to_Increase_Dietary_Self-Tracking_Compliance):

Achananuparp, P., Lim, E.-P., Abhishek, V., & Yun, T. (2018). Eat & Tell: A Randomized Trial of Random-Loss Incentive to Increase Dietary Self-Tracking Compliance. In Proceedings of the 2018 International Conference on Digital Health - DH ’18. https://doi.org/10.1145/3194658.3194662

Please contact [Aek](mailto:palakorna@smu.edu.sg?cc=palakorn@gmail.com) if you have any questions or problems.

## Requirements
The notebooks have been tested in R 3.5.1 via Anaconda with the following packages:

* effects
* dlyr
* ggplot2
* lme4

## Project Structure
By default, the project assumes the following directory structure:
```
project 
└───data  
│   │   deduction_amounts.csv
│   │   deductions_7d.csv
│   │   deductions.csv
│   │   demos.csv
│   │   end-of-days_7d.csv
│   │   end-of-days.csv
│   │   food_diaries.csv
│   │   post_food_diaries.csv
│   │   pre_food_diaries.csv
│   │   users.csv
└───notebooks
│   │   data-analysis.ipynb
└───reports
│   └───figures
```
All CSV data files should be put in the `data` folder. All notebooks should be put in the `notebooks` folder. Any generated reports and figures will be put in the `reports` folder.

## Pipeline

### Step 0: Data import
[Download the data](hhttps://drive.google.com/open?id=1zuo9CXxquiS8r8iyMQEJfDSQO8YO9j1w) and extract the CSV files to the `data` directory.

### Step 1: Run the data analysis notebook
Run the notebook `data-analysis.ipynb` to perform all analyses.

__Outputs:__ Several figures will be generated and stored in the `reports/figures` folder.
