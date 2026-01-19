# Crop Yield Prediction Analysis

This project analyzes crop yield data to understand factors affecting agricultural productivity across different Indian states, seasons, and crops.

## Dataset
The analysis uses `crop_yield.csv`, which contains data on:
- Crop types (Arhar/Tur, Coconut, Rice, etc.)
- Seasons (Kharif, Rabi, Whole Year)
- States (Assam, Karnataka, Kerala, etc.)
- Production statistics (Area, Production, Yield)
- Environmental factors (Annual Rainfall, Fertilizer, Pesticide)

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas
- seaborn
- matplotlib
- numpy

## Setup and Usage
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Crop.ipynb
   ```
4. Run all cells to generate the analysis and visualizations.

## Analysis Overview
The notebook covers:
- Data loading and cleaning
- Exploratory Data Analysis (EDA)
- Visualizations of yield per state and crop type
- Correlation analysis between yield and inputs (rainfall, fertilizer, etc.)
