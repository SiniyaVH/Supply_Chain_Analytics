# 📦 Supply Chain Analytics

### Data Analysis | Logistics | Inventory | Order Management

## 📌 Project Overview

Supply Chain Analytics uses data analysis techniques to understand and improve the flow of products, orders, and deliveries across supply chain operations.

This project focuses on analyzing supply chain data to identify operational patterns, evaluate order and shipping performance, explore product and regional sales trends, and generate actionable business insights.

Using Python and its data analysis libraries, the project follows an end-to-end workflow covering data cleaning, preprocessing, exploratory data analysis (EDA), statistical analysis, and data visualization.

The ultimate goal is to transform raw supply chain data into meaningful insights that support data-driven business decisions.

## 🎯 Project Objectives

* Analyze order and shipment data to understand operational performance.
* Clean and preprocess raw supply chain datasets.
* Identify missing values, duplicate records, inconsistent data types, and unusual observations.
* Analyze sales and order quantities across product categories.
* Explore order trends across different regions and time periods.
* Evaluate shipping and delivery performance using available data.
* Investigate inventory-related patterns when relevant inventory fields are available.
* Create meaningful visualizations to communicate findings.
* Provide data-driven recommendations for improving supply chain efficiency.

## 🏢 Business Problem

Supply chain operations involve multiple activities, including order processing, inventory management, product distribution, transportation, and delivery.

Without proper analysis, businesses may struggle to identify operational inefficiencies, understand delivery delays, monitor product demand, and evaluate performance across regions.

This project addresses important business questions such as:

* Which products or categories generate the highest sales?
* How does order volume change over time?
* Which regions contribute the most to order activity?
* How does shipping performance vary across shipping modes?
* Are there patterns in delayed deliveries?
* Which operational areas may require further investigation?
* What data-quality issues could affect business reporting?

The analysis will use available dataset fields to investigate these questions and develop evidence-based recommendations.

## 📂 Dataset Information

**Dataset Name:** 1.DataCo SMART Supply Chain Analytics

**Dataset Source:** [DataCo SMART Supply Chain dataset hosted on Mendeley Data]

**Dataset Link:** [(https://data.mendeley.com/datasets/8gx2fvg2k6/5)]

**File Format:** CSV, Excel, or another supported format.

The dataset may contain information about orders, products, customers, sales, shipping, delivery, and geographical regions. The exact fields depend on the selected dataset.

### Dataset Overview

| Attribute         | Description                                           |
| ----------------- | ----------------------------------------------------- |
| Dataset name      | To be specified                                       |
| Source            | To be specified                                       |
| File format       | To be verified                                        |
| Number of rows    | To be determined after loading                        |
| Number of columns | To be determined after loading                        |
| Data types        | Numerical, categorical, and date fields, as available |
| Data quality      | To be assessed                                        |
| Domain            | Supply Chain and Logistics                            |

**Note:** Actual dataset dimensions, column names, and findings should be added after inspecting the data.

## 🛠️ Tools and Technologies

| Tool             | Purpose                                        |
| ---------------- | ---------------------------------------------- |
| Python           | Data analysis and processing                   |
| Pandas           | Data cleaning, transformation, and aggregation |
| NumPy            | Numerical operations                           |
| Matplotlib       | Data visualization                             |
| Seaborn          | Statistical visualization                      |
| Jupyter Notebook | Interactive analysis and documentation         |
| Git and GitHub   | Version control and project sharing            |

## 🔄 Project Workflow

### 1. Data Loading

* Import the required Python libraries.
* Load the dataset into a Pandas DataFrame.
* Inspect the first and last few records.
* Review the dataset's dimensions and column names.

### 2. Data Understanding

* Examine column data types.
* Identify numerical and categorical variables.
* Understand the meaning of important fields.
* Check the level of detail represented by each row.

### 3. Data Cleaning

* Identify and handle missing values.
* Investigate duplicate records.
* Correct inconsistent data types.
* Standardize categorical values where necessary.
* Validate numerical and date fields.
* Investigate unusual values and potential outliers.

### 4. Feature Engineering

Create additional variables when the required source fields are available.

Examples include:

* Order month and year.
* Shipping duration.
* Delivery delay.
* Total sales by category.
* Daily or monthly order volume.
* Aggregated order quantities.

### 5. Exploratory Data Analysis (EDA)

* Analyze order and sales distributions.
* Compare product and category performance.
* Explore geographical patterns.
* Examine shipping and delivery information.
* Investigate trends over time.
* Study relationships between numerical variables.

### 6. Data Visualization

Create charts to communicate important patterns and comparisons.

### 7. Business Insights

* Summarize key findings.
* Identify areas requiring further investigation.
* Explain the operational significance of the results.
* Recommend improvements supported by the analysis.

## 📊 Exploratory Data Analysis

The following analyses may be performed depending on the available columns.

### 1. Order Analysis

* Total order records and unique orders.
* Order volume by region.
* Order activity over time.
* Distribution of order quantities.

### 2. Sales and Product Analysis

* Total sales by product category.
* Sales distribution across regions.
* Product-level order quantities.
* Comparison of sales across customer segments.

### 3. Shipping and Delivery Analysis

* Shipping duration by shipping mode.
* Delivery outcomes by region.
* Distribution of shipping delays.
* Comparison of available delivery-status categories.

### 4. Inventory Analysis

If the dataset contains appropriate inventory fields:

* Inventory levels across products.
* Stock availability.
* Reorder-level monitoring.
* Stockout patterns.

**Important:** Order quantities alone do not establish actual inventory levels or stockouts. These analyses require suitable inventory data.

### 5. Time-Based Analysis

* Daily order volume.
* Monthly sales trends.
* Changes in order quantities.
* Shipping performance over time.

### 6. Statistical Analysis

* Mean, median, and standard deviation.
* Distribution analysis.
* Potential outlier detection.
* Correlation analysis between suitable numerical variables.

## 📈 Key Performance Indicators (KPIs)

The following KPIs can be calculated if the required fields and definitions are available.

| KPI                       | Description                                                                   |
| ------------------------- | ----------------------------------------------------------------------------- |
| Total Orders              | Number of distinct orders                                                     |
| Total Sales               | Sum of validated sales values                                                 |
| Total Quantity            | Sum of recorded product quantities                                            |
| Average Order Value       | Total sales divided by distinct orders, using a consistent sales definition   |
| Average Shipping Duration | Average duration between valid shipping timestamps                            |
| On-Time Delivery Rate     | Percentage of eligible deliveries completed on or before the defined due date |
| Late Delivery Rate        | Percentage of eligible deliveries classified as late                          |
| Regional Sales            | Sales aggregated by geographical region                                       |
| Monthly Order Volume      | Number of distinct orders grouped by month                                    |

**KPI validation:** Confirm the meaning and aggregation level of the source fields before calculating metrics. Do not assume that a delivery-risk label represents an actual late delivery.

## 📉 Planned Visualizations

| Visualization | Purpose                                                     |
| ------------- | ----------------------------------------------------------- |
| Bar Chart     | Compare sales by product category or region                 |
| Line Chart    | Analyze order and sales trends over time                    |
| Histogram     | Understand numerical data distributions                     |
| Box Plot      | Investigate variability and potential outliers              |
| Count Plot    | Compare categorical values                                  |
| Scatter Plot  | Explore relationships between numerical variables           |
| Heatmap       | Visualize correlations between selected numerical variables |

Each chart should include a clear title, appropriate axis labels, and a brief interpretation.

## 💡 Expected Business Value

The analysis can help businesses:

* Understand order and sales patterns.
* Compare product and regional performance.
* Monitor shipping and delivery metrics.
* Identify data-quality problems.
* Investigate potential operational bottlenecks.
* Improve the visibility of supply chain performance.
* Support data-driven operational decisions.

These are potential benefits. Final recommendations will depend on the actual analytical findings.

## 📁 GitHub Repository Structure

```text
supply-chain-analytics/
│
├── data/
│   └── README.md
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   └── 03_exploratory_data_analysis.ipynb
│
├── outputs/
│   ├── charts/
│   └── summary_tables/
│
├── README.md
└── requirements.txt
```

## ⚙️ Installation and Setup

### Prerequisites

* Python 3.x
* Jupyter Notebook
* Git (optional)

### Step 1: Clone the Repository

Replace the placeholder with your actual GitHub repository URL.

```bash
git clone <your-repository-url>
```

### Step 2: Navigate to the Project Folder

```bash
cd supply-chain-analytics
```

### Step 3: Install the Required Libraries

Create a `requirements.txt` file with the following contents:

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

### Step 4: Add the Dataset

Download the dataset from its original source and place it in the appropriate local folder.

Update the file path in your notebook to match the downloaded file.

### Step 5: Launch Jupyter Notebook

```
jupyter notebook
```

Run the notebooks in numerical order, from data understanding through exploratory analysis.

**Data-sharing note:** Check the dataset license and usage terms before uploading raw or processed data to a public repository.

## 📝 Results and Key Findings

Add your actual findings here after completing the analysis.

Recommended items to document:

* Dataset dimensions and data-quality issues.
* Important sales and order patterns.
* Product and regional comparisons.
* Shipping and delivery observations.
* Relevant statistical relationships.
* Key business recommendations.

Avoid adding assumed results or unsupported numerical claims.

## ⚠️ Limitations

* Analysis depends on the availability and quality of the selected dataset.
* Missing or inconsistent values may affect results.
* Some KPIs require specific date, delivery, sales, or inventory fields.
* Order-level calculations must account for transaction-level records to avoid double-counting.
* Correlation does not establish causation.
* Business recommendations should be based on validated findings.

## 🚀 Future Improvements

Possible extensions include:

* Automated data-quality checks.
* Additional operational performance metrics.
* More detailed geographical analysis.
* Improved visual reporting.
* Integration of additional supply chain datasets.
* Demand forecasting or predictive analytics as separate extensions, if appropriate data is available.

## 👩‍💻 Skills Demonstrated

* Python programming
* Pandas and NumPy
* Data cleaning and preprocessing
* Feature engineering
* Exploratory Data Analysis (EDA)
* Descriptive statistics
* Data visualization
* KPI analysis
* Business problem-solving
* Analytical reporting
* Git and GitHub

## 📌 Conclusion

This Supply Chain Analytics project demonstrates how Python can be used to examine operational data, identify patterns, evaluate relevant performance metrics, and develop data-driven business insights.

By combining data cleaning, exploratory analysis, statistical techniques, and visualization, the project provides a structured approach to understanding supply chain operations and communicating analytical findings.

---

**Project Status:** Update this README as the analysis progresses.

**Author:** Siniya V H

**GitHub:** https://github.com/SiniyaVH

**LinkedIn:** https://www.linkedin.com/in/siniya-v-h
