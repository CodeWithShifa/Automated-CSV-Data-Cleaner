# Automated-CSV-Data-Cleaner
A Python script using Pandas to automate the process of handling missing values and removing duplicates from datasets
# 🧹 Automated CSV Data Cleaner

Data cleaning is the most crucial step in any Data Science pipeline. This project automates the "scrubbing" process to ensure that datasets are accurate, consistent, and ready for Machine Learning models.

## 🚀 Overview
Real-world data is often messy, containing empty cells and duplicate entries. This Python script uses the **Pandas** library to identify these issues and fix them automatically, saving hours of manual work.

## 🛠️ Key Features
* **Missing Value Imputation:** Automatically detects null values and fills them using statistical means (Mean/Average).
* **Duplicate Removal:** Identifies and purges redundant rows to maintain data integrity.
* **Automated Export:** Saves the refined data into a new file (`cleaned_house_prices.csv`) without altering the original source.
* **Data Auditing:** Prints a summary of missing values before and after the cleaning process.

## 📁 Project Structure
* `data_cleaner.py`: The core script containing the cleaning logic.
* `house_prices.csv`: The raw, unrefined input dataset.
* `cleaned_house_prices.csv`: The final, "ready-to-use" output dataset.

## 💻 Tech Stack
* **Language:** Python 3.x
* **Library:** Pandas

## 📊 Why This Matters
As the saying goes: *"Garbage In, Garbage Out."* By using this cleaner, we ensure that our Machine Learning models (like the House Price Predictor) receive high-quality data, leading to much more accurate predictions.
