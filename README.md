# Pandas Data Analysis Course 🐼

A comprehensive, hands-on course designed to help you master data manipulation with Python's Pandas library. This repository contains step-by-step lessons and practice exams (with solutions) covering everything from basic concepts to advanced data aggregation.

## 📚 Course Structure

The course is divided into 4 levels, each focusing on essential data analysis skills. Each level includes a **Lesson Notebook** for learning and an **Exam Notebook** for practice.

### Level 1: Basics & Loading Data 🟢
- **Lesson:** [`01_pandas_basics.ipynb`](01_pandas_basics.ipynb)
    - Introduction to Pandas Series & DataFrame.
    - Creating data structures manually.
    - Loading data from CSV and JSON files.
    - Basic data inspection techniques.
- **Practice:** [`01_pandas_basics_exam.ipynb`](01_pandas_basics_exam.ipynb)
    - Hands-on exercises for creating Series/DataFrames.
    - Practice loading and exploring datasets.

### Level 2: Data Cleaning 🟡
- **Lesson:** [`02_pandas_cleaning.ipynb`](02_pandas_cleaning.ipynb)
    - Handling missing values (NaN).
    - Identifying and removing duplicate data.
    - Data type conversion (e.g., string to numeric).
    - String operations for text cleaning.
- **Practice:** [`02_pandas_cleaning_exam.ipynb`](02_pandas_cleaning_exam.ipynb)
    - Scenarios involving "messy" data that require cleaning before analysis.

### Level 3: Data Manipulation 🟠
- **Lesson:** [`03_pandas_manipulation.ipynb`](03_pandas_manipulation.ipynb)
    - Selecting specific data using `.loc` and `.iloc`.
    - Filtering rows based on complex conditions.
    - Adding new calculated columns and removing unnecessary ones.
    - Applying custom functions to data.
    - Sorting and ranking data.
- **Practice:** [`03_pandas_manipulation_exam.ipynb`](03_pandas_manipulation_exam.ipynb)
    - Exercises on filtering, feature engineering, and data transformation.

### Level 4: Aggregation & Merging 🔴
- **Lesson:** [`04_pandas_aggregation.ipynb`](04_pandas_aggregation.ipynb)
    - GroupBy operations (Split-Apply-Combine) for summarization.
    - Creating Pivot Tables for cross-tabulation.
    - Merging and joining multiple DataFrames (Inner, Left, Outer joins).
    - Concatenating datasets.
- **Practice:** [`04_pandas_aggregation_exam.ipynb`](04_pandas_aggregation_exam.ipynb)
    - Advanced exercises on summarizing complex datasets and combining tables.

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/pandas-course.git
   cd pandas-course
   ```

2. **Install dependencies:**
   Ensure you have Python installed. Then install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
   *Core libraries: `pandas`, `numpy`, `jupyter`.*

3. **Start Learning:**
   Launch Jupyter Notebook to open the files:
   ```bash
   jupyter notebook
   ```
   or separate VS Code:
   ```bash
   code .
   ```

## 📝 How to Use
1. Open the **Lesson** notebook (e.g., `01_pandas_basics.ipynb`) to read and run the examples.
2. Once you understand the concepts, open the corresponding **Exam** notebook (e.g., `01_pandas_basics_exam.ipynb`).
3. Attempt the exercises in the empty cells provided.
4. Expand the **"Solution"** block to check your answer and learn the correct approach.

---
**Happy Coding!** 🚀
