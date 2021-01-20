# Coursera_Capstone

## Introduction
Every year car accidents cause hundreds of thousands of deaths worldwide. According to a research conducted by the World Health Organization (WHO) there were 1.35 million road tra c deaths globally in 2016, with millions more sustaining serious injuries and living with long-term adverse health consequences. Globally, road tra c crashes are a leading cause of death among young people, and the main cause of death among those aged 15{29 years. Road tra c injuries are currently estimated to be the eighth leading cause of death across all age groups globally, and are predicted to become the seventh leading cause of death by 2030.

For the final capstone project in the IBM certificate course, we want to analyze the accident “severity” in terms of human fatality, traffic delay, property damage, or any other type of accident bad impact. The data was collected by Seattle SPOT Traffic Management Division and provided by Coursera via a link. This dataset is updated weekly and is from 2004 to present. It contains information such as severity code, address type, location, collision type, weather, road condition, speeding, among others.

The target audiences of this study are those people who really care about the traffic records, especially in the transportation department. Also, we want to figure out the reason for collisions and help to reduce accidents in the future.

## Data
The data was collected by Seattle SPOT Traffic Management Division and provided by Coursera via a link. There are 194,673 observations and 38 variables in this data set. Since we would like to identify the factors that cause the accident and the level of severity, we will use SEVERITYCODE as our dependent variable Y (Target Variable) , and try different combinations of independent variables X to get the result. Since the observations are quite large, we may need to filter out the missing value and delete the unrelated columns first. Then we can select the factor which may have more impact on the accidents such as weather, road condition, and light condition.

## Conclusion
In this study, I analyzed the relationship between severity of an accident and some characteristics which describe the situation that involved the accident.I built and compared 3 different classification models to predict whether an accident would have a high or low severity. These models can have multiple application in real life.

Based on the dataset provided for this capstone from weather, road, and light conditions pointing to certain classes, we can conclude that particular conditions have a somewhat impact on whether or not travel could result in property damage (class 1) or injury (class 2).

By identifying the features that favor the most the gravity of an accident, these could be tackled by improving road conditions or increasing the awareness of the population.Furthermore, there are some places which has more accidents during the dark time. For those places, adding lights might be a good solution to reduce the collisions. Also, when more cars involved in the accident, it seems that the level of severity will increase. They may need to be responded immediately to save more life.
