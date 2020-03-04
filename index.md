# Caste and Health in India

## BACKGROUND:
Among the health inequities in India, none is so historically-ingrained and replicated as caste. While the caste-system was abolished and caste-based discrimination criminalized, it continues to impact health with regards to social mobility and opportunities. Even today, women in an “untouchable” caste have a lower life expectancy and reduced healthcare access compared to their upper-caste counterparts. While both caste and race are socially ascribed dimensions used to stratify individuals, caste, unlike race, is generationally inherited. In this project, I sought to determine whether caste was a significant predictor of three health outcomes: TB, anemia, and health-insured status, when controlling for age and wealth index and accounting for spatial factors.

## VISUALIZATIONS: 
The exposure image file depicts the distribution of scheduled castes and tribes across India (based on the data from the National Family Health Survey). Statistically significant clustering is also included of areas with high and low proportions of scheduled castes and tribes. The map and data are at district levels.

![Scheduled Castes & Tribes](exposure.png)


The model1 file depicts the results of a geographically weighted regression model: TB as an outcome of multiple predictors, including caste. Districts which have a positive association with proportion of scheduled castes/tribes and TB prevalence are depicted as green while districts which have a negative association with proportion of scheduled castes/tribes and TB prevalence are depicted as blue.

![TB](model1_slope.png)



# CONCLUSION:
## Discussion:
I hypothesized that based on my knowledge, the scheduled caste coefficient would have a positive effect on both TB and anemia cases, while having a negative correlation with health scheme status. Two of the three global models (health scheme and anemia) did not align with my hypothesis. However, when running local models, some districts did have coefficients in agreement with my hypothesis (which was based on my literature review). This is crucial because India’s health care policies are heterogeneous and dependent on both state and local policies. This could dictate future research in which the impact of local health policies in India on scheduled castes and tribes are evaluated.

## Limitations:
Some limitations of these analyses include the loss of heterogeneity when dichotomizing castes. India contains multiple scheduled castes and tribes, all of which have experienced different forms of oppression. Disaggregating caste as a category in future health surveys could provide deeper insight into the various needs of scheduled caste/tribe communities. Additionally, this model was based on aggregate values (i.e. the median age) rather than using a clustered, multilevel analysis. Weights provided in the dataset were not used, so we also do not have assurance of external validity. 

## Future Research:
Future studies should disaggregate data, include population density as a variable, and consider local health policies and programs when considering the impact of caste on health.
