Overview
This script extracts and processes commit-level information from multiple GitHub repositories using pydriller. It generates CSV files containing details of developer interactions with Python files in the repositories.

Dependencies
Ensure you have the following Python packages installed:
pip install pydriller pandas networkx scipy scikit-learn matplotlib seaborn numpy

Usage
Run the script to collect commit-level data from the specified repositories.
The script saves two CSV files:
df_repo.csv: Data extracted from the first set of repositories.
df_repo2.csv: Data extracted from the second set of repositories.
df_merged.csv: Merged dataset with anonymized author names.

How It Works
Extracts commit information using pydriller from given repositories.
Captures details like author, modified files, first authorship, file interactions, and commit activity.
Measures execution time for data extraction.
Merges datasets from different repositories and anonymizes developer names.

Output
After execution, you will find:
df_repo.csv
df_repo2.csv
df_merged.csv
