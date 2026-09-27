# Social-media-usage-data-analysis-with-python
Conclusion – Social Media Data Analysis
The main objective of this project is to utilize Python to simulate and analyze social media tweet interaction. Using libraries like pandas, numpy, seaborn, and matplotlib, it displays fundamental data science abilities such as data production, cleaning, visualization, and statistical analysis.

In order to examine user involvement through likes across different content categories, I created a social media dataset simulation for this project. Each step of the process—data creation, cleaning, visualization, and statistical analysis—helped improve the quality of the data and the insights discovered.

Process Overview
Data Generation:
•	Created a synthetic dataset with 500 entries.
•	Used pandas for dates, random for category selection, and numpy for like counts.

Data Cleaning:
•	Removed missing (NaN) and duplicate values using dropna() and drop_duplicates().
•	Converted Date to datetime using pd.to_datetime and coerced invalid formats.
•	Ensured Likes values were integers by using pd.to_numeric() and astype(int).

Visualization:
•	Used Seaborn and Matplotlib to plot:
	A histogram showing the distribution of likes (fairly uniform).
	A boxplot comparing likes across different content categories.

Statistical Analysis:
•	Calculated overall average likes (≈4870).
•	Grouped data by Category to find category-wise mean likes.
•	Identified Fitness, Travel, and Health as top-performing categories in terms of average likes.

Key Insights:
•	Fitness content received the highest average engagement, followed by Travel and Health.
•	The boxplot revealed a wide range of likes in each category, suggesting variability in audience response.
•	The histogram showed a fairly even spread, indicating no extreme skew in engagement distribution.

Challenges & Solutions:
Due to a version mismatch, sns.histplot() encountered an Attribute Error. resolved it by upgrading Seaborn.
By forcing invalid formats and methodically cleansing data, robustness was ensured.
My ability to simulate data-driven scenarios, clean and preprocess datasets, effectively display, and derive actionable insights—skills essential for data roles in tech and business environments—is demonstrated in this project.
