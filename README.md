# Effects of Covid 19 stringency measures on air quality in Switzerland  
  
In this work, we aimed to explore if the introduction of stringency measures in Switzerland 
during the COVID-19 pandemic have led to a reduction of PM2.5 concentrations in the air. 
To do so, we created a simplified linear model using python 3.8 for the prediction of 
the monthly sum of PM2.5, based on location and precipitations. The model was validated 
using the data collected before any stringency measures (due to corona) were initiated in 
Switzerland (2016-2019). A prediction of the PM2.5 concentration in air for the years 2020-
2021 was then performed, based on the model.

The results of the model were visualized using QGIS and then animated in Photoshop:  
![alt text](https://github.com/Eitams/Covid19-and-air-quality/blob/main/prediction_ref_animated.gif "Logo Title Text 1")

## Conclusions
The data presented here shows the impact of COVID-related restrictions on air pollution, specifically focusing on a measure called PM2.5. This measure has limited ability to explain the effects. Although strict measures in February 2021 appear to have lowered PM2.5 levels, other months with similar lockdowns, like April 2020, didn't show the expected reduction. Despite April 2020 having even stricter measures than February 2021 (73 vs. 60), only February 2021 saw a reduction in PM2.5.

This suggests that the length of strict measures during the second wave, which became stricter over two months before peaking in January, had a delayed impact on PM2.5. In contrast, April 2020, despite high stringency, had shorter duration of measures.

Importantly, various local factors like winds, wildfires, and other events that weren't considered due to limited data availability can influence PM2.5. Adding these factors to the model could enhance its accuracy and help explain differences between predicted and actual values during COVID-related shutdowns.

While other studies have shown air pollution reduction during lockdowns in different parts of the world, they focused on shorter time periods and daily comparisons rather than monthly averages.

Furthermore, Switzerland had less strict restrictions throughout the pandemic compared to some countries, as evident from its lower stringency index. For instance, Switzerland's highest index was 73 in April 2020, while several countries reached 100 (e.g. India).

Tools: python, QGIS and phothshop.  
For a more detailed review on the process, analysis and conclcusion please see the project report (PM25andCovid19_prediction.pdf)
