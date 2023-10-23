# Acea-Time-Series-for-Water-Prediction-
All water bodies  are sub-system of a larger one, the water cycle.   Hence, all these kind of waterbody are connected to each others.  Precipitation is the principal source of input for all of the water-bodies.   Response time, or the amount of time between rainfall and the response of the water level, varies depending on a number of factors.
# Dataset Description
It consist of  nine different datasets, completely independent and not linked to each other. Each dataset can represent a different kind of waterbody. As each waterbody is different from the other, the related features as well are different from each other. So, if for instance we consider a water spring we notice that its features are different from the lake’s one. This is correct and reflects the behavior and characteristics of each waterbody. The Acea Group deals with four different type of waterbodies: water spring (for which three datasets are provided), lake (for which a dataset is provided), river (for which a dataset is provided) and aquifers (for which four datasets are provided).
Let’s see how these nine waterbodies differ from each other.

Waterbody: Auser
Type: Aquifer

Description: This waterbody consists of two subsystems, called NORTH and SOUTH, where the former partly influences the behavior of the latter. Indeed, the north subsystem is a water table (or unconfined) aquifer while the south subsystem is an artesian (or confined) groundwater.

The levels of the NORTH sector are represented by the values of the SAL, PAG, CoS and DIEC wells, while the levels of the SOUTH sector by the LT2 well.

Waterbody: Petrignano
Type: Aquifer

Description: The wells field of the alluvial plain between Ospedalicchio di Bastia Umbra and Petrignano is fed by three underground aquifers separated by low permeability septa. The aquifer can be considered a water table groundwater and is also fed by the Chiascio river. The groundwater levels are influenced by the following parameters: rainfall, depth to groundwater, temperatures and drainage volumes, level of the Chiascio river.

datasets_description.xlsx(41.04 kB)
Table	Total Rows	Total Columns
Dataset_Feature_Value	34	5
Datasets_Description	9	3
Datasets_Feature_Description	77	8

# Problem Definition
For this tutorial, we will build a model to predict the depth to groundwater of an aquifer located in Petrignano, Italy. The question we want to answer is
> What is the future depth to groundwater of a well belonging to the aquifier in Petrigrano over the next quarter?

> The wells field of the alluvial plain between Ospedalicchio di Bastia Umbra and Petrignano is fed by three underground aquifers separated by low permeability septa. The aquifer can be considered a water table groundwater and is also fed by the Chiascio river. The groundwater levels are influenced by the following parameters: rainfall, depth to groundwater, temperatures and drainage volumes, level of the Chiascio river.

> Indeed, both rainfall and temperature affect features like level, flow, depth to groundwater and hydrometry some time after it fell down. 

# Data Collection 
In a typical workflow for time series, this would be the time for data collection. In this example, we will skip the data collection step and use data from the [Acea Smart Water Analytics challenge](https://www.kaggle.com/c/acea-water-prediction/). Therefore, this section will be a dataset overview. 
# Challenge
To predict the amount of water in each unique waterbody? The challenge is to determine how features influence the water availability of each presented waterbody. To be more straightforward, gaining a better understanding of volumes, they will be able to ensure water availability for each time interval of the year.

The time interval is defined as day/month depending on the available measures for each waterbody. Models should capture volumes for each waterbody(for instance, for a model working on a monthly interval a forecast over the month is expected).
The desired outcome is a notebook that can generate four mathematical models, one for each category of waterbody (acquifers, water springs, river, lake) that might be applicable to each single waterbody.
![image](https://github.com/Harshitapanchbhai/Acea-Time-Series-for-Water-Prediction-/assets/85555899/c615aa8d-7167-44d1-8d60-3400e808505e)

# Results 

![image](https://github.com/Harshitapanchbhai/Acea-Time-Series-for-Water-Prediction-/assets/85555899/7e13e4c2-3c71-48c9-9be1-408bb165c5c7)
![image](https://github.com/Harshitapanchbhai/Acea-Time-Series-for-Water-Prediction-/assets/85555899/19322331-de48-468a-90d4-9df24adbe992)
![image](https://github.com/Harshitapanchbhai/Acea-Time-Series-for-Water-Prediction-/assets/85555899/8985a42e-0c84-4424-8839-99950c91c458)
![image](https://github.com/Harshitapanchbhai/Acea-Time-Series-for-Water-Prediction-/assets/85555899/20379b46-4a25-49ab-8f0c-83436c44504f)
![image](https://github.com/Harshitapanchbhai/Acea-Time-Series-for-Water-Prediction-/assets/85555899/9a94076a-82f8-4183-bcc0-e8b7d0667c7f)

![image](https://github.com/Harshitapanchbhai/Acea-Time-Series-for-Water-Prediction-/assets/85555899/19476859-5ed7-48d4-a7e7-4c263101b283)![image]![image](https://github.com/Harshitapanchbhai/Acea-Time-Series-for-Water-Prediction-/assets/85555899/f2a51fa8-1496-4dca-bb5f-2d4a19c98fe9)
(https://github.com/Harshitapanchbhai/Acea-Time-Series-for-Water-Prediction-/assets/85555899/c2710933-6e4c-449f-b2bd-44973c5cd4ee)






