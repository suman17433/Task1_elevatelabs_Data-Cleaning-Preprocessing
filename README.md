# Task1_elevatelabs_Data-Cleaning-Preprocessing
Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats)

# 📊 Marketing Campaign — Data Cleaning & Preprocessing

## 🧠 Project Overview
This project focuses on **cleaning and preprocessing** the real-world dataset `marketing_campaign.csv` using **Python (Pandas)** in **Google Colab**.

It demonstrates how to:
- 🧹 Handle missing values  
- 🔁 Remove duplicate entries  
- ✏️ Standardize text data  
- 📅 Convert date columns  
- 🔡 Rename columns  
- 📊 Verify and fix data types  

This is a **Data Analyst Internship Task** designed to build strong data preprocessing skills.


## 📁 Repository Structure

| 📂 Folder/File | 📘 Description |
|----------------|----------------|
| `task1_elevate.ipynb` | Main Google Colab notebook with all cleaning steps |
| `marketing_campaign.csv` | Original dataset |
| `cleaned_customer_personality.csv` | Cleaned dataset after processing |
| `README.md` | Project documentation (this file) |


## ⚙️ Technologies Used

| Tool | Purpose |
|------|----------|
| 🐍 Python | Main programming language |
| 🧾 Pandas | Data handling & cleaning |
| 📉 NumPy | Numerical operations |
| ☁️ Google Colab | Cloud-based environment for execution |
| 💻 GitHub | Version control & sharing |

# 9) Summary
```python
    summary = summarize_changes(original_df, df)
    print("\n=== Cleaning Summary ===")
    print(f"Original shape: {summary['original_shape']}")
    print(f"Cleaned shape: {summary['cleaned_shape']}")
    print(f"Duplicate rows dropped (if any): {summary['dropped_duplicates']}")
    # print a few sample missing counts (only non-zero)
    nonzero_missing = {k:v for k,v in summary['missing_after_cleaning'].items() if v>0}
    print("Columns with missing values after cleaning (non-zero):", nonzero_missing)

if __name__ == "__main__":
    main()
```
