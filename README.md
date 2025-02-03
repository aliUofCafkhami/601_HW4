# 601_HW4
## Objective
The objective of this assignment is to conduct a detailed analysis of the City of Calgary’s Building Energy Benchmarking dataset. Various python packages such as **re** (Regular Expressions (Regex)), **Pandas** (for basic tabular operations), **NumPy**, **Matplotlib** and **seaborn** is utilized to preprocess, analyze, and visualize the data. The tasks include cleaning the dataset, extracting relevant information using Regex, performing data aggregations, identifying outliers, and creating exploratory visualizations.

It is worth noting that one of the highlights of this assignment was to utilize the **Regular Expression (Regex)** in python, therefore, the cells where Regex was used have been accompanied with further explaination.

Following is the result of the analysis:
**Top 5 properties with the highest total energy consumption**
Table below, presents the top 5 properties with the highest total energy consumption.

| Primary Property Type - Self Selected   |   sum_EUI_prop_type |
|:----------------------------------------|--------------------:|
| Office                                  |         1.01534e+06 |
| Fitness Center/Health Club/Gym          |    889771           |
| Distribution Center                     |    726555           |
| Ice/Curling Rink                        |    567892           |
| Fire Station                            |    306095           |

As can be seen from the table, Office buildings as well as the fitness center,health clubs and gyms have the highest consumption of energy with 1.01534e+06 GJ for office and 889770.6 for the fitness center,health clubs and gyms altogether, respectively.
Figure below depicts the yearly trend of average Site Energy Use Intensity (EUI).
![image](https://github.com/user-attachments/assets/364361a6-724d-4e9f-938e-f4619fb2acad)
According to the graph there was a significant drop in the EUI between the years 2019 and 2020, which becomes somewhat steady after 2020 with low fluctuation. This could be due to start of Covid-19 pandemic which resulted in the closure of the public places such as offices and gyms. It is interesting to note that even after the end of pandemic 2022 and 2023, the energy consumption did not rise to the pre-pandemic.

**Top 10 buildings with the highest GHG emissions**
Figure below, illustrates the bar graph comparing the emission of Green House Gasses (GHG) in metric tonnes of different building types since when they were built
![image](https://github.com/user-attachments/assets/6fbf4dd6-87ac-4c66-9049-eb7ebeb405fc)
