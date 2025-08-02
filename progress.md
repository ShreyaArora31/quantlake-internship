# 🌟 Internship Daily Progress

## 📆 Day 1 - Python Basics - 16th June

A collection of basic Python functions demonstrating core programming concepts, developed in Jupyter Notebook.

### Environment Used:

- **Python**: 3.13.3
- **Anaconda**: 24.11.2
- **IDE**: VS Code with Jupyter Notebook
- **Tools**:
  - Git for version control
  - GitHub for repository hosting
  - Anaconda installed for environment management

### Basic Python Topics:

- Variable and Data Types
- Conditional statements
- Looping structures
- List, tuples, dictionary

### My Workflow:

1. **Repo Setup:** Firstly, I made a new folder on my local computer in order to open the project through VS Code. Then, I created a repository named quantlake-internship on my github account and cloned the empty repository onto my local computer folder.
2. **Environment Setup:** I installed python 3.13.3, anaconda 24.11.2. With the help of anaconda prompt shell, I opened the file of my repository on Jupyter notebook.
3. **Notebook Completion:** I wrote my code on my notebook which I created and the code was simultaneously saving in my local system.
4. **Git and GitHub:** At last, I committed all the changes to my github repository using git commands - add, commit, push with the help of VS Code.

### Learnings:

My key learnings were -

1. How to use jupyter notebook through anaconda, open local folders, create notebooks and write python codes on it.
2. How to use Markdowns in notebooks.
3. Practiced Python fundamentals.
4. Set up a working Python environment.
5. Successfully structured and initialized my internship repository.

## 📆 Day 2 - Python Fundamentals - 19th June

### Environment Used:

- **Python:** 3.13.3
- **Anaconda:** 24.11.2
- **Jupyter Notebook using Anaconda**
- **Version Control:** Git (local) and GitHub (remote)

### Files Added:

- `training/day2_python_fundamentals.ipynb`
- Updated `progress.md`

### Tasks Completed:

**🔹 Task 1: Data Structures Deep Dive**

- Practiced with:

  - `list`, `tuple`, `set`, `dict`

- Performed:

  - List comprehensions
  - Access to nested dictionary values
  - Sorting lists and removing duplicates using sets

**🔹 Task 2: Functions & Modules**

- Wrote custom functions:

  - Factorial calculator
  - Prime number checker

- Used built-in modules:

  - `math`

**🔹 Task 3: Exception Handling**

- Used `try`, `except` blocks
- Handled:

  - Division by zero
  - Invalid input types

**🔹 Task 4: Practice Problems**

- Solved coding challenges:

  - FizzBuzz
  - Largest number in a list
  - String reversal

### Learnings:

- Strengthened understanding of core Python data structures
- Learned how to write reusable functions
- Gained hands-on experience using built-in Python modules
- Practiced handling common runtime exceptions
- Improved logical thinking with small coding tasks

### Challenges Faced:

- Misused set() on nested lists which caused a TypeError

### Outcome:

- Confident with core Python features
- GitHub now contains a well-structured log of Day 1 and Day 2 progress

## 📆 Day 3 - Pandas Introduction - 20th June

### Environment Used:

- **Python**: 3.13.3
- **Pandas**: 2.1.4
- **Jupyter Notebook** via Anaconda
- **Dataset**: Iris dataset from scikit-learn

### Files Added:

- `training/day3_pandas_intro.ipynb`
- Updated `progress.md`

### Tasks Completed:

**🔹 Task 1: Pandas Data Structures**

- Created Series and DataFrames from scratch
- Learned:
  - Difference between Series (1D) and DataFrames (2D)
  - How to construct them from lists/dictionaries
  - Importance of indexes in Pandas

**🔹 Task 2: Data Loading & Inspection**

- Loaded Iris dataset using scikit-learn
- Used key inspection methods:
  - `.info()` - showed 150 rows × 5 columns
  - `.describe()` - revealed stats (mean sepal length: 5.84cm)
  - `.isnull().sum()` - confirmed no missing values
  - `.dtypes` - identified float64 measurements and object type species

**🔹 Task 3: Data Access & Manipulation**

- Practiced:
  - Column selection: `df['col']` vs `df[['col1','col2']]`
  - Label vs position access: `.loc[]` and `.iloc[]`
  - Added calculated column (sepal area)
  - Dropped columns/rows with `.drop()`

**🔹 Task 4: Built-in Methods**

- Applied:
  - `.sort_values()` - ordered flowers by sepal length
  - `.value_counts()` - showed 50 flowers per species
  - `.unique()` - identified 3 species types
  - Statistical methods (`.mean()`, `.max()`, etc.)

### Key Observations/Learnings:

1. **Data Structure Understanding**:

   - Series = Enhanced 1D array
   - DataFrame = Tabular 2D structure with heterogenous columns

2. **Real-world Data Handling**:

   - Automatic alignment by index/labels
   - Missing value handling in statistical methods
   - Vectorized operations (no loops needed)

3. **Notebook Documentation**:
   - Used Markdown headers and bullet points
   - Added clear explanations for each code block
   - Included example outputs

### Challenges Faced:

- Initially confused `.loc[]` (label-based) with `.iloc[]` (position-based)
- Had to experiment with `axis` parameter in `.drop()`

### Outcome:

- Confident with Pandas' core data structures
- Can load, inspect, and clean tabular data
- Notebook ready for GitHub with:
  - Clear section headers
  - Explanatory comments
  - Example outputs

## 📆 Day 4 - Pandas: Data Manipulation I - 23rd June

### Environment Used:

- **Python:** 3.13.3
- **Pandas:** 2.1.4
- **Jupyter Notebook:** using Anaconda
- **Dataset:** [Superstore Sales Data](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

### Files Added:

- `training/day4_data_manipulation_1.ipynb`
- Updated `progress.md`

### Tasks Completed:

**🔹 Task 1: Indexing and Slicing**

- Mastered data access methods:
  - Label-based selection with `.loc[]`
  - Position-based selection with `.iloc[]`
  - Conditional filtering (e.g., `df[df['Sales'] > 500]`)
- Key learning: Difference between view vs copy when slicing

**🔹 Task 2: Filtering & Sorting**

- Applied Boolean filters with multiple conditions (`&`, `|`)
- Sorted data using:
  - Single column: `sort_values('Profit')`
  - Multiple columns: `sort_values(by=['Region', 'Sales'])`

**🔹 Task 3: Handling Missing Data**

- Identified nulls with `isnull().sum()`
- Practiced:
  - Dropping: `dropna()`
  - Filling: `fillna()` (mean, ffill/bfill)
  - Created test DataFrames with `np.nan`
- Learned: FutureWarning fix for `fillna(method=...)`

**🔹 Task 4: GroupBy Operations**

- Performed aggregations:
  - Basic: `groupby('Category').mean()`
  - Advanced: `agg(['sum', 'mean', 'count'])`
- Used `reset_index()` to clean grouped results
- Discovered: Multi-level grouping (Region + Category)

**🔹 Task 5: Merging DataFrames**

- Simulated real-world scenario by splitting dataset
- Practiced join types:
  - Inner, left, and outer joins

### Key Observations/Learnings:

1. **Data Manipulation**:

   - Importance of proper indexing for performance
   - How joins affect dataset size (cardinality)
   - Vectorized operations vs iterative approaches

2. **Real-world Applications**:

   - Handling messy retail data (nulls, mixed types)
   - Business questions answered through grouping
   - Merging transactional and reference data

3. **Methods Practiced**:
   - **Selection:** Learnt .loc[] (labels), .iloc[] (positions), and Boolean filters
   - **Grouping:** Can split-apply-combine data with single/multiple keys
   - **Aggregation:** Used sum, mean, count, and custom aggregations
   - **Output Control:** Applied reset_index() to convert grouped objects to DataFrames

### Challenges Faced:

- Initial confusion between merge types
- GroupBy output formatting (fixed with `reset_index()`)
- FutureWarning for `fillna(method=...)` (updated to `ffill()`)

### Outcome:

- Confident in core Pandas operations
- Learnt how to:
  - Clean and transform raw business data
  - Perform complex aggregations
  - Combine datasets intelligently

## 📆 Day 5 - Pandas: Data Manipulation II - 25th June

### Environment Used:

- **Python:** 3.13.3
- **Pandas:** 2.1.4
- **Jupyter Notebook:** using Anaconda
- **Dataset:** [Superstore Sales Data](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

### Files Added:

- `training/day5_data_manipulation_2.ipynb`
- Updated `progress.md`

### Tasks Completed:

**🔹 Task 1: Reshaping DataFrames**

- Practiced reshaping techniques:
  - `df.pivot()`: Created cross-tab views (e.g., Sales by Region & Category)
  - `pd.pivot_table()`: With multiple aggregation functions
  - `df.melt()`: Converted wide format to long format
- Key learning: Pivot tables ideal for summary dashboards

**🔹 Task 2: Apply Custom Functions**

- Implemented transformation logic:
  - Profit margin classification using `.apply()` with lambda
  - Discount flagging with conditional logic

**🔹 Task 3: Mapping & Replacing**

- Standardized values using:
  - `.map()`: State abbreviations mapping
  - `.replace()`: "Consumer" → "Retail" transformation
- Cleaned categorical data for consistency

**🔹 Task 4: Combining DataFrames**

- Concatenated DataFrames:
  - Vertically with `pd.concat(axis=0)`
  - Horizontally with `pd.concat(axis=1)`
- Handled mismatched columns (automatic NaN filling)

**🔹 Task 5: End-to-End Pipeline**

Built complete data processing workflow:
1. Raw data loading → cleaning (handled outliers/missing values)
2. Grouped & reshaped data
3. Added derived columns
4. Created pivot tables for visualization

### Key Observations/Learnings:

1. **Reshaping Methods**:
   - Pivot tables excel at multi-dimensional summaries
   - Melting useful for visualization-friendly formats
   - `reset_index()` crucial after pivoting

2. **Transformation Logic**:
   - `.apply()` versatile for row/column operations
   - Lambda functions great for simple rules
   - Named functions better for complex business logic

3. **Data Combination**:
   - Vertical concat for adding rows
   - Horizontal concat requires unique indices
   - `merge()` better for key-based joins

### Challenges Faced:

1. **Horizontal Concatenation**:
   - Error: `InvalidIndexError` from duplicate indices
   - Solution: Used `drop_duplicates()` before concat

2. **Performance Classification**:
   - Edge cases with negative profit margins
   - Debugged with: `df['Profit Margin'].describe()`

3. **Pivot Table Formatting**:
   - Multi-index confusion
   - Fixed with `reset_index()` and `margins_name`

### Outcome:

- Confident in reshaping datasets using pivot/melt
- Comfortable applying custom business logic
- Proficient with `.apply()`, `.map()`, and DataFrame combining
- Prepared for complex case studies with:
  - Multi-step transformations
  - Business metric calculations
  - Dashboard-ready formatting

## 📆 Day 6 - Data Visualization - 1st July

### Environment Used:

- **Python:** 3.13.3
- **Matplotlib:** 3.8.4
- **Seaborn:** 0.13.2
- **Jupyter Notebook:** using Anaconda
- **Dataset:** [Superstore Sales Data](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

### Files Added:

- `training/custom_lineplot.png`
- `training/monthly_trends.png`
- `training/seaborn_heatmap.png`
- Updated `progress.md`

### Tasks Completed:

**🔹 Task 1: Created Multiple Visualizations**

- Saved 3 plots as image files:
  1. `custom_lineplot.png`: Monthly sales and profit trends
  2. `monthly_trends.png`: Category-wise sales over time
  3. `seaborn_heatmap.png`: Correlation matrix of numerical features

**🔹 Task 2: Learned Chart Types**

- Mastered 5 essential visualization types:
  - Line plots (trend analysis)
  - Scatter plots (relationship visualization)
  - Histograms (distribution analysis)
  - Heatmaps (correlation visualization)

**🔹 Task 3: Data & Features Visualized**

- Key metrics visualized:
  - Sales trends over 4 years (2014-2017)
  - Profit margins by product category
  - Correlations between Sales, Quantity, Discount, and Profit
  - Outlier detection in Technology category sales

### Key Observations/Learnings:

1. **Tool Selection**:
   - Matplotlib for precise control and customization
   - Seaborn for quick statistical visualizations
   - Use `plt.style.use()` for consistent styling

2. **Visualization Best Practices**:
   - Line plots ideal for time-series data
   - Heatmaps perfect for correlation analysis
   - Histograms reveal data distributions
   - Always label axes and add titles

3. **Publication Quality**:
   - 600 DPI for journal submissions
   - Arial font for professional look
   - Consistent color palettes (colorblind-friendly)
   - Proper figure sizing (9cm width for single-column)

### Chart I'm Most Proud Of:

**`custom_lineplot.png`** - This dual-axis line chart effectively shows:
- Monthly sales trends (primary axis)
- Profit margin percentages (secondary axis)
- Clear annotation of peak sales month
- Professional styling meeting academic standards

### Challenges Faced:

1. **Dual-Axis Formatting**:
   - Secondary axis labels blending with background
   - Solved with `ax2.spines['right'].set_color()`

2. **Heatmap Annotations**:
   - Text overlap in small cells
   - Fixed with `annot_kws={"size": 8}`

3. **Publication Export**:
   - TIFF file size too large
   - Optimized with `pil_kwargs={'compression': 'tiff_lzw'}`

### Outcome:

- Confident in selecting appropriate chart types
- Proficient with Matplotlib/Seaborn customization
- Able to produce publication-quality figures
- Understand when to use:
  - Matplotlib for full control
  - Seaborn for quick statistical plots
- Completed professional visualization workflow:
  1. Data preparation
  2. Visualization creation
  3. Style refinement
  4. Multi-format export
  5. Interpretation/documentation

## 📆 Day 7 - Introduction to SQL & SELECT Queries - 6th July

### Environment Used:

* **Python:** 3.13.3  
* **SQLite3:** Built-in with Python  
* **Pandas:** 2.2.2  
* **Jupyter Notebook:** via Anaconda  
* **Database:** [Chinook](https://www.sqlitetutorial.net/sqlite-sample-database/)

### Files Added:

* `training/day7_sql_intro.ipynb`
* Updated `progress.md`

### 5 Interesting Queries I Wrote:

1. Top 5 Invoice Totals:

   ```sql
   SELECT * FROM invoices ORDER BY Total DESC LIMIT 5;
   ```

2. Countries with Most Invoices:

   ```sql
   SELECT BillingCountry, COUNT(*) FROM invoices GROUP BY BillingCountry ORDER BY COUNT(*) DESC;
   ```

3. Customers with First Name Starting With 'A':

   ```sql
   SELECT * FROM customers WHERE FirstName LIKE 'A%';
   ```

4. Average Sale Per Country:

   ```sql
   SELECT BillingCountry, AVG(Total) FROM invoices GROUP BY BillingCountry;
   ```

5. Employees in Specific Cities:

   ```sql
   SELECT FirstName, LastName FROM employees WHERE City IN ('Calgary', 'Edmonton');
   ```

### Outcome by EOD:

- Learned how to query structured data using SQL
- Practiced SELECT, WHERE, ORDER BY, LIMIT, GROUP BY
- Extracted valuable information from tabular datasets
- Built confidence in using SQL for analytics and reporting

## 📆 Day 8 – SQL & Data Integration – 8th July

### Environment Used:

- **Python:** 3.13.3  
- **SQLite3:** Built-in with Python  
- **Pandas:** 2.2.2  
- **Jupyter Notebook:** using Anaconda  
- **Database:** [Chinook Sample DB](https://www.sqlitetutorial.net/sqlite-sample-database/)

### Files Added:

- `training/day8_sql_integration.ipynb`
- Updated `progress.md`

### Key Observations/Learnings:

1. **Complex SQL Queries**

   * Subqueries with `IN` are powerful for conditional filtering
   * Grouped aggregations help answer high-level business questions easily
   * SQL works best for concise data retrieval and filtering logic

2. **SQL vs Pandas**

   * SQL is cleaner for set-based operations and filtering
   * Pandas excels for in-memory transformation, reshaping, and chaining logic
   * Both tools are essential in a data science workflow

3. **Favorite Integration Technique**

   * `pd.read_sql_query()` combined with `merge()` gives complete control
   * Writing SQL inside Python allows reproducible, scriptable analytics pipelines

### Outcome:

* Performed advanced filtering and aggregation using SQL
* Executed SQL directly from Python without Pandas
* Simulated SQL joins using Pandas `.merge()`
* Understood the synergy between SQL and Pandas in modern data workflows

## 📆 Day 9 – Advanced SQL Analytics & Case-Based Queries – 8th July 

### Environment Used:

- **Python:** 3.13.3  
- **SQLite3:** Built-in with Python  
- **Pandas:** 2.2.2  
- **Jupyter Notebook:** using Anaconda  
- **Database:** [Chinook Sample DB](https://www.sqlitetutorial.net/sqlite-sample-database/)

### Files Added:

- `training/day9_advanced_sql.ipynb`
- Updated `progress.md`

### Key Observations/Learnings:

1. **Multi-table Joins & Aggregations**
   - Queried total revenue and order count per customer using `JOIN` and `GROUP BY`
   - Identified top 5 spending customers with their country using `ORDER BY` + `LIMIT`
   - Calculated total revenue per product category by joining `tracks`, `genres`, and `invoice_items`

2. **Window Functions**
   - Used `ROW_NUMBER()` and `RANK()` to rank customer orders by amount
   - Calculated running total of monthly sales using `SUM() OVER (PARTITION BY)`
   - Found top 3 revenue-generating products per genre using `DENSE_RANK()`

3. **CTEs (Common Table Expressions)**
   - Created CTEs for average order value per customer to filter high-value clients
   - Used a CTE to isolate orders in the last 3 months, then aggregated revenue

4. **Business Insights**
   - Very few products had consistent sales across late 2013
   - Most customers had 1–2 orders only; high-spending customers were rare
   - Product sales were sparse—highlighting the need for active-month filtering
   - Identified products with decreasing sales using a pivot + filtering logic in Pandas

5. **Challenging/Interesting Part**
   - Most challenging: Identifying products with declining sales due to sparse data
   - Learned to dynamically pick active months and use `.pivot_table()` instead of `.pivot()` for robustness
   - Appreciated how SQL + Pandas together helped simulate real BI dashboard scenarios

### Outcome:

- Mastered writing complex multi-table queries and analytics SQL
- Used advanced SQL features like window functions and CTEs
- Identified business patterns such as revenue drop and top customers
- Gained confidence in using SQL as a primary data analysis tool
- Built analysis pipelines mixing SQL and Pandas for real-world insights

## 📆 Credit Risk Analytics Project – 24th July

### 🛠️ Environment Used:

* **Python:** 3.13.3
* **Jupyter Notebook** (via Anaconda)
* **Power BI Desktop** (.pbix file)
* **Excel:** Data source (`.xlsx`)
* **Libraries:** `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

---

### 📂 Files Added:

* `Bank_Personal_Loan_Modelling.xlsx` – Raw dataset
* `Credit Risk Analytics – Identifying Drivers of Loan Default.ipynb` – Data cleaning, EDA, modeling
* `Credit Risk Analysis.pbix` – Interactive Power BI dashboard
* `Credit Risk Analysis Dashboard.png` – Dashboard snapshot
* `Credit Risk Analytics – Top 5 Insights.pdf` – Presentation slides

---

### 📈 Dashboard Snapshot

The Power BI dashboard visualizes high-risk segments, top drivers of default, and overall customer loan behavior.

The Power BI dashboard visualizes high-risk segments, top drivers of default, and overall customer loan behavior.

![Credit Risk Dashboard](./Credit%20Risk%20Analysis%20Dashboard.png)

---

### 🔍 Key Observations & Learnings:

1. **EDA & Feature Understanding**

   * Identified `Income`, `Education`, and `Family` as critical features.
   * Detected outliers in `CCAvg`, `Mortgage`, and `Income`.
   * Classified data types (categorical vs. numerical) for proper handling.

2. **Target Distribution**

   * Only \~10% of customers defaulted on loans, highlighting class imbalance.
   * High proportion of defaults were from **low income** and **non-digitally active** segments.

3. **Dashboard Insights**

   * **RiskSegment = High Risk** users mostly had low income and no credit card or online banking.
   * Family size and age group (30–50) had moderate correlations with defaults.
   * Digitally active users were more likely to take personal loans.

4. **ML Insights (if applicable)**

   * Applied logistic regression and decision trees to validate risk factors.
   * Key predictors: `Income`, `Education`, `CD Account`, `Online`, `CCAvg`.

---

### 📈 Business Insights

* **Low-income, low-education groups** are high risk — should be flagged early in loan approvals.
* **Digital engagement (Online/CC usage)** reduces default risk — banks can promote digital tools.
* **Customers with multiple family members or CD accounts** tend to be safer bets.

---

### 💡 Challenges Faced

* Balancing detailed analysis within limited slide space.
* Handling class imbalance in predictive modeling.
* Choosing dashboard visuals that best convey risk segmentation insights.

---

### ✅ Outcome

* Built an **end-to-end credit risk analysis project** from raw data to insights.
* Created a clean, interactive Power BI dashboard for stakeholder storytelling.
* Delivered a concise PDF with the **Top 5 actionable insights**.
* Practiced working with **structured data, business KPIs, and real-world dashboards**.