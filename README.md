# 🚕 Taxi Data Analysis and Visualization Using Python

## 📌 Project Overview

This project focuses on analyzing and visualizing taxi trip data using Python. The objective is to clean the dataset, handle missing values, explore patterns, and create meaningful visualizations to understand taxi fares, trip distances, payment methods, and customer travel behavior.

The project uses **Pandas, Matplotlib, and Seaborn** to perform data cleaning, exploratory data analysis (EDA), and data visualization.

## 🎯 Objectives

* Load and explore the taxi dataset.
* Identify and handle missing values.
* Analyze taxi fares and trip distances.
* Understand trip distribution across pickup boroughs.
* Explore payment methods and tipping behavior.
* Visualize relationships between numerical variables.
* Generate meaningful insights using different visualization techniques.

## 🛠️ Technologies and Libraries

* **Python** – Programming language
* **Pandas** – Data manipulation and cleaning
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical data visualization

## 📂 Dataset

* **Dataset:** Taxis
* **Source:** Seaborn built-in dataset
* **Loading method:** `sns.load_dataset("taxis")`

The dataset contains taxi trip information, including:

* Pickup and drop-off timestamps
* Pickup and drop-off locations
* Trip distance
* Fare amount
* Tip amount
* Tolls
* Total fare
* Payment method

## 🧹 Data Cleaning and Preprocessing

The following data-cleaning techniques were applied:

* Checked missing values in all columns.
* Filled missing categorical values using the mode.
* Filled missing numerical values using the median.
* Removed rows with missing values in critical columns.
* Converted pickup timestamps into datetime format.
* Sorted the dataset by pickup time for time-based visualization.

## 📊 Data Visualization

### 1. Line Chart – Fare Over Time

Visualizes taxi fares against pickup timestamps to explore changes in fare amounts over time.

### 2. Bar Chart – Total Fare by Pickup Borough

Displays the total fare collected from each pickup borough using grouping and aggregation.

### 3. Pie Chart – Trips by Payment Method

Shows the proportion of trips made using different payment methods, such as credit cards and cash.

### 4. Histogram – Distribution of Trip Distance

Illustrates the frequency distribution of taxi trip distances and helps identify common trip lengths.

### 5. Box Plot – Tip Distribution by Pickup Borough

Compares tip amounts across pickup boroughs and helps identify median tips, variability, and potential outliers.

### 6. Count Plot – Number of Trips per Pickup Borough

Displays the number of taxi trips originating from each pickup borough.

### 7. Scatter Plot – Distance vs. Fare

Explores the relationship between trip distance and fare amount. Pickup boroughs are represented using different colors.

### 8. Heatmap – Correlation Matrix

Visualizes correlations among numerical variables, including distance, fare, tip, tolls, and total fare.

### 9. Pair Plot – Relationships Between Numerical Variables

Examines pairwise relationships among distance, fare, tip, and total fare for trips from the five most frequent pickup zones.

### 10. Violin Plot – Fare Distribution by Payment Method

Visualizes the distribution and density of fare amounts across different payment methods.

## 🔍 Key Analysis Areas

* Fare variation over time
* Total fare contribution by pickup borough
* Payment method distribution
* Trip distance patterns
* Differences in tipping behavior across boroughs
* Relationship between trip distance and fare
* Correlations among numerical variables
* Fare distribution across payment methods

## 📚 Learning Outcomes

Through this project, I practiced:

* Data loading and inspection using Pandas
* Missing-value detection and treatment
* Data preprocessing and datetime conversion
* Grouping and aggregation
* Creating different types of charts
* Exploring relationships between numerical and categorical variables
* Performing exploratory data analysis
* Presenting data through meaningful visualizations
