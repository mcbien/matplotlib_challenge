# matplotlib_challenge
Michael Bien-Matplotlib Homework
This analysis examines a study in drug regimens in the treament of tumors in mice.

FILES:
Analyis file: Bien_pymaceuticals.ipynb
Observations: Michael Bien – Matplotlib Homework Observations
Raw Data files in data folder: Mouse_metadata.csv, Study_results.csv

BRIEF OF ANALYSIS APPROACH:
1. Merged Raw Data files into combined data
2. Located and removed the duplicate entries for Mouse ID g989 into the clean_data DataFrame
3. Created Summary Statistic tables using 2 methods: 1. Multiple series method, 2. Single groupby method (.agg)
4. Created bar charts of Mouse ID count by Drug Regimen using 2 methods: 1. pyplot, 2. Matplotlib
5. Created pie charts of Mouse ID count by Gender using 2 methods: 1. pyplot, 2. Matplotlib
6. Determine the Max Timepont for each mouse
7. Limited the data to Ramican, Capomulin, infubinol and Ceftamin
8. Created a boxplot by the four regimens with clear outliers
9. Created a line chart of Timepoint vs. Tumor Volume for mouse s185
10. Created a scatterplot of the Weight vs. Average Tumor Volumne for the Capomulin Regimen and added a regression line
