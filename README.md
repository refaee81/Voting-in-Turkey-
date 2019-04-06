# Voting-in-Turkey-

Who votes for the AKP party in Turkey? 
Research/Project Questions: 
Who votes for the AKP party in Turkey? What factors drive the voting tendency in Turkey?
 Literature Hypotheses 
People who are religious and conservative tend to vote for the AKP Party . People who have high economic optimism tend to vote for the AKP Party. Kurdish people do not tend to vote for the AKP Party. Women vote less for the AKP Party. People who are highly educated do not vote for the AKP Party. High social class people do not tend to vote for the AKP Party. Young and well educated people do not tend to vote for the AKP Party. 
Data Description  
Data retrieved from the Worlds Values Survey website. The World Values Survey is a periodical survey conducted every 2 – 3 years and highlights trends and patterns in the global politics. The dataset is representative of the adult population of Turkey aged 18+ and the size is 1,605 respondents. The dependent variable was the respondents’ votes in the last Turkish elections classified into three classes: Vote for AKP, Not Vote, Other. The below independent variables have been selected:  Religiousity_Coded ,  Economic_Satisfaction_Coded,  Ideology_Coded, Employment_Coded, Social_Class_Coded, Income_Coded, Sex_Coded, Age_Coded, Ethnicity_Coded, Education_Coded. 
Research Question Answers: 
We can describe the voters of AKP party in Turkey are predicted to be religious married +30years who are ethnically Turkish and ideologically rightists, with middle to high income and mostly living in east of Turkey. 
Models Scores & Results: 
The R-squared of initial OLS regression was around 0.15 and some variables held insignificant P-Values. Thus, classification models reflected better performance results and predication accuracies. 
The best classification score came by Random Forest Model enhanced with Gridsearch at 0.61. This is just slightly more than KNN-gridsearched with 0.60 and SVM-gridsearched with 0.59. For further details of the best parameters for each gridsearch, see blow: 
Model	Model Score	GridSearch Score
Logistic Regression 	0.526	0.55
KNN	0.502	0.621
Random Forest 	0.487	0.613
SVM	0.525	0.592

 
References
•	http://www.worldvaluessurvey.org/WVSDocumentationWV6.jsp 
•	Cook, R. Dennis (February 1977). "Detection of Influential Observations in Linear Regression". Technometrics. American Statistical Association. 19 (1): 15–18. doi:10.2307/1268249. JSTOR 1268249. MR 0436478.
•	https://datascienceplus.com/perform-logistic-regression-in-r/ 
•	Akarca, A. T. (2009). A prediction for AKP’s nationwide vote share in the 29 March 2009 Turkish local elections. İktisat İşletme ve Finans , 24 (276), 8-22.
•	Baslevent, C., & Akarca, A. T. (2008). Micro evidence on inter-party vote movements in turkey: Who voted for AKP in 2002? Munich: Munich Personal RePEc Archive (MPRA).
•	Carkoglu, A. (2011). Turkey’s 2011 General Elections: Towards a Dominant Party System? Insight Turkey , 13 (3), 43-62.
•	Carkoglu, A., & Hinich, M. J. (2006). A spatial analysis of Turkish party preferences. Electoral Studies , 25 (2), 369-392.
•	Çarkoglu, A. (2009). Turkey's local elections of 2009: winners and losers.Insight Turkey, 11(2), 1.
•	Dickenson, M. (2012). Turkish Foreign Policy and Public Opinion in the AKP Era. Foreign Policy Analysis , 1-18.

