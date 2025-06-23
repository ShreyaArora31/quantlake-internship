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
