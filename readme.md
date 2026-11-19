# Tips for Data Analyst Report

This repository contains a collection of tips and best practices for creating effective data analyst reports. Wheather you're a beginner or an experienced analyst, these tips will help you communicate your findings clearly and effectively.

### 1. Installation by creating a virtual python environment
To setup a Python enviroment for workig with data analysis reports, follow these steps:

```bash
# create a new virtual environment
python -m venv.venv

# Activate the virtual environment in windows using gitbash
source .venv/Scripts/activate

# create a requirements.txt file and add liabraries
# install required packages
pip install -r requirements.txt 
```
## 2. Create a Jupyter Notebook

```bash
# create a ipynb file

### 2.1 Use of Claude code for data analytics report

### Here is the prompt no.1 
> 1. I have df in this notebook, which is tips data. Act as a data analyst and write the code using Python liabraries: pandas, numpy, seaborn, matplotlib, and plot to do the basic data anaytics tasks such as: 
1. data composition report
2. data distribution report
3. data comparision report
4. data relationship report.

> If you need to do the statistics, please install stats models and scipy liabraries using code cells in jupyter notebook. 

> If you need to create a plot and whenever you do that, please interpret the results as I would like to submit that in a report form.

> Lets see what you have got, i am really looking forward to your code without bugs and best possible plots.