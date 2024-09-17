# Tri-Media-Sales-Forecasting-Engine
This repository contains a machine learning project focused on predicting sales based on advertising spend using linear regression. The dataset includes advertising budgets for TV, Radio, and Newspaper, with the goal of understanding how each medium contributes to overall sales. 
Here’s an updated README with the new project name **"Tri Media Forecasting Engine"**:

---

# Tri Media Sales Forecasting Engine

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Model Evaluation](#model-evaluation)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction
**Tri Media Forecasting Engine** is a machine learning project aimed at predicting sales based on advertising spends across three major media channels: **TV**, **Radio**, and **Newspaper**. Using **Linear Regression**, the project provides insights into the effectiveness of each medium and helps forecast future sales based on different ad budget allocations.

The model is evaluated through key metrics such as **Mean Squared Error (MSE)** and **R-squared (R²)**. The project includes data visualization to help interpret the model's performance and results.

## Dataset
The dataset contains the following features:
- **TV**: Advertising spend on TV in thousands of dollars.
- **Radio**: Advertising spend on Radio in thousands of dollars.
- **Newspaper**: Advertising spend on Newspapers in thousands of dollars.
- **Sales**: Sales of the product in thousands of units.

This dataset is typically used in projects involving regression analysis and marketing strategy optimization.

## Project Structure
```
├── advertising.csv                # Dataset
├── tri-media-forecasting-engine.ipynb   # Colab notebook with code
├── README.md                      # Project documentation
└── LICENSE                        # License for the project
```

## Installation
To run this project locally, you need to have Python and the necessary libraries installed.

### Prerequisites
- Python 3.x
- Jupyter Notebook / Google Colab
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

### Installation Steps

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/tri-media-forecasting-engine.git
    ```

2. Navigate to the project directory:
    ```bash
    cd tri-media-forecasting-engine
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter notebook or upload it to Google Colab to run:
    ```bash
    jupyter notebook tri-media-forecasting-engine.ipynb
    ```

## How to Use
1. Load the dataset (`advertising.csv`) into the notebook.
2. Follow the steps for **data preprocessing**, **exploratory data analysis (EDA)**, and **model training**.
3. Use the trained model to make predictions for future advertising budgets.
4. Check the visualizations and metrics to interpret the model's performance.

You can experiment with different advertising spend values to see their impact on predicted sales.

## Model Evaluation
The model's performance is evaluated using:
- **Mean Squared Error (MSE)**: Measures the average squared difference between actual and predicted sales.
- **R² (R-squared)**: Explains the proportion of variance in sales that is accounted for by the advertising spend.

## Visualizations
- **Regression Line**: Visualizes the linear relationship between each advertising channel and sales.
- **Residual Plot**: Helps visualize the error distribution to check for model fit.
- **Actual vs Predicted Sales**: Shows how close the model's predictions are to actual sales.
- **Feature Importance (Coefficient Plot)**: Highlights the relative contribution of each advertising channel to sales.

## Conclusion
The **Tri Media Forecasting Engine** demonstrates how linear regression can be effectively used to predict sales based on advertising spend across different media channels. Insights from this model can guide businesses in making informed marketing decisions, maximizing return on investment (ROI) across TV, Radio, and Newspaper advertising.

### Key Findings:
- **TV advertising** has the largest impact on sales, followed by **Radio**.
- **Newspaper advertising** has a lesser but still significant effect.
- The model achieves a high R² and a low MSE, indicating good predictive performance.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to adjust the repository name, file paths, or any content based on your specific implementation. Let me know if you need further changes!
