# End-to-End Data Auditing & Feature Engineering Pipeline

A production-ready Python pipeline built using **NumPy** and **Pandas** to ingest, audit, clean, and extract business intelligence from a high-loss multi-feature dataset.

## 🛠️ Tech Stack & Concepts Used
- **Python 3.x**
- **Pandas:** DataFrame manipulation, column axis pruning, missing data imputation, grouping, multi-metric aggregations.
- **NumPy:** Vectorized arrays, element-wise math transformations, nested conditional structures (`np.where`).
- **Development Environment:** VS Code with Jupyter Notebook Extensions.

## 📈 Data Pipeline Architecture
1. **Data Audit:** Evaluated shape (`891, 12`), scanned null distribution using `.isna().sum()`, and permanently pruned features crossing a 70% data-loss threshold.
2. **Imputation Engineering:** Patched numeric features via zero-outlier calculations (`np.nanmedian`) and structural text defaults.
3. **Feature Engineering:** Calculated real-time global currency vectors and grouped demographic records using nested bitwise validation rules.
4. **Business Intelligence Aggregation:** Summarized system revenue performance across demographic clusters using multi-tiered index matrices.

## 🚀 How To Run
1. Clone the repository: `git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git`
2. Open the directory in VS Code.
3. Ensure packages are installed: `pip install numpy pandas notebook`
4. Execute `pipeline.ipynb` to watch the tracking engine transform raw data to insights.
