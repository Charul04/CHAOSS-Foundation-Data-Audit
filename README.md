# CHAOSS Foundation Data Audit
Hi! This is my analysis of the project metadata from the CHAOSS datasets. I wanted to see how the data looks for different foundations and if there are any big gaps in the information.

# What I did
I used PythoncPandas to analyze the structured_project_analysis.csv file and created several visualizations. 

# My Main Findings
Technical Missing Values: I performed a NaN analysis to ensure the dataset wouldn't cause errors during visualization.

Security Check: I checked how many projects use https vs http to see if links are secure.

Data Gaps: I counted the "Unknown" fields in each row to see which projects are missing the most info.

Top Performing Projects: I checked for projects with 100% completion and found that no project is currently 100% complete in this dataset.

Duplicate Check: Verified that there are no duplicate values, ensuring the data is unique.

# Visuals
I used Seaborn to create charts that explain the data:

Foundation Comparison: A bar chart showing the average "Unknown" values per foundation.

Project Counts: A count of how many projects each foundation has.

Security Audit: A plot showing the distribution of Secure vs Insecure links.

# How to use this
If you want to run my analysis:

Make sure you have pandas, seaborn, and matplotlib installed.

Run the EDA notebook.ipynb file.

# Why I made this
I’m a first-year student applying for the LFX Mentorship. I wanted to show that I can do more than just basic coding—I can actually find insights in a real dataset that could help the community improve its data integrity.
