# Football Team Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview

This data analysis project aims to provide insights into the data of performance of football teams over the past year. By analyzing various aspects of the data, we seek to identify trends, make data driven recommendations, and gain deeper understanding of which is the best team for the company to invest in.

![football team vs performance chart](https://github.com/user-attachments/assets/ad268cc0-15a7-448e-b7c8-49c753bf71d0)


### Data Sources

Data: The primary dataset used for this analysis is the "Premier_League_Final_Data_batch2.csv" file, containing detailed information about each team's goals, number of wins, loss and draws.

### Tools

- Python
- Pandas library (Data Cleaning and Exploratory Data Analysi)
- Numpy library (Data Cleaning and Exploratory Analysis)
- Matplotlib library (Exploratory Analysis)

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the data to answer key questions, such as:
- Which football team has the highest chance of winning?
- Which team the company should invest in?

### Data Analysis

``` python
#creating bar chart
plt.figure(figsize = (25,10))
plt.bar(club_sort_1["Club"], club_sort_1["Score"] , color = "turquoise")

#labels and title
plt.ylabel("Scores" , fontsize = 16)
plt.title("Football Club v/s Performance score 2023/2022/2021" , fontsize = 18)

#legends
plt.legend(["Score"] , fontsize = 14)

plt.xticks(rotation = 90 , fontsize = 14)
plt.yticks( fontsize = 14)

plt.ylim(0, 100)

plt.show()
```

### Results/Findings

*Birmingham City , Sheiffield Wednesday , Queens Park Rangers , Derby county* were among the top 5 highest scorer team but all of them havent played for the last 3 years.

Among all the team the top scorer as well as a best consitent player in the last 3 years appears to be *Sheffield United*.

### Recommendations

Based on the analysis, we recommend the following actions:

- Since *Birmingham City , Sheiffield Wednesday , Queens Park Rangers , Derby county* havent played for the last 3 years considering them as potential teams to be invested in will be a waste of time and asset.

- Investing in *Sheffield United* club would be the best option because the team has been top scorere as well as best consistent player in last 3 years.
