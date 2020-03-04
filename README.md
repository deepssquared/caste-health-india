# Caste and Health in India

## BACKGROUND:
Among the health inequities in India, none is so historically-ingrained and replicated as caste. While the caste-system was abolished and caste-based discrimination criminalized, it continues to impact health with regards to social mobility and opportunities. Even today, women in an “untouchable” caste have a lower life expectancy and reduced healthcare access compared to their upper-caste counterparts. While both caste and race are socially ascribed dimensions used to stratify individuals, caste, unlike race, is generationally inherited. In this project, I sought to determine whether caste was a significant predictor of three health outcomes: TB, anemia, and health-insured status, when controlling for age and wealth index and accounting for spatial factors.

## VISUALIZATIONS: 
The exposure image file depicts the distribution of scheduled castes and tribes across India (based on the data from the National Family Health Survey). Statistically significant clustering is also included of areas with high and low proportions of scheduled castes and tribes. The map and data are at district levels.

![Scheduled Castes & Tribes](exposure.png)


The model1 file depicts the results of a geographically weighted regression model: TB as an outcome of multiple predictors, including caste. Districts which have a positive association with proportion of scheduled castes/tribes and TB prevalence are depicted as green while districts which have a negative association with proportion of scheduled castes/tribes and TB prevalence are depicted as blue.

![TB](model1_slope.png)
