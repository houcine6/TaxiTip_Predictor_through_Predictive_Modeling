# TaxiTip_Predictor_through_Predictive_Modeling
This repository houses a comprehensive analysis focused on enhancing taxi driver earnings in New York City. Utilizing machine learning techniques, including Random Forest and XGB models, the project identifies factors influencing generous tipping behavior.

# Project Overview
In this project, our objective was to build predictive models using both Random Forest and gradient boosted decision trees (XGB) techniques with cross-validation to determine whether a taxi passenger was likely to leave a generous tip or not. The data used for this analysis was gathered from yellow taxi rides in New York City during the year 2017. The end result was our Random Forest model, which achieved an accuracy of 67% and a precision of 67%, and the XGB model, which achieved an accuracy of 66% and a precision of 67%. These models helped us identify crucial factors that distinguish passengers who tipped well from those who didn't. Key factors included predicted fare, mean duration, mean distance, and others, which significantly influenced whether a passenger would leave a generous tip or not.

## Business Understanding
Understanding the economic challenges faced by New York Taxi Drivers, with an average annual salary of around $45,000 according to "salary.com," it became imperative to identify the factors that influence clients to leave generous tips. By comprehending these factors, drivers can potentially increase their earnings, thereby improving their financial stability.

## Data Understanding
For this project, we utilized a dataset called "2017_Yellow_Taxi_Trip_Data.csv," which was merged with "nyc_preds_means.csv." The data in "2017_Yellow_Taxi_Trip_Data.csv" was collected by the New York City Taxi & Limousine Commission and published by the city of New York as part of their NYC Open Data program. This dataset provided valuable insights into taxi trips in the city, allowing us to analyze passenger behavior and tipping patterns.

**Dataset Link:** [Dataset](https://data.cityofnewyork.us/Transportation/2017-Yellow-Taxi-Trip-Data/biws-g3hs).

## Modeling and Evaluation
We employed Random Forest and XGB models for this analysis. The Random Forest model achieved an accuracy of 67% and a precision of 67%, while the XGB model achieved an accuracy of 66% and a precision of 67%. These models were instrumental in identifying key factors that influence a client's decision to leave a tip or not. Feature importances were also analyzed, providing additional insights into the significant predictors.

![](results.png)

## Random Forest Model Performance:
  - *Accuracy: 67%*
  - *Precision: 67%*

## XGB Model Performance:
  - *Accuracy: 66%*
  - *Precision: 67%*

Additionally, the feature importances highlighted the factors that had the most substantial impact on tipping behavior.

![](feature%20importances.png)

## Conclusion
Both the Random Forest and XGB models effectively served the purpose of identifying crucial factors that influence a client's decision to leave a tip. These findings offer valuable insights for taxi companies, enabling them to focus their efforts on enhancing the factors that increase the likelihood of a client leaving a gratuity. By understanding these tipping patterns, taxi drivers and companies can optimize their services, improve customer satisfaction, and ultimately enhance their earnings, addressing the economic challenges faced by drivers in the industry.

