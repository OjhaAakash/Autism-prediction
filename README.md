# Autism-prediction

Data Set Name: Autistic Spectrum Disorder Screening Data for Toddlers – 
Date: July, 22, 2018.
Author: Dr Fadi Thabtah
Abstract: Autistic Spectrum Disorder (ASD) is a neurodevelopmental  condition associated with significant healthcare costs, and early diagnosis can significantly reduce these. Unfortunately, waiting times for an ASD diagnosis are lengthy and procedures are not cost effective. The economic impact of autism and the increase in the number of ASD cases across the world reveals an urgent need for the development of easily implemented and effective screening methods. Therefore, a time-efficient and accessible ASD screening is imminent to help health professionals and inform individuals whether they should pursue formal clinical diagnosis.  The rapid growth in the number of ASD cases worldwide necessitates datasets related to behaviour traits. However, such datasets are rare making it difficult to perform thorough analyses to improve the efficiency, sensitivity, specificity and predictive accuracy of the ASD screening process. Presently, very limited autism datasets associated with clinical or screening are available and most of them are genetic in nature. Hence, we propose a new dataset related to autism screening of toddlers that contained influential features to be utilised for further analysis especially in determining autistic traits and improving the classification of ASD cases. In this dataset, we record ten behavioural features (Q-Chat-10) plus other individuals characteristics that have proved to be effective in detecting the ASD cases from controls in behaviour science. 
Source: Fayez Thabtah
Department of Digital Technology
Manukau Institute of Technology,
Auckland, New Zealand
fadi.fayez@manukau.ac.nz
Data Type: Predictive and Descriptive: Nominal / categorical, binary and continuous 
Task: Classification
Attribute Type: Categorical, continuous and binary  
Area: Medical, health and social science
Format Type: Non-Matrix
Does your data set contain missing values? No
Number of Instances (records in your data set): 1054
Number of Attributes (fields within each record): 18 including the class variable 
Attribute Information:  For Further information about the attributes/feature see below table.

Attributes:
A1-A10: Items within Q-Chat-10  in which questions possible answers : “Always, Usually, Sometimes, Rarly & Never” items’ values are mapped to “1” or “0” in the dataset. For questions 1-9 (A1-A9) in Q-chat-10,  if the respose was  Sometimes / Rarly / Never “1” is assigned to the question (A1-A9). However, for question 10 (A10), if the respose was Always / Usually / Sometimes then “1” is assigned to that question. If the user obtained More than 3 Add points together for all ten questions. If your child scores more than 3 (Q-chat-10- score) then there is a potential ASD traits otherwise no ASD traits are observed.
The remaining features in the datasets are collected from the “submit” screen in the ASDTests screening app. It should be noted that the class varaible was assigned automatically based on the score obtained by the user while undergoing the screening process using the ASDTests app.

Relevant Papers:  
1) Tabtah, F. (2017). Autism Spectrum Disorder Screening: Machine Learning Adaptation and DSM-5 Fulfillment. Proceedings of the 1st International Conference on Medical and Health Informatics 2017, pp.1-6. Taichung City, Taiwan, ACM.
2) Thabtah, F. (2017). ASDTests. A mobile app for ASD screening. www.asdtests.com [accessed December  20th, 2017].
3) Thabtah, F. (2017). Machine Learning in Autistic Spectrum Disorder Behavioural Research: A Review. Informatics for Health and Social Care Journal. 
4) Thabtah F, Kamalov F., Rajab K (2018) A new computational intelligence approach to detect autistic features for autism screening. International Journal of Medical Infromatics, Volume 117, pp. 112-124.

Table 1: Details of variables mapping to the Q-Chat-10 screening methods
Variable in Dataset	Corresponding Q-chat-10-Toddler Features
A1	 Does your child look at you when you call his/her name?
A2	How easy is it for you to get eye contact with your child? 
A3	Does your child point to indicate that s/he wants something? (e.g. a toy that is 
out of reach) 
A4	Does your child point to share interest with you? (e.g. poin9ng at an 
interes9ng sight) 
A5	Does your child pretend? (e.g. care for dolls, talk on a toy phone) 
A6	Does your child follow where you’re looking? 
A7	If you or someone else in the family is visibly upset, does your child show signs 
of wan9ng to comfort them? (e.g. stroking hair, hugging them)
A8	Would you describe your child’s first words as: 
A9	Does your child use simple gestures? (e.g. wave goodbye) 
A10	Does your child stare at nothing with no apparent purpose? 









It is recommended to discard the Score variable as it has been used to assign the class label so if you keep the score variable the models derived might be overfitted.
![image](https://github.com/OjhaAakash/Autism-prediction/assets/114509223/c7f55210-b4b5-45ce-81dc-93574ad0fa47)
