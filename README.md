# Pandas for AI/ML - Conceptual and Technical Assessment

## Student Details

**Name:** N.V. Datha Sai Divya Pamidimarri  
**Submission File:** `Divya_Pandas.ipynb`  
**Topic:** Pandas and NumPy for data manipulation, analysis, and cleaning in AI/ML workflows

## Project Overview

This repository contains the completed Pandas assignment notebook for the AI/ML conceptual and technical assessment. The work is arranged section by section, following the assignment format, and shows how Pandas and NumPy can be used for output prediction, code correction, data preprocessing, and practical data-cleaning tasks.

The notebook includes code, visible outputs, and short explanations so that each answer is easy to follow and review.

## Files Included

| File | Description |
| --- | --- |
| `README.md` | Gives an overview of the assignment, the notebook contents, and the steps to run the file. |
| `Divya_Pandas.ipynb` | Main Jupyter Notebook containing all assignment sections, code cells, outputs, and explanations. |

## Notebook Structure

The notebook is divided into four sections:

### Section A - Output Prediction

This section checks the ability to read Pandas and NumPy code and predict the expected output. It covers:

- Vectorized operations on NumPy arrays and Pandas Series
- Boolean filtering in DataFrames
- Descriptive statistics such as mean, maximum, and median
- Group-wise analysis using `groupby()`
- Positive and negative correlation using Pandas

### Section B - Code Correction

This section identifies common mistakes in Pandas code and shows the corrected implementation. It covers:

- Correct CSV reading when a header row is present
- Sorting values to display the highest salary records
- Updating missing values using `fillna()`
- Calculating correlation between two columns correctly

### Section C - Edge Cases

This section looks at special cases that can affect the accuracy of data analysis. It covers:

- NumPy broadcasting with different array shapes
- CSV parsing with quoted commas, missing values, and mixed date formats
- The effect of extreme values on mean and median
- Investigating outliers before removing or replacing them

### Section D - Scenario-Based Problems

This section applies Pandas to a student assessment dataset that contains common data-quality issues. It covers:

- Loading and inspecting a CSV dataset
- Standardizing inconsistent department names
- Removing duplicate records
- Converting mixed-format marks into numeric values
- Distinguishing absent students from missing entries
- Identifying invalid marks outside the valid range
- Reporting cleaned data and summary counts

The sample dataset for this section is included directly inside the notebook. This keeps the repository simple and ensures that only the required notebook and README files are needed.

## How to Run the Notebook

1. Open `Divya_Pandas.ipynb` in Jupyter Notebook, JupyterLab, VS Code, or Google Colab.
2. Run the cells from top to bottom.
3. Confirm that all outputs are visible after running the notebook.
4. Review the explanations along with the code and output for each question.

## Requirements

The notebook uses the following Python libraries:

- `pandas`
- `numpy`

Install them if they are not already available:

```bash
pip install pandas numpy
```

## Submission Notes

- Submit only the `.ipynb` notebook file if that is the required submission format.
- Keep the filename as `Divya_Pandas.ipynb`.
- Make sure all cells are executed before final submission.
- Check that the notebook opens correctly and does not contain unexpected errors.
