# automobile_EDA
## Overview
This Jupyter Notebook performs automated exploratory data analysis (EDA) on an automobile dataset. The main goal is to understand the structure, distribution, and key patterns within the data.

## Features
- **Data Loading**: Reads data from `Automobile.csv` using pandas.
- **Basic Exploration**:
  - Displays the first few rows of the dataset.
  - Provides metadata such as column types and missing values.
  - Computes summary statistics.
- **Visualization**:
  - Uses `seaborn` and `matplotlib` for visual representation.
  - **Fuel Type Distribution**: A count plot visualizing the frequency of different fuel types.
  - **Price Distribution**: A histogram (`displot`) showing how car prices are distributed.
  - **Horsepower vs. Price**: A joint plot illustrating the relationship between horsepower and price.
  - **Price Boxplot**: A boxplot that highlights the presence of outliers in the price column.
  - **Mean MPG Calculation**: A new column `mean_mpg` is computed as the average of city and highway mileage.

## Key Insights
- The dataset contains various types of fuel, with gasoline being the most common.
- The price distribution is right-skewed, meaning a few expensive cars significantly increase the mean price.
- There is a positive correlation between horsepower and price, indicating that more powerful cars tend to be more expensive.
- The boxplot of prices shows significant outliers, suggesting that some cars are exceptionally high-priced.
- The computed `mean_mpg` column provides a better understanding of fuel efficiency across different cars.

## Requirements
To run this notebook, you need the following Python libraries installed:
- pandas
- seaborn
- matplotlib

You can install them using:
```sh
pip install pandas seaborn matplotlib
```

## How to Use
1. Open the notebook in Jupyter.
2. Run the cells sequentially to load and explore the dataset.
3. Modify or extend the analysis as needed.

## Notes
- Ensure that `Automobile.csv` is present in the working directory.
- Additional preprocessing may be required depending on the dataset quality.

## License
This project is open-source and free to use for educational and research purposes.

