# Logistics Data Analysis – Week 1

## Internship
**Logistics Data Analyst Intern – Week 1**

## Project Title
**Inventory Management and Stockout Reduction in a Retail Supply Chain**

## Objective
This project simulates the planning and strategy phase of a logistics data analysis project. The analysis focuses on understanding logistics order patterns and demonstrating how data-driven techniques can support inventory planning and resource allocation.

## Scenario
The proposed scenario focuses on inventory management in a retail supply chain. The company experiences fluctuations in order demand, which may lead to stockouts during high-demand periods and excess inventory during low-demand periods.

## KPIs
The project identifies three relevant logistics KPIs:

- **Stockout Rate** – Measures inventory availability.
- **Inventory Turnover** – Measures inventory efficiency.
- **Order Fulfillment Rate** – Measures order fulfillment performance.

## Dataset
The project uses the **Daily Demand Forecasting Orders** dataset from the **UCI Machine Learning Repository**.

The dataset contains 60 observations and 13 columns, including 12 predictive attributes and the target variable **Target (Total orders)**.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## Analysis Performed

The Week 1 analysis includes:

1. Data Loading and Inspection
2. Data Cleaning Checks
3. Exploratory Data Analysis
4. Linear Regression
5. K-Means Clustering
6. Business Interpretation
7. Strategic Decision Support

## Project Files

- `Week1_Logistics_Analysis.ipynb` – Python analysis notebook
- `Daily_Demand_Forecasting_Orders.csv` – Dataset used for analysis
- `Strategic Planning and Data Exploration in Logistics.docx` – Week 1 strategic planning report

## Expected Outcomes

The proposed approach is expected to support:

- Better demand visibility
- Improved inventory planning
- More effective resource allocation
- Reduced risk of stockouts and excess inventory
- Data-driven logistics decision-making

## Note

The current dataset provides logistics order information but does not contain direct inventory, stockout, warehouse, or fulfillment fields. Therefore, the selected KPIs and optimization approach are presented as part of the proposed strategic framework, while the available dataset is used to demonstrate order analysis, regression and clustering.

## Data Source

UCI Machine Learning Repository – Daily Demand Forecasting Orders


# Logistics Data Analysis – Week 2

## Internship

**Logistics Data Analyst Intern – Week 2**

## Project Title

**Data Collection, Cleaning and Preprocessing for Logistics Analysis**

## Objective

This project focuses on preparing logistics data for analysis by inspecting data quality, checking missing values and duplicate records, identifying potential outliers, applying normalization techniques and validating the processed dataset.

## Dataset

The project uses the **Daily Demand Forecasting Orders** dataset from the **UCI Machine Learning Repository**.

The dataset contains 60 observations and 13 columns, including 12 predictive attributes and the target variable **Target (Total orders)**.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Analysis Performed

The Week 2 analysis includes:

1. Data Loading and Inspection
2. Missing Value Checks
3. Duplicate Record Checks
4. Data Type Inspection
5. Potential Outlier Detection Using Boxplots
6. Potential Outlier Detection Using the IQR Method
7. Min-Max Normalization
8. Final Data Validation

## Results

- Dataset shape: 60 rows and 13 columns.
- Missing values: 0.
- Duplicate records: 0.
- Potential outliers were identified using the IQR method.
- A total of 47 column-level outlier flags were identified. These are not 47 unique records.
- Min-Max scaling was applied to numerical columns.
- The normalized values ranged from 0 to 1.

## Project Files

- `Week2_Logistics_Analysis.ipynb` – Python data preprocessing notebook
- `Daily_Demand_Forecasting_Orders.csv` – Dataset used for analysis
- `Week2_Logistics_Data_Preprocessing.docx` – Week 2 report

## Expected Outcomes

The preprocessing workflow is intended to support:

- Improved understanding of data quality
- Identification of unusual data values
- Consistent numerical scales for analysis
- More reliable data preparation
- Data-driven logistics decision-making

## Note

Potential outliers were identified for investigation and were not automatically removed. Min-Max scaling was used to transform numerical values to a range between 0 and 1. These results describe the preprocessing performed and do not independently establish improvements in logistics performance.

## Data Source

UCI Machine Learning Repository – Daily Demand Forecasting Orders

https://archive.ics.uci.edu/dataset/409/daily+demand+forecasting+orders


## Week 3: Advanced Data Analysis and Visualization in Logistics

### Objective
To perform Exploratory Data Analysis (EDA) on a hypothetical logistics dataset using Python, create visualizations, identify relationships between logistics variables and derive insights about operational efficiency, transportation costs and potential delivery bottlenecks.

### Dataset
**File:** `Week3_Hypothetical_Logistics_Dataset.csv`

The dataset contains 90 shipment records and 10 columns, including shipment ID, date, route, vehicle type, shipment volume, distance, delivery time, transportation cost, fuel consumption and on-time delivery status.

### Tools and Technologies
- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

### Analysis Performed
1. **Data inspection:** Examined dataset dimensions, column names, data types and sample records.
2. **Data quality checks:** Checked missing values and duplicate records. No missing values or duplicate rows were found.
3. **Descriptive statistics:** Calculated mean, median, minimum, maximum, quartiles and standard deviation.
4. **Correlation analysis:** Examined relationships among shipment volume, distance, delivery time, transportation cost and fuel consumption.
5. **Route-wise analysis:** Compared average delivery time, transportation cost per shipment, cost per kilometre, fuel per kilometre, on-time delivery rate and implied speed.
6. **Vehicle-wise analysis:** Compared shipment counts, average distance, delivery time, transportation cost and on-time delivery rates.
7. **Visualization:** Created a scatter plot, bar charts, histogram, box plot and correlation heatmap to communicate the findings.

### Visualizations Created
- Distance vs. Transportation Cost — Scatter Plot
- Average Delivery Time by Route — Bar Chart
- On-Time vs. Not-On-Time Shipments — Bar Chart
- Distribution of Delivery Times — Histogram
- Delivery-Time Spread and Potential Outliers — Box Plot
- Correlation Heatmap of Logistics Metrics
- Average Implied Speed by Route — Bar Chart

### Key Findings
- Distance and transportation cost had a strong positive correlation of approximately **0.982**.
- Route A had the lowest average delivery time at approximately **5.35 hours**.
- Route E had the highest average delivery time at approximately **7.51 hours** and an on-time delivery rate of approximately **26.67%**.
- Average transportation cost per shipment was highest for Route E at approximately **₹3,336.74** and lowest for Route C at approximately **₹2,660.20**.
- Route D had the highest average implied speed at approximately **31.33 km/h**, while Route C had the lowest at approximately **25.44 km/h**.

### Recommendations
- Investigate Route E's delivery delays and review route conditions, waiting time, loading and unloading activities.
- Monitor delivery performance against the actual operational service-level target.
- Compare routes and vehicle types under similar operating conditions before making efficiency decisions.
- Track transportation cost per shipment, cost per kilometre and fuel consumption per kilometre.
- Collect additional operational data, such as traffic conditions and loading delays, to improve future analysis.

### Limitations
This is a hypothetical dataset created for educational purposes. The on-time delivery status was generated using an assumed 6.5-hour threshold, not a verified company service-level agreement. Implied speed was calculated using distance divided by total delivery time and should not be interpreted as actual driving speed.

### Deliverables
- `Week3_Hypothetical_Logistics_Dataset.csv` — Dataset
- `Week3_Hypothetical_Logistics_Dataset.ipynb` — Python analysis notebook
- `Week3_Advanced_Logistics_Analysis_Report.docx` — Final report

### Conclusion
This task provided practical experience in Python-based exploratory data analysis, descriptive statistics, correlation analysis, data visualization and logistics performance interpretation. The findings demonstrate how data analysis can help identify patterns, compare routes, investigate potential bottlenecks and develop data-driven recommendations.

# Week 4: Predictive Modeling and Optimization in Logistics Systems

## Project Overview

This project focuses on applying machine learning techniques to predict shipment delivery times and explore strategies for improving logistics operations.

Using a hypothetical logistics dataset containing 90 shipment records, predictive models were developed and evaluated using Python.

The project compares Linear Regression, Decision Tree Regression and a baseline model to identify an effective approach for estimating delivery time.

## Objectives

- Predict shipment delivery time using machine learning.
- Perform data preprocessing and feature selection.
- Train and evaluate regression models.
- Compare model performance using MAE, RMSE, and R².
- Apply cross-validation and hyperparameter tuning.
- Recommend strategies for improving logistics efficiency.

## Dataset Description

**Dataset:** `Week3_Hypothetical_Logistics_Dataset.csv`

- Total Records: 90
- Total Columns: 10
- Missing Values: 0
- Duplicate Records: 0

**Target Variable:** `Delivery_Time_hours`

**Predictor Features:**
- `Distance_km`
- `Shipment_Volume`
- `Route`
- `Vehicle_Type`

The dataset is simulated and used for educational analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Workflow

1. **Data Preparation:** Loaded and inspected the dataset, selected relevant features and applied preprocessing.
2. **Model Training:** Trained a baseline model, Linear Regression, and Decision Tree Regressor.
3. **Hyperparameter Tuning:** Used GridSearchCV to tune Decision Tree parameters.
4. **Model Evaluation:** Compared models using MAE, RMSE, and R² on a held-out test set.
5. **Cross-Validation:** Applied five-fold cross-validation to assess Linear Regression performance.
6. **Visualization:** Created actual-versus-predicted and residual plots.
7. **Optimization Recommendations:** Proposed improvements for delivery planning, route monitoring and resource allocation.

## Model Performance

The dataset was divided into 80% training data and 20% testing data.

| Model | MAE (hours) | RMSE (hours) | R² |
|---|---:|---:|---:|
| Mean Baseline | 1.209 | 1.574 | -0.234 |
| Linear Regression | **0.567** | **0.674** | **0.774** |
| Tuned Decision Tree | 0.960 | 1.077 | 0.423 |

**Best Performing Model: Linear Regression**

Linear Regression achieved the lowest test-set prediction error among the evaluated models, with an MAE of approximately 34 minutes.

## Key Findings

- Linear Regression performed better than the baseline and tuned Decision Tree on the held-out test set.
- The model achieved an R² score of 0.774, explaining approximately 77.4% of the variation in delivery times in the test sample.
- Route E showed a higher average delivery time in the previous exploratory analysis, suggesting an area for further investigation.
- Predictive modeling can support delivery planning and early identification of shipments requiring attention.

## Optimization Recommendations

- Identify shipments at risk of exceeding their planned delivery windows.
- Investigate routes with consistently higher delivery times.
- Improve dispatch planning and vehicle allocation using predicted delivery times.
- Collect additional operational information such as traffic, weather and loading delays.
- Monitor model performance using new shipment records before real-world deployment.

## How to Run the Project

1. Open Google Colab.
2. Upload `Week3_Hypothetical_Logistics_Dataset.csv`.
3. Open the Week 4 Python notebook or script.
4. Run the code cells sequentially.
5. Review the model evaluation results and visualizations.
6. Download the generated prediction and model comparison CSV files.

## Project Files

- `Week3_Hypothetical_Logistics_Dataset.csv` — Hypothetical logistics dataset.
- `Week4_Logistics_Predictive_Model.py` — Python predictive modeling implementation.
- `Week4_Predictive_Modeling_and_Optimization.docx` — Detailed project report.

## Limitations

This project uses a small hypothetical dataset. The findings demonstrate a predictive modeling workflow but do not guarantee real-world performance. Actual deployment would require larger datasets, additional operational features and time-aware validation.

## Conclusion

This project demonstrates how predictive modeling can be applied to logistics delivery-time estimation. Linear Regression achieved the best test-set performance among the evaluated models, while the analysis provided recommendations for improving shipment monitoring, delivery planning and operational decision-making.
