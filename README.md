# <p align="center"> Video-Game-Sales </p>

## Introduction

---

The video game industry is a rapidly growing market with diverse genres, platforms, and publishers contributing to its expansion. This project aims to analyze video game sales data to uncover significant trends and insights. Utilizing a dataset from Kaggle and Tableau for visualization, we seek to provide a detailed analysis of key performance indicators (KPIs) to understand the dynamics of the video game market better. Through this analysis, we aim to provide actionable insights that can guide developers, marketers, and publishers in their strategic decision-making processes


![](https://github.com/paragon-tech001/Video-Game-Sales/blob/main/videogames%20intro.jpg)

## Project Objectives

---
**_The primary objectives of this project are:_**

1. To identify the total sales distribution across different video game genres.
2. To determine the top-performing video games based on global sales.
3. To analyze sales trends over the years, categorized by genre.
4. To rank gaming platforms based on their sales performance.
5. To evaluate the top publishers in the video game industry by sales volume.
   
## Data Description

--- 

![](https://github.com/paragon-tech001/Video-Game-Sales/blob/main/vg%20data%20source.PNG)

**__The dataset utilized in this project is sourced from Kaggle and contains comprehensive video game sales data. The key attributes in the dataset include:_**
- Name: The title of the video game.
- Platform: The platform (e.g., PlayStation, Xbox, PC) on which the game was released.
- Year of Release: The year when the game was released.
- Genre: The category or genre of the game (e.g., Action, Sports, Role-Playing).
- Publisher: The company that published the game.
- Sales Figures: Sales data broken down by regions (NA_Sales for North America, EU_Sales for Europe, JP_Sales for Japan, Other_Sales for other regions) and globally (Global_Sales).

## Data Cleaning and Preparation

---

![](https://github.com/paragon-tech001/Video-Game-Sales/blob/main/data%20model.PNG)

Missing Values: Identified and handled missing values through imputation and omission where necessary.
Data Consistency: Ensured consistency in genre and platform names by standardizing entries.
Outliers: Detected and managed outliers to ensure they do not skew the analysis results.

## Methodology

---

**_The methodology for this project involved several key steps:_**

#### Data Exploration and Analysis

- Descriptive Statistics: Calculated basic statistics (mean, median, mode, etc.) to understand the general distribution of the data.
- Exploratory Data Analysis (EDA): Used graphical tools to uncover initial patterns, correlations, and anomalies.

## Visualization in Tableau

---

**_Total Sales by Genre_**

![](https://github.com/paragon-tech001/Video-Game-Sales/blob/main/Total%20sales%20by%20genre.PNG)

- _Visualization Description:_
A vertical bar chart represents the total global sales for each video game genre. This visualization helps in identifying which genres are the most commercially successful.
- _Insights:_
The chart reveals that Action, Sports, and Shooter genres dominate the market, indicating a higher consumer preference for these types of games. Conversely, genres like Puzzle and Strategy show lower sales, suggesting a niche but less commercially significant market.

**_Top 10 Games by Sales_**

![](https://github.com/paragon-tech001/Video-Game-Sales/blob/main/Top%2010%20names%20by%20sales.PNG)

- _Visualization Description:_
A horizontal bar chart showcases the top 10 video games by global sales, providing a clear view of the most successful titles in the dataset.

- _Insights:_

The chart highlights blockbuster franchises and titles, such as "Wii Sports", "Grand Theft Auto V" and "Super Mario" which have significantly higher sales. This indicates the strong market presence and popularity of certain franchises, reflecting consumer loyalty and brand strength.

**_Sales by Year and Genre_**

![](https://github.com/paragon-tech001/Video-Game-Sales/blob/main/sales%20by%20genre%20and%20year.PNG)

- _Visualization Description:_
An area chart visualizes the sales trends over the years, segmented by genre, offering insights into how different genres have evolved over time.
- _Insights:_
This visualization shows notable trends, such as the rise of the Shooter genre in recent years and the steady popularity of Sports games. It also reflects the decline of some genres, potentially due to shifts in consumer preferences or technological advancements.

**_Top 10 Platforms by Sales_**

![](https://github.com/paragon-tech001/Video-Game-Sales/blob/main/Top%2010%20platforms%20by%20sales.PNG)

- _Visualization Description:_
A packed bubble chart ranks the top 10 platforms based on their total sales, illustrating the market share of each platform.
- _Insights:_
The chart demonstrates that platforms like PlayStation and Xbox have substantial market shares, indicating their dominance in the gaming industry. It also shows the significant presence of Nintendo platforms, reflecting their strong fan base and successful product lineup.

**_Top 10 Publishers by Sales_**

![](https://github.com/paragon-tech001/Video-Game-Sales/blob/main/Top%2010%20publishers%20by%20sales.PNG)

- _Visualization Description:_
A treemap displays the top 10 publishers by global sales, providing a visual hierarchy of the major players in the video game industry.
- _Insights:_
The treemap highlights major publishers such as Nintendo, EA, and Activision, showing their leading roles in the market. It also reflects the diverse range of successful publishers, indicating a competitive industry landscape.

## Interpretation of Results

---

- **_Total Sales by Genre:_** The dominance of genres like Action and Sports suggests that these types of games have a broad appeal and significant market potential. Developers focusing on these genres may have higher chances of commercial success.
- **_Top 10 Games by Sales:_** The prominence of certain franchises underscores the importance of brand loyalty and franchise development in the video game industry.
- **_Sales by Year and Genre:_** Trends over time reveal shifts in consumer preferences and the impact of technological advancements on game development. For instance, the increasing popularity of Shooter games may be linked to improvements in graphics and gameplay mechanics.
- **_Top 10 Platforms by Sales:_** The market dominance of specific platforms indicates where developers and publishers might focus their efforts to maximize reach and profitability.
- **_Top 10 Publishers by Sales:_** The success of leading publishers highlights the importance of established distribution networks, marketing capabilities, and strong game portfolios.

## Recommendation

---

**_Based on the insights derived from the visualizations, several recommendations can be made:_**
- **_For Developers:_** Focus on creating high-quality games in popular genres like Action, Sports, and Shooter to leverage consumer demand.
- **_For Marketers:_** Target major platforms such as PlayStation, Xbox, and Nintendo for marketing campaigns to reach a larger audience.
- **_For Publishers:_** Invest in and promote successful franchises and consider diversifying the genre portfolio to capture a broader market segment. Additionally, analyzing trends can help in anticipating and adapting to shifts in consumer preferences.

## Conclusion
--- 

This project provided a detailed analysis of video game sales using data visualization techniques. The insights gained from the analysis offer valuable guidance for developers, marketers, and publishers in the video game industry. By understanding sales trends and market dynamics, stakeholders can make informed decisions to better position themselves for success in this competitive market. Future work could involve deeper analysis into regional sales trends, consumer demographics, and the impact of emerging technologies on the video game industry.
