# data-analysis-project
Exploratory data analysis and data tagging project involving data cleaning, feature generation, and insight extraction using Python.

# Data Tagging and Exploratory Data Analysis Project

## Description
This project focuses on data tagging, data cleaning, and exploratory data analysis of a dataset containing technical complaint records. The dataset includes free-text fields describing issues, causes, and corrective actions. The objective was to convert unstructured information into structured categories and derive meaningful insights from the data.

## Project Objectives
- Convert free-text complaint data into structured tags
- Clean and standardize the dataset
- Perform exploratory data analysis (EDA)
- Identify important patterns and potential root causes
- Generate insights that can support better decision-making

## Data Tagging Approach
The tagging process involved carefully analyzing each record by reviewing the **Complaint, Cause, and Correction** fields together. This allowed a clear understanding of what problem occurred, why it happened, and how it was resolved.

### Root Cause Identification
The primary cause of the issue was identified and categorized based on logical reasoning. Common categories included:

- Installation-related issues (e.g., not installed, not tightened, loosened)
- Quality-related problems (e.g., poor material, faulty parts)
- Missing components (e.g., missing parts, missing seals)
- Specification issues (e.g., out of range, incorrect fitting)

When the cause was unclear, the symptom description and corrective action were used to infer the most appropriate category.

### Symptom Tagging
The symptom condition represented the visible or reported issue observed during operation. Examples included:

- Leak
- Missing component
- Broken part
- Error codes
- Equipment not functioning

The **symptom component** identified the specific physical part involved in the issue.

### Fix Identification
Corrective actions were categorized based on the primary action taken, such as:

- Installed
- Replaced
- Retightened
- Repaired
- Reset
- Cleaned

The **fix component** represented the part that was repaired or replaced during the corrective process.

## Data Processing and Analysis
After tagging the dataset, the data was cleaned and analyzed using Python. The analysis included:

- Column-wise dataset analysis
- Handling missing or inconsistent values
- Standardizing categorical fields
- Generating tags from free-text data
- Creating visualizations to identify key patterns

Libraries used for analysis included:

- Pandas
- NumPy
- Matplotlib
- Seaborn

## Key Insights
The analysis revealed several recurring patterns:

- Many failures were related to installation quality and improperly fitted components.
- Components such as seals, couplers, and fittings appeared frequently in failure cases.
- Recurring sensor and electrical issues indicated possible contamination or calibration challenges.
- Several issues were associated with loose or missing parts, highlighting the importance of improved inspection procedures.

## Conclusion
This project demonstrates how unstructured technical records can be transformed into structured datasets through systematic tagging and analysis. The insights derived from the analysis can support improvements in quality control, preventive maintenance, and manufacturing processes.
