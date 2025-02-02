# Pharmacy-Sales-Report
# Pharmacy Sales Report - Power BI Basics

## About
This repository contains a Power BI tutorial that demonstrates basic practices in Power BI reporting using standard visualizations, bookmarks, slicers, and drilling.

## Dataset
The dataset used in this tutorial is derived from an initial dataset consisting of 600,000 transactional records collected over a span of 6 years (2014-2019). These records include the date and time of sale, the brand name of the pharmaceutical drug, and the quantity sold. The data was exported from a Point-of-Sale system used in an individual pharmacy.

### Drug Categories
The selected group of drugs from the dataset consists of 57 drugs classified into the following Anatomical Therapeutic Chemical (ATC) Classification System categories:

-  M01AB: Anti-inflammatory and antirheumatic products, non-steroids, Acetic acid derivatives, and related substances
-  M01AE: Anti-inflammatory and antirheumatic products, non-steroids, Propionic acid derivatives
-  N02BA: Other analgesics and antipyretics, Salicylic acid and derivatives
-  N02BE/B: Other analgesics and antipyretics, Pyrazolones and Anilides
-  N05B: Psycholeptics drugs, Anxiolytic drugs
-  N05C: Psycholeptics drugs, Hypnotics, and sedatives drugs
-  R03: Drugs for obstructive airway diseases
-  R06: Antihistamines for systemic use

## Page 1
The first page of the Power BI report provides an overview of the most important information, including the top 5 drugs with the highest and lowest sales, sales per year, and drug types. This page uses visualizations to present the data in an easily understandable format.
![image](https://github.com/Anastasiia-Tetervak/Pharmacy_sales_Power_BI_tutorial/assets/112822472/1cd56700-2b75-480f-a241-477b7b0dd545)

## Page 2
The second page of the Power BI report displays the sales per month. It provides a visual representation of the sales trends over time.
![image](https://github.com/Anastasiia-Tetervak/Pharmacy-Sales-Report---Power-BI-basics/assets/112822472/60d0cbbf-4bb5-421a-92a4-89c2cc1da0e0)

### Resampling
The sales data has been resampled to daily, monthly, quarterly, and yearly periods for analysis. The data has already been pre-processed, which involved outlier detection and treatment, as well as missing data imputation.

## Contents
The repository includes the following files:

1. `Pharmacy_Sales_Report.pbix`: The Power BI file containing the tutorial report.
2. `README.md` (this file): Provides an overview of the tutorial and dataset.
3. `salesmonthly.csv`: data used in the report.

Note: The dataset used in this tutorial is for demonstration purposes only and does not represent actual pharmacy sales data.
