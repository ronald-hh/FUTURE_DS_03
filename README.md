# Bank Marketing Funnel & Conversion Analysis
## Project Overview
This project analyzes data from a bank's phone marketing campaign selling term deposits, using Python. The goal is to understand where conversion happens along the funnel, identify which channels, timing, and customer segments perform best, and provide insights that can help improve campaign conversion rates.
## Features
- Clean and prepare the dataset
- Build the funnel: leads contacted -> call connected -> customer converts (subscribes)
- Analyze conversion by number of contact attempts
- Compare conversion across contact channels (cellular vs landline)
- Assess the impact of past campaign outcomes on conversion
- Analyze seasonality in conversion by month
- Compare conversion across customer segments (job type and age group)
- Visualize trends using charts
- Provide business insights and recommendations
## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
## Installation
Install the required libraries before running the notebook.
```bash
pip install pandas matplotlib notebook
```
## How to Run
1. Download or clone this repository.
```bash
git clone <repository-link>
```
2. Move into the project folder.
```bash
cd <project-folder>
```
3. Start Jupyter Notebook.
```bash
jupyter notebook
```
4. Open the notebook:
```
Bank_Marketing_Funnel_Analysis.ipynb
```
5. Run all the cells from top to bottom.
## Dataset
This project uses the **bank-additional-full** dataset, which contains information on leads contacted through a bank's phone marketing campaign, including demographics, job type, contact channel, number of contact attempts, outcome of previous campaigns, and whether the lead converted (subscribed to a term deposit).

## Project Structure
```
Bank_Marketing_Funnel_Analysis.ipynb
README.md
bank-additional-full.csv
```
> Replace the dataset filename if yours is different.
## Results
The analysis includes:
- Data cleaning and preprocessing
- The lead -> connected -> converted funnel
- Conversion rate by number of contact attempts
- Conversion rate by contact channel
- Impact of past campaign outcomes on conversion
- Seasonality in conversion by month
- Conversion by customer segment (job type and age group)
- Business insights on campaign performance
- Recommendations for improving conversion
