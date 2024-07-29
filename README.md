# [Exploring the Long-Term Value of a Degree](https://medium.com/@tullyro/exploring-the-long-term-value-of-a-degree-7649475173b5)
**Analysis of College Majors, Salaries, and Student Debt**

## Project Overview

This notebook analyzes the relationship between college majors, starting and mid-career salaries, student debt, regional differences, and the type of college attended. The datasets used for this analysis are:

1. **Degrees That Pay Back**: This dataset contains information on starting and mid-career salaries for various undergraduate majors. It includes data on percent changes from starting to mid-career salaries, as well as percentile salary data.
   - Source: [Kaggle: College Salaries](https://www.kaggle.com/datasets/wsj/college-salaries)
   
2. **Salaries by College Type**: This dataset provides salary data categorized by the type of college (e.g., Engineering, Liberal Arts).
   - Source: [Kaggle: College Salaries](https://www.kaggle.com/datasets/wsj/college-salaries)
   
3. **Salaries by Region**: This dataset contains information on salaries categorized by region (e.g., California, Midwestern, Southern).
   - Source: [Kaggle: College Salaries](https://www.kaggle.com/datasets/wsj/college-salaries)
   
4. **Student Loan Debt by Major**: This dataset provides median student loan debt data for various college majors.
   - Source: [Education Data Initiative: Student Loan Debt by Major](https://educationdata.org/student-loan-debt-by-major)

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Files in the Repository

- `Exploring the Long-Term Value of a Degree.ipynb`: Jupyter notebook containing the complete code for the project.
- `degrees-that-pay-back.csv`: Dataset containing information on starting and mid-career salaries for various undergraduate majors.
- `salaries-by-college-type.csv`: Dataset providing salary data categorized by the type of college.
- `salaries-by-region.csv`: Dataset containing information on salaries categorized by region.
- `Bachelors Degree Debt Table.csv`: Dataset providing median student loan debt data for various college majors.
- `README.md`: Documentation of the project.

## Summary of Results

- Analysis of starting and mid-career salaries across different undergraduate majors.
- Correlation between student debt and mid-career salaries.
- Comparison of mid-career salaries by region and college type.
- Visualization of salary percentiles across different fields.

## Business Questions Addressed

1. **What are the starting and mid-career salaries for various undergraduate majors?**
   - **Solution**: Visualization of starting and mid-career median salaries, along with percent change.
2. **How does student debt correlate with mid-career salaries for different majors?**
   - **Solution**: Analysis and visualization comparing mid-career median salaries with median student debt.
3. **How do mid-career salaries vary by region?**
   - **Solution**: Boxplot visualization of mid-career median salaries by region.
4. **How do mid-career salaries vary by college type?**
   - **Solution**: Boxplot visualization of mid-career median salaries by college type.
5. **What are the salary percentiles for different majors at mid-career?**
   - **Solution**: Visualization of mid-career salary percentiles across various fields.

## Blog Post

You can read more about this analysis in my blog post: [Exploring the Long-Term Value of a Degree](https://medium.com/@tullyro/exploring-the-long-term-value-of-a-degree-7649475173b5)

## Acknowledgements

- Kaggle for providing the College Salaries dataset.
- Education Data Initiative for providing the Student Loan Debt by Major dataset.

## Motivation

The motivation for this project is to apply data science techniques to a real-world dataset and derive actionable insights that can be communicated effectively to stakeholders.

## How to Use This Repository

1. Clone the repository:
   ```sh
   git clone https://github.com/<your-username>/Exploring the Long-Term Value of a Degree.git
2. Navigate to the project directory
   ```sh
   cd Exploring the Long-Term Value of a Degree
3. Open the Jupyter notebook:
   ```sh
   jupyter notebook "Exploring the Long-Term Value of a Degree.ipynb"