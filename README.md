# Chronicles of Australian Ultra-Marathoners: Unraveling the Endurance Legacy Down Under

## Introduction
Welcome to the repository dedicated to examining the enduring legacy of ultra-marathon events, with a particular focus on the remarkable contributions of Australian athletes. This README offers a comprehensive overview of the meticulous steps taken in data curation, visualization, and the invaluable insights unearthed through rigorous analysis.

Please check out the dataset here. ["Kaggle"](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running/data)

## Overview
This project delves into over two centuries of ultra-marathon race records, exploring the participation trends, demographic distribution, and performance metrics of Australian athletes. By filtering the dataset to include only Australian athletes and events, and focusing on the 50km and 100km distances, the analysis provides a detailed understanding of Australia's involvement in endurance racing.

Please check out my workhere: [Python](/python_ultra_marathon_eda_project.ipynb)

## Data Preprocessing

Short summary:
- Subsetted the dataset to include only Australian athletes and events.
- Filtered the "Event distance/length" column to focus on 50km and 100km races.
- Extracted data from the years 2012 to 2022 to analyze recent trends.
- Resulted in a subset of 52,256 records from the original 7,461,226 values.

## Data Cleaning
- Checked for and removed any duplicate entries.
- Filled or removed NULL values to ensure data integrity.
- Removed unnecessary columns for streamlined analysis.

## Data Visualization

### Trend of Event Participation Over Time.
We can see that the number of events throughout the years has steadily increased since 2012. However, there was a sudden plunge in the data in 2020, which is highly likely due to the COVID-19 pandemic and lockdown measures. 

![Trend of Participation Over Time](/vizs/Trend%20participation.png)

### Ranking the most popular events based on participant numbers.
From the visualization, we can see the most popular events in Australia. In the first and second please, the same events with different distances have topped. That is "Ultra Trail Australia."

#### What is Ultra Trail Australia?
Ultra-Trail Australia (UTA) is Australia's premier trail running event held annually in the Blue Mountains National Park, New South Wales. The course takes runners through some of the most stunning scenery in the Blue Mountains, including waterfalls, eucalyptus forests, and sandstone cliffs.

![The Most Popular Events](/vizs/Most%20popular%20events.png)

### Distribution of participants by gender and distance.
In both distances, we can see the male is predominantly higher than the female participants. 

![The Distribution of Race Distance & Gender](/vizs/Race%20distance%20&%20gender.png)

### Age Distribition of Participants
Regardless of the distance, the active participants of ultra-marathon age distribution start when the runners are in their early 30s and late 50s, including both genders. 

![Age Distribition](/vizs/Age%20distribution.png)

### Average Speed by Event Distance & Gender
From this visualization, we can observe in both distances, male runs slightly faster than females. 

![Average Speed by Event Distance & Gender](/vizs/Avg%20speed%20by%20dis%20&%20gen.png)

### The Average Speed of Athletes by Age
We can see numerous variations in terms of average speeds from different age groups as well as gender. Nonetheless, one thing we can observe clearly is that the average speed is decreasing when the age is increasing. 

![The Average Speed of Athletes by Age](/vizs/age%20&%20gender%20&%20avg%20speed.png)

### Monthly Variation in Event Participation
The month May typically hold the highest number of ultra-marathon events. 

![Monthly Variation in Event Participation](/vizs/Monthly%20variation.png)

## Project Goals:
The primary objective of this project is to illustrate the extensive participation of Australians in ultra-marathon events. 

By showcasing the age and gender distribution of participants and highlighting the increasing involvement of older individuals, the aim is to inspire the younger generation to embrace physical activity and adopt a healthy lifestyle.

This repository serves as a comprehensive resource for anyone interested in exploring the dynamics of ultra-marathon running in Australia and gaining insights into the endurance sports landscape.

**Note:** The dataset used for this analysis is anonymized to comply with data protection laws and preserve athlete privacy.