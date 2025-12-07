# Supply Chain Cost Analysis & ML Prediction

This project simulates a supply chain environment to analyze cost drivers and proposes a Machine Learning model to predict future operational costs. It is designed as a self-contained Jupyter Notebook that generates synthetic data, visualizes key metrics, and trains a predictive model.

## 📌 Overview

Efficient supply chain management requires understanding how various factors—demand, transport rates, inventory levels, and lead times—impact total costs. This repository demonstrates how to:

1.  **Simulate Data**: Generate a realistic dataset for multiple distribution centers (North, South, Central) over a 365-day period.
2.  **Analyze & Visualize**: Use Python libraries (`seaborn`, `matplotlib`) to uncover trends and cost breakdowns.
3.  **Predict Costs**: Implement a Random Forest Regressor to predict daily operational costs based on operational signals.

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed (3.8+ recommended).

### Installation

1.  Clone this repository:
    ```bash
    git clone https://github.com/yourusername/supply-chain-analysis.git
    cd supply-chain-analysis
    ```

2.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Usage

1.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2.  Open `supply-chain-cost-optymization.ipynb` to view the analysis and run the cells.

## 📊 Key Features

-   **Synthetic Data Generation**: Creates realistic daily logs including:
    -   Daily Demand (with seasonality)
    -   Transport Unit Costs (market fluctuations)
    -   Inventory Levels & Lead Times
-   **Interactive Visualizations**:
    -   Multi-line charts for cost trends.
    -   Stacked bar charts for cost component analysis.
    -   Multivariate scatter plots for correlation analysis.
-   **Machine Learning Model**:
    -   **Algorithm**: Random Forest Regressor (Scikit-Learn).
    -   **Target**: Daily Total Cost.
    -   **Output**: Model performance metrics (MAE, RMSE) and Feature Importance plots.

## 🛠 Technology Stack

-   **Python 3**
-   **Pandas & NumPy**: Data manipulation and simulation.
-   **Matplotlib & Seaborn**: Data visualization.
-   **Scikit-Learn**: Machine Learning implementation.
-   **Jupyter Notebook**: Interactive development environment.

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
