# Visualizing Housing Market Trends: An Analysis of Sale Prices and Features using Tableau

## Project Overview

This project focuses on analyzing housing market trends using Tableau. The objective is to explore housing data, validate its quality, clean the dataset, and prepare it for visualization and dashboard creation.

The dataset contains information about house prices, bedrooms, bathrooms, floor counts, property area, and renovation details.

---

# Step 1: Dataset Collection

## Description

The first step of the project involved collecting the housing dataset required for analysis. The dataset was obtained from Kaggle and downloaded in CSV format.

## Actions Performed

* Downloaded the housing dataset from Kaggle.
* Extracted the dataset files to the local project directory.
* Organized the dataset inside a `dataset` folder for better project structure.

## Dataset Information

| Attribute      | Value  |
| -------------- | ------ |
| File Format    | CSV    |
| Total Records  | 21,609 |
| Total Features | 31     |

## Dataset File

```
dataset/Transformed_Housing_Data2.csv
```

## Proof

Screenshot showing dataset collection step.

![Dataset Collected](screenshots/dataset_collected.png)

---

# Step 2: Loading the Dataset into Tableau

## Description

The downloaded dataset was imported into Tableau Public to enable data exploration and visualization.

## Actions Performed

1. Opened Tableau Public.
2. Selected **Text File** as the data source.
3. Navigated to the dataset location.
4. Imported the CSV file into Tableau.
5. Verified that the dataset loaded successfully.

## Data Source Verification

After importing the dataset, the following checks were performed:

* Verified column headers
* Confirmed the dataset structure
* Ensured that all columns were correctly detected
* Confirmed the dataset size

| Property      | Value  |
| ------------- | ------ |
| Total Rows    | 21,609 |
| Total Columns | 31     |

## Proof

Screenshot showing the dataset loaded into Tableau.

![Dataset Loaded](screenshots/loaded_dataset.png)

---

# Step 3: Data Cleaning and Preparation

## Description

Before creating visualizations, the dataset was reviewed and cleaned to ensure data quality and accuracy.

## Data Review & Exploration

The dataset was explored to understand:

* Data types
* Value ranges
* Data distributions

This helped identify potential outliers and ensured familiarity with the dataset structure.

---

## Field Renaming and Formatting

Some column names were simplified to improve readability.

Example changes:

| Original Field      | Updated Name |
| ------------------- | ------------ |
| No of Bedrooms      | Bedrooms     |
| No of Bathrooms     | Bathrooms    |
| Flat Area (in Sqft) | Living Area  |


This improves clarity when building visualizations.

---

## Data Type Validation

Each column was verified to ensure correct data types:

| Field        | Data Type |
| ------------ | --------- |
| Sale Price   | Numeric   |
| Bedrooms     | Numeric   |
| Bathrooms    | Numeric   |
| Floors       | Numeric   |
| Living Area  | Numeric   |
| Age of House | Numeric   |

---

## Duplicate and Missing Value Check

The dataset was validated for inconsistencies.

* No significant missing values were detected.
* Only **11 duplicate rows** were identified, which is negligible relative to the dataset size.

---

## Optional Calculated Fields

A calculated field was created to enhance analysis.

### Price per Sqft

Formula:

```
[Sale Price] / [Flat Area (in Sqft)]
```

This metric helps analyze property value efficiency.

---

## Data Validation

To ensure accuracy:

* Dataset structure was verified.
* Column formats were confirmed.
* Key numerical fields were validated.

The dataset is now clean and ready for visualization.

## Proof

Screenshot showing dataset prepared in Tableau.

![Data Cleaning](screenshots/data_cleaning.png)

---

# Tools Used

* Tableau Public
* Kaggle Housing Dataset
* GitHub for project documentation

---

# Conclusion

The dataset was successfully:

* Collected
* Imported into Tableau
* Cleaned and validated

The data is now structured and ready for the next stage of the project: **Data Visualization and Dashboard Development**.

Future steps will include creating visualizations to analyze housing market trends and presenting insights through interactive dashboards.
