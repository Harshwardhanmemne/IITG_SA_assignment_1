# IITG_SA_assignment_1
This Jupyter Notebook analyzes a classic car dataset to identify “consistent” car models — those that were produced over multiple years and maintained low variation in fuel efficiency (mpg). The core objectives of this project are:

🧠 Objectives:
Identify car models that appeared in the dataset across multiple model years.

Compute the standard deviation of mpg for each model to measure fuel efficiency consistency.

Filter and return only those models with at least 2 appearances and mpg standard deviation < 1.0.

Report each qualifying model’s:

Number of appearances

Average mpg

Sort the final result by:

Number of appearances (descending)

Average mpg (descending)

✅ Key Concepts Used:
Data cleaning and filtering

Grouping and aggregation with pandas

Standard deviation and mean computation

Multi-level sorting using sort_values

This assignment is a good demonstration of applying basic pandas operations to solve a real-world data quality and consistency problem.
