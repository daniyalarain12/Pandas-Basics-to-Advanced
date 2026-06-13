# 🐼 Pandas — Basics to Advanced

> A structured, topic-by-topic Pandas learning repository covering everything from DataFrames and Series to Time Series Analysis — with 18 well-organized Jupyter Notebooks and real-world dataset practice.
> 
> Built as **Part 2** of my Data Science & AI Engineering journey — following the Python and NumPy repositories.

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Latest-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Notebooks](https://img.shields.io/badge/Notebooks-18-red?style=for-the-badge)
![DataScience](https://img.shields.io/badge/Data_Science-Journey-purple?style=for-the-badge)

---

## 📖 About This Repository

This repository is a **complete, production-quality Pandas learning resource** organized into 18 focused Jupyter Notebooks. It progressively builds your skills from absolute basics all the way to advanced topics including time series analysis, pivot tables, multi-DataFrame merging, and real-world data cleaning.

Every notebook is focused on a **single concept**, written with clean, well-commented code and structured markdown explanations — making it an ideal reference for anyone on a Data Science or Machine Learning journey.

---

## 🗺️ My Data Science Journey

This repository is **Part 2** of a series of structured learning repositories:

| # | Repository | Topics | Status |
|---|-----------|--------|--------|
| 1 | [Python — Basics to Advanced](https://github.com/daniyalarain12/Python-Basics-to-Advanced) | 14 Chapters · 5 Projects · 100+ Problems | ✅ Completed |
| 2 | [NumPy — Basics to Advanced](https://github.com/daniyalarain12/NumPy-Basics-To-Advanced) | 11 Notebooks · Arrays · Linear Algebra | ✅ Completed |
| 3 | **Pandas — Basics to Advanced** *(this repo)* | 18 Notebooks · DataFrames · Time Series | ✅ Completed |
| 4 | Matplotlib & Seaborn | Data Visualization | 🔜 Coming Soon |
| 5 | Scikit-Learn | Machine Learning | 🔜 Coming Soon |

---

## 🗂️ Repository Structure

```
Pandas-Basics-to-Advanced/
│
├── 📓 01_introduction_to_pandas.ipynb
├── 📓 02_creating_dataframes_and_series.ipynb
├── 📓 03_data_inspection.ipynb
├── 📓 04_data_selection_filtering_and_aggregation.ipynb
├── 📓 05_working_with_indexes.ipynb
├── 📓 06_loc_iloc_at_and_iat.ipynb
├── 📓 07_adding_modifying_and_deleting_columns.ipynb
├── 📓 08_renaming_ranking_and_reordering.ipynb
├── 📓 09_handling_missing_values.ipynb
├── 📓 10_replace_map_apply_and_assign.ipynb
├── 📓 11_sorting_data.ipynb
├── 📓 12_groupby_and_aggregation.ipynb
├── 📓 13_merging_dataframes.ipynb
├── 📓 14_concatenation.ipynb
├── 📓 15_pivot_pivot_table_and_melt.ipynb
├── 📓 16_stacking_and_unstacking.ipynb
├── 📓 17_crosstab_and_contingency_tables.ipynb
└── 📓 18_time_series_analysis.ipynb
```

---

## 🧩 Topics Covered

### 🟢 Beginner

#### Notebook 01 — Introduction to Pandas
- What is Pandas and why use it
- Understanding Series and DataFrames
- Data Munging and Data Wrangling concepts
- Reading data from CSV, Excel, and JSON
- Writing data to CSV and Excel files
- Overview of missing value handling

#### Notebook 02 — Creating DataFrames and Series
- Creating DataFrames from dictionaries of lists
- Creating DataFrames from lists of dictionaries
- Creating Series from different data structures
- Custom indexes in Series
- Exporting DataFrames to CSV, Excel, and JSON

#### Notebook 03 — Data Inspection
- Viewing first rows with `head()`
- Viewing last rows with `tail()`
- Displaying dataset information with `info()`
- Understanding DataFrame structure and dtypes

#### Notebook 04 — Data Selection, Filtering & Aggregation
- Selecting single and multiple columns
- Slicing rows from a DataFrame
- Filtering with single and multiple conditions
- Using `query()` for clean conditional filtering
- Aggregation operations
- Generating descriptive statistics with `describe()`

#### Notebook 05 — Working with Indexes
- Understanding what indexes are
- Viewing DataFrame index range
- Setting a custom index with `set_index()`
- Resetting indexes with `reset_index()`

---

### 🟡 Intermediate

#### Notebook 06 — loc, iloc, at, and iat
- Label-based row and column selection with `loc`
- Position-based selection with `iloc`
- Fast single cell access with `at` and `iat`
- Slicing rows and selecting specific columns
- Key differences between `loc` and `iloc`

#### Notebook 07 — Adding, Modifying & Deleting Columns
- Adding new columns at the end of a DataFrame
- Inserting columns at specific positions with `insert()`
- Modifying individual cell values
- Updating entire columns
- Deleting single and multiple columns with `drop()`

#### Notebook 08 — Renaming, Ranking & Reordering
- Renaming all column names at once
- Renaming specific columns with `rename()`
- Renaming row labels
- Assigning ranks to data with `rank()`
- Reordering and repositioning columns

#### Notebook 09 — Handling Missing Values
- Detecting missing values with `isnull()`
- Counting missing values per column
- Removing missing data with `dropna()`
- Filling missing values with `fillna()`
- Forward fill (`ffill`) and backward fill (`bfill`)
- Linear and time-based interpolation
- Using `how` and `thresh` parameters in `dropna()`
- Reindexing DataFrames with date ranges
- Detecting and removing duplicate rows

#### Notebook 10 — Replace, Map, Apply & Assign
- Replacing invalid values with `replace()`
- Multiple and regex-based replacements
- Converting categorical values to numeric form
- Series transformation with `map()`
- Row and element-wise operations with `apply()`
- Creating new columns using `apply()` and `lambda`
- Functional-style DataFrame updates with `assign()`

#### Notebook 11 — Sorting Data
- Sorting with a single column using `sort_values()`
- Ascending and descending order sorting
- Multi-column sorting with independent sort orders
- Using the `ascending` parameter as a list

---

### 🔴 Advanced

#### Notebook 12 — GroupBy & Aggregation
- Grouping data by single and multiple columns
- Applying `sum`, `mean`, `max` aggregations
- Iterating through grouped data
- Accessing specific groups
- Using `describe()` on grouped data
- Multiple aggregations with `agg()`
- Renaming aggregated columns

#### Notebook 13 — Merging DataFrames
- Combining DataFrames with `merge()`
- Inner, Outer, Left, Right, and Cross joins
- Identifying data source after merge with `indicator`
- Handling common column names with `suffixes`

#### Notebook 14 — Concatenation
- Vertical (row-wise) concatenation with `concat()`
- Horizontal (column-wise) concatenation
- Using `keys` for hierarchical indexing
- Concatenating DataFrames with Series
- Understanding index alignment in concatenation

#### Notebook 15 — Pivot, Pivot Table & Melt
- Transforming long → wide format with `pivot()`
- Aggregation and summarization with `pivot_table()`
- Time-based grouping with `Grouper`
- Reshaping wide → long format with `melt()`
- Customizing melted column names

#### Notebook 16 — Stacking & Unstacking
- Understanding `stack()` in Pandas
- Converting column levels into row levels
- Working with MultiIndex DataFrames
- Restoring original structure with `unstack()`

#### Notebook 17 — Crosstab & Contingency Tables
- Understanding contingency tables
- Using `pd.crosstab()` for categorical analysis
- Analyzing relationships between categorical variables
- Adding row and column totals with `margins`
- Computing percentage distributions with `normalize`
- Applying aggregation with `values` and `aggfunc`

#### Notebook 18 — Time Series Analysis
- Understanding time series data structure
- Working with datetime index
- Slicing data using date ranges
- Resampling data (monthly, yearly, etc.)
- Generating custom date ranges
- Using business day frequency
- Forward filling for missing dates
- Shifting and lagging time series data
- Calculating returns and changes in real stock prices (Apple)

---

## 📊 Repository Stats

| Detail | Count |
|--------|-------|
| Total Notebooks | 18 |
| Concepts Covered | 100+ |
| Difficulty Levels | 3 (Beginner → Intermediate → Advanced) |
| Real Datasets Used | ✅ Yes |
| Language | Python 100% |

---

## 🛠️ Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Pandas, NumPy, OpenPyXL

### Install Dependencies
```bash
pip install pandas numpy jupyter openpyxl xlrd
```

### Clone the Repository
```bash
git clone https://github.com/daniyalarain12/Pandas-Basics-to-Advanced.git
cd Pandas-Basics-to-Advanced
```

### Launch Jupyter Notebook
```bash
jupyter notebook
```

Open any notebook and run the cells from top to bottom.

---

## 🎯 What You Will Learn

By working through all 18 notebooks in order, you will be able to:

- ✅ Understand Pandas as the backbone of data analysis in Python
- ✅ Create and inspect DataFrames and Series from any data source
- ✅ Select, filter, and aggregate data with full confidence
- ✅ Handle missing values and clean messy real-world datasets
- ✅ Transform and engineer features using map, apply, and assign
- ✅ Group and aggregate data for business-level insights
- ✅ Merge and concatenate multiple DataFrames like a pro
- ✅ Reshape data using pivot tables, melt, stack, and unstack
- ✅ Analyze categorical relationships with crosstab
- ✅ Perform professional time series analysis on real stock data

---

## 🗺️ Learning Path

```
01 Intro ──► 02 DataFrames & Series ──► 03 Inspection ──► 04 Selection & Filtering
                                                                      │
                                                                      ▼
08 Renaming & Ranking ◄── 07 Columns ◄── 06 loc & iloc ◄── 05 Indexes
      │
      ▼
09 Missing Values ──► 10 Replace & Apply ──► 11 Sorting ──► 12 GroupBy
                                                                   │
                                                                   ▼
16 Stack & Unstack ◄── 15 Pivot & Melt ◄── 14 Concat ◄── 13 Merging
      │
      ▼
17 Crosstab ──► 18 Time Series ✅
```

> 💡 Follow the notebooks in order for the best learning experience.

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!
- Open an **Issue** for bug reports or suggestions
- Submit a **Pull Request** with improvements or new examples

---

## 👨‍💻 Author

**Daniyal Arain**
- GitHub: [@daniyalarain12](https://github.com/daniyalarain12)

---

## ⭐ Show Your Support

If this repository helped you learn Pandas, please consider giving it a **⭐ star** — it helps others discover it too!

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

*Part of my ongoing Data Science & AI Engineering journey* 🚀

</div>
