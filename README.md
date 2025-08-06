# Marketing & Customer Behavior Analysis for an E-Commerce Company

## Project Overview
This project is a comprehensive analysis of a leading e-commerce company's marketing and sales data. The goal is to derive actionable insights, understand customer behavior, and build predictive models to support strategic decision-making. The analysis addresses key business questions related to revenue generation, customer acquisition and retention, marketing effectiveness, and product performance.

## Key Features & Analysis
- **Transactional Revenue Calculation**: Calculated total transactional revenue, including the impact of discounts, taxes, and delivery charges.
- **Exploratory Data Analysis (EDA)****: Performed detailed analysis of sales and customer data to identify patterns such as seasonality, regional trends, and product demand.
- **Customer Segmentation**: Implemented **RFM (Recency, Frequency, Monetary)** analysis and **K-Means clustering** to segment customers into strategic groups for targeted marketing.
- **Predictive Modeling**: Developed and evaluated classification models for **churn prediction** and regression models for **customer lifetime value (CLV) estimation**.
- **Cohort Analysis**: Conducted a monthly cohort analysis to visualize and understand customer retention rates over time.
- **Marketing ROI**: Analyzed the return on investment for both online and offline marketing channels to optimize future spending.
- **Product Performance**: Identified top-selling products by units sold and revenue, assessing the impact of discounts and taxes on demand.

## Data Sources
The project utilizes a dataset comprising five interconnected files:
- `Online_Sales.csv`: Transactional sales data
- `Customers_Data.csv`: Customer demographics
- `Discount_Coupon.csv`: Discount percentages by category
- `Marketing_Spend.csv`: Daily marketing expenditure
- `Tax_Amount.csv`: GST tax percentages by category

## Technologies & Libraries Used
- **Python**: The core language for the entire analysis.
- **Pandas**: For data manipulation and cleaning.
- **Numpy**: For numerical operations.
- **Matplotlib & Seaborn**: For creating data visualizations.
- **Scikit-learn**: For machine learning tasks, including clustering, classification, and regression.

## Getting Started
To run this analysis, you will need to have Python and the listed libraries installed. The project notebook is available in this repository.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/ZenithMacwan/E-commerce
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd E-commerce
    ```
3.  **Install the required libraries:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn missingno
    ```
4.  **Open and run the Jupyter Notebook:**
    ```bash
    jupyter notebook marketing-customer-behavior-analysis.ipynb
    ```

Feel free to explore the notebook, and provide any feedback or suggestions!
