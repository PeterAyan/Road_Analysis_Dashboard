# Road Accident Analysis Dashboard
![Alt Text](accident.jpg)
## Introduction

This project focuses on analyzing UK road accident data to gain insights into patterns, trends, and key factors contributing to accident occurrences. The analysis aims to identify effective strategies for reducing road accidents by exploring the relationships between variables such as weather conditions, road types, vehicle types, and temporal patterns.

## Data Source

The dataset used for this analysis is sourced from [click here](https://data.dft.gov.uk/road-accidents-safety-data/dft-road-casualty-statistics-collision-2021.csv) and dataset data guide [click here](https://data.dft.gov.uk/road-accidents-safety-data/dft-road-casualty-statistics-collision-2021.csv). It contains information on road accidents in the UK, including details such as accident severity, location, time, weather conditions, road surface conditions, and vehicle types involved. The dataset covers the time period from Jan to Dec, 2021.

## Data Transformation

The road accident dataset was preprocessed using Power Query to ensure data quality and integrity. The following steps were performed:
  1.  Handling missing values: Rows with missing values, denoted as -1, were removed from the dataset.
  ![Alt}()
  3.  Converting numerical values to categorical: Columns such as weather conditions, road surface conditions, road type, and number of vehicles were converted from numerical to categorical format for better analysis.
  ![Alt}()

## Data Modelling

No modelling was required since by default the downloaded dataset were in a table and that was used for the analysis

## Analysis and Visualizations

The analysis utilized various visualization tools and techniques to explore the UK road accident dataset:

-  Data Analysis Expressions (DAX): Used to calculate total accident occurrences and severity types.
-  Stacked Bar Chart: Employed to analyze the distribution of accident severity across different road types.
-  Stacked Area Chart: Investigated the relationship between weather conditions and road surface conditions in accident occurrences.
-  Heat Map: Visualized the geographical distribution of accident incidents.
-  Other visualizations: Pie charts, donut charts, cards, matrix, multi-row cards, and slicers were used to present additional insights.

## Key Findings

The analysis revealed several key findings:
-  A total of 37.4k accidents were recorded, with the majority being slight accidents (29.1k), followed by serious accidents (7.8k) and fatal accidents (498).
-  Most accidents occurred during daylight hours (72.57%) compared to dark periods (27.43%).
-  Urban areas accounted for 69.37% of accidents, while rural areas accounted for 30.62%.
-  Accidents were more frequent during the wind season and in the month of September (2,267 accident indices).
-  Motorcycles were involved in a high number of accidents (37,378), while buses had minimal involvement (2 accidents).
-  Police attended the scene in 25,672 out of the total 37.4k accidents.
-  The heat map highlighted accident hotspots across the environs.

## Dashboard Overview

The interactive dashboard provides a comprehensive view of the UK road accident analysis. It includes visualizations such as cards displaying total accidents and severity types, donut charts showing the distribution of accidents by area, a stacked area chart illustrating the relationship between weather and road surface conditions, and a heat map depicting accident hotspots. The dashboard allows users to filter and explore the data based on various parameters.
![WhatsApp Image 2024-03-21 at 10 52 28 PM](https://github.com/PeterAyan/insightfulmind/assets/164429264/b82d16e9-cb9b-474a-aa54-5c1ed35f3354)

## Insights and Recommendations

Through the analysis presented in this dashboard, several key insights and recommendations can be derived:

1. **Targeted Interventions**: Identify high-risk areas, road types, or environmental conditions that contribute significantly to accidents, and prioritize resource allocation and safety measures accordingly.

2. **Infrastructure Improvements**: Evaluate the need for infrastructure upgrades, such as road maintenance, lighting enhancements, or traffic management systems, in areas with higher accident rates.

3. **Public Awareness Campaigns**: Develop targeted public awareness campaigns to educate drivers, pedestrians, and other road users about road safety practices, particularly in areas or conditions with higher accident risks.

4. **Vehicle Safety Regulations**: Assess the need for stricter vehicle safety regulations, especially for vehicle types that are disproportionately involved in accidents, to improve overall road safety.

5. **Collaborative Efforts**: Foster collaboration among relevant stakeholders, including government agencies, law enforcement, transportation authorities, and community organizations, to implement comprehensive road safety strategies.

By leveraging the insights derived from this Road Accident Analysis Dashboard, policymakers and authorities can make data-driven decisions to enhance road safety, reduce accident rates, and ultimately save lives.


