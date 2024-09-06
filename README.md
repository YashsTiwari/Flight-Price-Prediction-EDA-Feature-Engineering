# Flight Price Prediction: EDA and Feature Engineering

This project focuses on conducting **Exploratory Data Analysis (EDA)** and **Feature Engineering** on the Flight Price Prediction dataset. I aimed to apply data science techniques, from cleaning and understanding the dataset to preparing it for model training.

## Project Overview

The flight price dataset contains various details about flights, such as airlines, sources, destinations, and prices. The main objective of this project is to:
- Explore the dataset to identify patterns and insights.
- Engineer features that could help in building predictive models.
- Prepare the data for training machine learning models.

### Key Steps in the Project

1. **Data Loading and Preprocessing:**
   - The dataset was loaded using pandas.
   - Handled missing values appropriately by filling or dropping them where necessary.

2. **Exploratory Data Analysis (EDA):**
   - Descriptive statistics were performed to understand the dataset.
   - Visualizations and insights were derived from the data to explore trends in flight prices, durations, and more.

3. **Feature Engineering:**
   - Extracted new features such as `Date`, `Month`, `Year`, `Departure Hour`, `Arrival Hour`, `Duration Hours`, and `Duration Minutes`.
   - Encoded categorical features like `Airline`, `Source`, `Destination`, and `Additional_Info` using one-hot encoding.

4. **Dropping Unnecessary Columns:**
   - Removed columns that were not useful after feature extraction, such as `Duration`.

5. **Final Data Preparation:**
   - Combined all the processed features into a final dataframe, ready for model training.

### Next Steps

In future iterations, I plan to:
- Train machine learning models to predict flight prices.
- Tune models for improved accuracy.

## Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/YashsTiwari/Flight-Price-Prediction-EDA-Feature-Engineering.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook to view the analysis.
