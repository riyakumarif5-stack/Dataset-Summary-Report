# Dataset-Summary-Report
A Pandas-based dataset summary report in Google Colab — explores a student dataset's structure, statistics, and missing values.
# 📊 Dataset Summary Report — Student Dataset

A Google Colab notebook that explores a student dataset using **Pandas** — loading the CSV, inspecting its structure, and pulling out descriptive statistics and observations about data quality. Built as a hands-on data exploration exercise, with every cell already executed against the real dataset so outputs are visible directly in the notebook.

## What's Covered

| Section | Concepts |
|---|---|
| Load Dataset | Reading a CSV into a DataFrame with `pd.read_csv()` |
| First & Last Rows | `head()`, `tail()` |
| Random Sample | `sample()` |
| Shape, Columns & Index | `shape`, `columns`, `index` |
| Data Types | `dtypes` |
| Structure Summary | `info()` — column names, non-null counts, dtypes in one view |
| Descriptive Statistics | `describe()` — count, mean, std, min, quartiles, max |
| Missing Values | `isnull().sum()` |
| Observations | Written notes on row/column counts, dtypes, missing data, and value ranges |

## Dataset

`Day7_Student_Dataset.csv` — 25 rows, 7 columns:
`Student_ID`, `Name`, `Age`, `Course`, `Marks`, `Attendance_Percentage`, `City`

## Project Structure

```
Dataset_Summary_Report.ipynb   # main notebook (open in Colab or Jupyter)
Day7_Student_Dataset.csv       # dataset used by the notebook
```

## How to Run

### Option 1: Google Colab (recommended)
1. Open [Google Colab](https://colab.research.google.com).
2. Go to **File → Upload notebook** and select `Dataset_Summary_Report.ipynb`, or open it directly from this GitHub repo via **File → Open notebook → GitHub**.
3. Upload `Day7_Student_Dataset.csv` to the Colab session (Files panel on the left, or drag-and-drop).
4. Run all cells — outputs are already included, but you can re-run everything (**Runtime → Run all**) to confirm it yourself.

No installation needed — Pandas comes preloaded in Colab.

### Option 2: Jupyter Notebook (locally)
```bash
jupyter notebook Dataset_Summary_Report.ipynb
```
Make sure `Day7_Student_Dataset.csv` is in the same folder as the notebook. Requires Python 3.7+ and Pandas:
```bash
pip install pandas
```

## Author

Riya
