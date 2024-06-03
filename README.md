# Case Study With Python

**Title:** Bellabeat Fitness Data Analysis <br>
**Tool:** Python <br>
**Dataset:** [Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit)

## Given Scenario
Bellabeat, a high-tech manufacturer of health-focused products for women. Bellabeat is a successful small company, but they have the potential to become a larger player in the global smart device market. Cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. You have been asked to focus on one of Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices. The insights you discover will then help guide marketing strategy for the company.

## ❓ Ask 
- The problem that we're attempting to tackle in the given situation is that we need to identify trends in how consumers are actually using smart devices, and then I'll offer suggestions to the stakeholders based on these insights. This will assist the organisation with their marketing plans, tracking more clients, and establishing a presence in the global market.

- These studies will be provided to Bellabeat's founders and Chief Creative Officer, a mathematician and essential part of the Bellabeat executive team.

- We will collaborate with the Bellabeat marketing analytics team. A group of data analysts who collect, analyse, and report data to assist drive Bellabeat's marketing strategy. You joined our team six months ago and have been busy learning about Bellabeat's vision and business goals, as well as how you can assist Bellabeat achieve them as a junior data analyst.

### 💡 Business Task
To gain insights into how customers are utilizing smart devices and how this information can inform our marketing strategy, we need to conduct a comprehensive analysis.

## 💻 Prepare 
**Information about dataset**
- FitBit Fitness Tracker Data was used as the data source for this case study. This dataset is housed in Kaggle, is accessible via Mobius, and was generated by responders to an Amazon Mechanical Turk distributed poll dated 04.12.2016 05.12.2016.

- The data is licenced under CC0: Public Domain, with the author relinquishing all of his or her rights to the work under copyright law worldwide, including all related and neighbouring rights, to the extent permissible by law.

- The dataset is made up of 18.csv files. 15 in long format, 3 in broad format. The databases contain a wide range of information such as activity metrics, calories, sleep records, heart rate, and steps in seconds, minutes, hours, and days.

- The data has some drawbacks, such as a very small sample size, and the time span of the dataset is also not optimal.

## 🛠 Process
**Setting Up Environment**
```
import pandas as pd 
import numpy as np 
import matplotlib.pyplot as plt 
import seaborn as sns 
import datetime as dt
```
**Importing the dataset**
The dataset has 18 csv files, however the majority of them have been merged into a single file called dailyActivity_merged.csv, which will be my primary focus. I'll also use certain files that weren't merged into this particular one

```
daily_activity = pd.read_csv('.../Fitabase Data/dailyActivity_merged.csv')
daily_activity.head()
```














