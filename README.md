# Comorbidity Index
Comorbidity means multiple disease diagnosis for a patient. In EHR data, usually each patient at each encounter will have one primary diagnosis as well as several other non-primary diagnoses. The co-exist of such multiple disease diagnoses is called comorbidity. From data analysis point of view, the comorbidity is a very useful indicator for clinical outcomes such as mortality. So it is desired to summarise the comorbidity into one score. There are serveral ways to calculate the comorbidity index such as Charlson Comorbidity Index, Elixhauser Comorbidity Index and NCI Comorbidity Index. 

This python package is designed to calculate those comorbidity index. 

## Charlson Comorbidity Index
Charlson et al. proposed this comorbidity index in their 1987 paper, [A new method of classifying prognostic comorbidity in longitudinal studies: development and validation](https://www.ncbi.nlm.nih.gov/pubmed/3558716), which has been cited more than 20,000 times since then. Based on the data of 607 patients admitted to medical service in one month period, they proposed a comorbidity index including 17 diseases with different weights. They showed that this comorbidity index is good indicator for one-year mortality. 
