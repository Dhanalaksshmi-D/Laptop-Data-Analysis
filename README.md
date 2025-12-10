# Laptop-Data-Analysis
The dataset was cleaned using Pandas by fixing missing values, standardizing formats, and converting data types. After preprocessing features like RAM, CPU, and storage, exploratory analysis was performed using visualizations to identify trends, distributions, and key insights.
Project Description / Analysis Workflow

For this project, I performed a detailed data analysis on a laptop specifications dataset using Python, focusing mainly on Pandas, NumPy, and Matplotlib/Seaborn for data cleaning, preprocessing, and visualization.

1. Data Cleaning

Imported the dataset using Pandas and inspected the structure, data types, and missing values.

Standardized column names and corrected formatting inconsistencies.

Handled missing or inconsistent values where required.

Converted numerical features stored as text into proper numeric types.

Cleaned categorical fields such as Company, TypeName, CPU, RAM, GPU, etc., to ensure consistent labeling.

2. Data Preprocessing

Extracted key features from text fields (e.g., CPU brand, GPU type).

Normalized units such as RAM (GB), weight, and price where necessary.

Performed encoding on categorical variables for later analysis or modeling.

Filtered out irrelevant or duplicate entries.

3. Exploratory Data Analysis (EDA)

Generated summary statistics using Pandas (describe() and groupby analysis).

Created visualizations to understand:

Company-wise distribution of laptops

Price distribution

RAM and storage configurations

Laptop type categories

Popular CPU/GPU combinations

Identified trends such as:

Brands offering the highest number of models

Relationship between RAM, CPU type, and price

Weight vs portability patterns

Performance-focused vs budget-focused categories

4. Insights Extraction

Based on the cleaned and analyzed data, meaningful insights were drawn about:

Market patterns

Specification trends

Price variations across companies

User-focused laptop segments (gaming, ultrabook, workstation, etc.)
