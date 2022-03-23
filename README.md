# data-driven-prediction-of-battery-cycle-life-before-capacity-degradation
# Implementing 'Variance Model'

The linear predictor is coded at the end of `Load Data.ipynb` but you need to generate the dataset first if you do not have it. To do that, follow the steps:
1. Make sure you have the right packages dependencies for the Python packages listed in `requirements.txt`
Shell commands: `pip install 'PackageName==1.4'`
2. Download the MatLab files (.mat extensions) at: https://data.matr.io/1/projects/5c48dd2bc625d700019f3204 
... this should take you some time
3. Convert them into a pickle packages by runing the `BuildPkl...ipynb` Jupyters
4. Run `Load Data.ipynb`
... you should be set!