# Moscow Real Estate Price Analysis

This project analyzes real estate prices in Moscow and the Moscow Region using Python. It includes data preprocessing, exploratory data analysis, visualizations, and predictive modeling.

## Project Overview

The goal is to explore factors influencing apartment prices and compare price per square meter between Moscow and Moscow Region. The dataset (`data.csv`) is sourced from [Kaggle](https://www.kaggle.com/datasets/egorkainov/moscow-housing-price-dataset) and contains apartment details such as area, number of rooms, distance to metro, and more.

### Features
- **Data Cleaning**: Handles outliers and encodes categorical variables (apartment type, region, renovation).
- **Exploratory Data Analysis**: Visualizes relationships between price and features like area, minutes to metro, and number of rooms.
- **Modeling**: Implements Linear Regression and Random Forest Regressor to predict prices, with R² score evaluation.
- **Statistical Analysis**: Conducts a T-test to compare price per square meter between Moscow and Moscow Region.

## Requirements
- Python 3.x
- Libraries: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `scipy`

Install dependencies:
```bash
pip install pandas matplotlib seaborn scikit-learn scipy
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/MoscowRealEstateAnalysis.git
   ```
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/egorkainov/moscow-housing-price-dataset) and place `data.csv` in the project directory.
3. Run the Jupyter notebook `SRW.ipynb` to execute the analysis.

## Key Findings
- Scatter plots reveal correlations between price and features like area and number of rooms.
- Random Forest outperforms Linear Regression in price prediction based on R² scores.
- T-test indicates significant price per square meter differences between Moscow and Moscow Region (p-value ≈ 0).

## File Structure
- `SRW.ipynb`: Main Jupyter notebook with the analysis.
- `data.csv`: Dataset (not included; download from Kaggle).
- `README.md`: Project documentation.

## Contributing
Feel free to open issues or submit pull requests for improvements or bug fixes.

## License
This project is licensed under the MIT License.