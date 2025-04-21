# Task 1 – Cleaned Car Price Dataset

### ✅ Task Summary:
This task involved cleaning a raw car price dataset. The goal was to prepare it for further analysis or modeling.

### 🛠️ What I Did:
- Removed rows with missing key fields (`make`, `model`, `sellingprice`)
- Dropped duplicate records
- Cleaned text columns (converted to lowercase, stripped whitespace)
- Standardized date and numeric formats
- Retained `condition` and `saledate` columns for reference (despite missing data)

### 📂 Files Included:
- `task1.ipynb`: Code for cleaning the dataset
- `cleaned_car_prices.csv`: Final cleaned dataset
- (Optional) Screenshots of data before/after cleaning
- `README.md`: This file

---

### 📌 Note:
The original dataset was loaded from a local path (`F:\car_prices.csv`). To run this notebook, change the path or use a relative file path like:
```python
df = pd.read_csv('car_prices.csv')
