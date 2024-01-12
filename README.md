# 🎮 A Deep Dive into the Gaming Universe (EDA)
This project is a comprehensive EDA over the gaming industry. The analysis can be accessed [here](analysis/a-deep-dive-into-the-gaming-universe-eda.ipynb).

**Author**: Po-Hsun (Ben) Chen

## Summary
Video games have become one of the most popular forms of entertainment in recent decades, with the industry generating billions of dollars in revenue each year. This notebook presents an exploratory data analysis (EDA) of video game sales data, with the aim of gaining insights into the trends and patterns in the industry.

## Data Source
The dataset used in this analysis contains information on video game sales from 1980 to 2020, including data on game titles, platforms, publishers, genres, ratings, and sales figures. The dataset used in this analysis is sourced from Kaggle. You can access the dataset [here](https://www.kaggle.com/datasets/gregorut/videogamesales).

## Dependencies
All required dependencies are listed in this [conda environment file](environment.yaml).

## How to Reproduce the Analysis
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/phchen5/gaming-universe-eda.git
   cd gaming-universe-eda
   ```
2. **Download the Dataset from the Source:**
   You may need to register for a Kaggle account. After you've downloaded the dataset, place the `vgsales.csv` file within a `data/` folder located in the root. You may also place it anywhere else in the repository as you like, just 
be sure to edit the data source path within the analysis.
3. **Set Up and Activate Environment:**
   ```bash
   conda env create -f environment.yaml
   conda activate gaming-universe-eda
   ```
4. **Open the Notebook:**
   ```bash
   jupyter lab analysis/a-deep-dive-into-the-gaming-universe-eda.ipynb
   ```
5. **Run the Cells and Have Fun Exploring!**

## Files
- `analysis/a-deep-dive-into-the-gaming-universe-eda.ipynb`: Jupyter notebook containing the EDA code.
- `environment.yaml`: Conda environment file listing required dependencies.

