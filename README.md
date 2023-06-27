## Introduction

Slope is an unsupported inclined mass of soil or rock.Natural slopes are those formed by natural causes and they include hills and valley slopes.
Artificial slopes are the ones engineered by humans and include earthen dams,highway and railway embankments,landfills,levees etc.
Failure of a soil mass takes place by the downward and outward movement of soil which is caused by the action of gravitational forces, supplemented by earthquake forces in some cases. 
The factor of safety (FS)  is defined as the ratio of the sum of resisting forces or moments to the sum of driving forces or moments. When the factor of safety is equal to 1.0, a slope has just reached critical failure condition. If the factor of safety falls below 1.0 then a failure is imminent or has already occurred. Factors of safety in the range of 1.3 to 1.5 are considered reasonably safe in many design scenarios.

## Objective

Analysis of Factors of Safety (FS) at different slope heights, slope angles and strength parameters of soil such as cohesion and angle of internal friction.
This helps to understand the trends in FS which,in turn, helps geotechnical engineers gain deeper understanding of the stability of existing slopes, 
assess the possibility of landslides in natural and engineered slopes, enable redesign of failed slopes and planning of preventive measures and study the effect of seismic loading on embankments and slopes.

## Data

Soil slopes of heights (h) 3m,6m,9m and 12m are taken into consideration.
Different slope angles of 2H:1V,1.5H:1V,1H:1V and 0.5H:1V are considered for each height.
The strength parameters of soil considered for the study are cohesion (c) and angle of internal friction (Փ).
The data used is first-hand and is generated using a Civil Engineering software called PLAXIS.

## Tools

The data is explored and cleaned using the Pandas library of Python and visualizations are created using Tableau. Please use the following link to access it:
[https://public.tableau.com/app/profile/reeba1597/viz/FactorofSafetyofSoilSlopes/Dashboard](https://public.tableau.com/app/profile/reeba1597/viz/SlopeStabilityAnalysis/Dashboard3)
Moreover,predictive analysis has been carried out on the data using Python.

## Results

It can be noted that under no surcharge conditions with other parameters remaining unaltered,

1.	Factor of safety increases with increase in cohesion value
2.	Factor of safety increases with increase in the value of friction angle and
3.  Factor of safety decreases as the slope angle increases
4.  Factor of safety decreases as the slope is of a greater height

As a result of employing Machine Learning Algorithms on the dataset, it is possible to predict the factor of safety value of a slope given its slope angle,height and strength parameters of its soil. This can have wide applications in the field of Civil engineering. The project can be further expanded by considering the data generated in PLAXIS when surcharge conditions are applied to slopes.
