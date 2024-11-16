# Movies Analysis in the Entertainment Industry 🎥
This project is focusing on analyzing trends in the movie industry using python. The analysis explores trends, understands the correlation between gross income and various variables to derive meaningful insights.

**Table of contents**
- [Overview](#overview)
- [Technologies used](#technologies-used)
- [Features](#features)
- [Visualizations](#visualizations)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Data analysis](#data-analysis)

**Overview**
This project analyzes movie trends in the industry using statistical methods and data visualization techniques. It includes:
- Cleaning and preprocessing the dataset.
-Identifying the most prevalent movie genres.
- To study the correlation between gross income and budget.
- Discover the countries that dominate in the movie industry.

**Technologies used**
- Python: For data manipulation and analysis.
- Pandas:For handling and cleaning data.
- Matplotlib and Seaborn: For data visualization.

 **Data analysis**
  ```python
  ##import the important libraries
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np

##read the data
df = pd.read_csv("movies data.csv")
df.head()
```

**Features**
- Scatter plot analysis of gross income and budget
- Heatmap to analyze the correlation between gross income and other numeric variables.
- Bar chart of most prevalent movie genres.
- Bar chart of countries that dominate in the movie industry.

**Visualizations**
- Scatter plot analysis of gross income and budget
  
 ![scatter plot](https://github.com/user-attachments/assets/413843d0-3e0a-480a-921c-43024a697f01)

 - Heatmap to analyze the correlation between gross income and other numeric variables.

 
![Heatmap analysis](https://github.com/user-attachments/assets/2b038fe2-a2c4-41ad-b840-8a5213d91481)


- Bar chart of most prevalent movie genres.

  ![Bar chart](https://github.com/user-attachments/assets/06c4270f-0c78-41ac-a61d-16ccecfe5df5)

  
- Bar chart of countries that dominate in the movie industry.

![Bar chart countries](https://github.com/user-attachments/assets/a9b32ab0-7bd5-44c9-ade8-b58a5a4cbef1)
  

**Findings**
- Budget is correlated gross income, the higher the budget the higher the gross income
- The most prevalent genres are comedy, action and drama.
- USA dominate the movie industry in terms of gross income.

**Recommendations**
- Increase Investment in High-Potential Movies by allocating larger budgets to projects with proven directors, writers, or casts to maximize gross income.
- Develop marketing strategies focused on the U.S. market, which shows high gross income potential.
- Blend Genres for Broader Appeal to attract diverse audiences.
