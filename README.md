
Project – Wine Quality



Introduction: The wine industry shows a recent exponential growth as social drinking is on the rise. Nowadays, industry players are using product quality certifications to promote their products. This is a time-consuming process and requires the assessment given by human experts, which makes this process very expensive. Also, the price of red wine depends on a rather abstract concept of wine appreciation by wine tasters, opinion among whom may have a high degree of variability. Another vital factor in red wine certification and quality assessment is physicochemical tests, which are laboratory-based and consider factors like acidity, pH level, sugar, and other chemical properties. The red wine market would be of interest if the human quality of tasting can be related to wine’s chemical properties so that certification and quality assessment and assurance processes are more controlled. This project aims to determine which features are the best quality red wine indicators and generate insights into each of these factors to our model’s red wine quality.
Advantages of Wine: Studies have found that consuming moderate amounts of wine along with a balanced diet rich in fruits and vegetables is beneficial for your health. Research has found the optimal daily amount to be 1 glass (150 ml) for women and 2 glasses (300 ml) for men. This regimen is part of a Mediterranean diet and has been associated with beneficial health outcomes and disease prevention. Although research suggests that drinking a glass of wine has several potential health benefits, they can also be obtained by eating a healthy diet. In other words, if you didn’t drink wine before, you don’t need to start simply for the health benefits. For example, a healthy diet rich in fruits, vegetables, whole grains, fibre, legumes, fish, and nuts already provides high amounts of antioxidants and helps prevent heart disease.
Purpose of Project: This data will allow us to create different regression models to determine how different independent variables help predict our dependent variable, quality. Knowing how each variable will impact the red wine quality will help producers, distributors, and businesses in the red wine industry better assess their production, distribution, and pricing strategy.
Project Introspection:  The purpose of this project is to create an algorithm that assesses red wine quality as good or terrible. The influence of 11 characteristics (pH, citric acid, density, and so on) on wine quality was tested in the dataset to arrive at this categorization. The learning approach employed was logistic regression learning. According to experts, the wine is differentiated according to its smell, flavour, and colour. This is a machine learning project classifying the quality of red wine as 'good' or 'bad'. The data is from UC Irvine's Machine Learning Repository.

Data Understanding: We have obtained the red wine data samples from the north of Portugal to model red wine quality based on physicochemical tests. The dataset contains a total of 12 variables, which were recorded for 1,599 observations. 
Objective: To check which variables are likely to affect the quality of red wine the most and to analyse a list of variables of interest that had the highest correlations with quality.
Description of Data Set: 
a)	Data Source: https://towardsdatascience.com/red-wine-quality-prediction-using-regression-modeling-and-machine-learning-7a3e2c3e1f46 
b)	Reference Source: https://archive.ics.uci.edu/ml/datasets/wine+quality 
c)	Inputs/Data Set Information: The dataset is related to red variants of the Portuguese "Vinho Verde" wine. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g., there is no data about grape types, wine brand, wine selling price, etc.).These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g., there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. So, it could be interesting to test feature selection methods. 


d)	Attribute Information: 
•	Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulphur dioxide
7 - total sulphur dioxide
8 - density
9 - pH
10 - sulphates
11 – alcohol
•	Output variable (based on sensory data):
12 - quality (score between 0 and 10)
Preliminary Exploratory Data Analysis: 1) The given table below shows data for the given parameters for Red Wine quality.
 
2) The given heatmap shown below, determines the parameters for the Red Wine quality index, where parameters range from -0.6 to 0.9. Each of the following equal index, it shows the value as 1, and for the rest of the parameters it varies.
 
Expected Outcome: The outcome for the given data shows the quality for the respective variables of red wine, in a range of 0 to 10. Hence, it specifies the intake and the need of the red wine accordingly to the producers.
References:
•	 https://www.ijsr.net/archive/v9i7/SR20718002904.pdf
•	Paulo Cortez1, Juliana Teixeira1, Ant´onio Cerdeira2, Fernando Almeida2,m Telmo Matos2, and Jos´e Reis12, 1 Dep. of Information Systems/Algoritmi Centre, University of Minho, 4800-058 Guimar˜aes, Portugal,
•	K. Thakkar ,J. Shah, R. Prabhakar ,A. Narayan ,A. Joshi, “AHP and MACHINE LEARNING TECHNIQUES for Wine Recommendations,” International Journal of Computer Science and Information Technologies,7(5)


