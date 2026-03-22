
# Study and Implementation of Categorical Data Analysis in Python

## Aim
To study and implement various techniques for analyzing categorical data using the Pandas library, including frequency distribution, cross-tabulation, and grouping.

---

## Objectives
- Understand the difference between nominal and ordinal categorical data  
- Perform frequency counting and percentage distribution  
- Apply cross-tabulation to analyze relationships between variables  
- Perform grouping and sorting based on categorical features  
- Filter and extract subsets from a dataset  

---

## Theory
Categorical data refers to data that can be divided into distinct groups or categories. In Python, the Pandas library provides efficient tools to analyze such data and extract meaningful insights about patterns and relationships.

---

## 1. Frequency Distribution
Frequency distribution involves counting how many times each unique value appears in a dataset.

- Helps identify the most and least common categories  
- Normalized frequency shows percentage distribution  

---

## 2. Cross-Tabulation (Crosstab)
Cross-tabulation is used to analyze the relationship between two categorical variables.

- Creates a contingency table  
- Useful for comparing categories (e.g., Gender vs Grades, Payment vs Product Type)

---

## 3. Unique Value Identification
- `unique()` → returns distinct values  
- `nunique()` → returns count of unique categories  

---

## Metadata and Exploration

### Value Counts
Used to determine frequency of categories such as product types or student grades.

### Percentage Distribution
Using `normalize=True` converts counts into proportions (e.g., 40% of data belongs to a category).

### Sorting and Filtering
- Sort data alphabetically or numerically  
- Filter specific categories (e.g., only "Electronics")

---

## Advanced Categorical Analysis

### Crosstab
Helps find relationships between variables (e.g., delivery type vs customer type).

### Groupby
Used for multi-level analysis such as:
- Grade distribution within departments  
- Sales distribution across product categories  

---

## Applications

- **Market Research:** Analyze customer preferences  
- **Academic Analysis:** Study student performance  
- **Inventory Management:** Track product demand  
- **Logistics:** Optimize delivery and payment methods  

---

## Conclusion
Categorical data analysis is essential for extracting meaningful insights from non-numerical data. Techniques like value counts, cross-tabulation, and grouping help summarize data effectively and reveal relationships between variables.
