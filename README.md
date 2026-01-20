# Sampling Assignment

csv link: https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv

## Sampling techniques used

Five different samples were created after balancing the dataset:

sample1 – simple random sampling  
sample2 – stratified sampling  
sample3 – cluster sampling  
sample4 – systematic sampling  
sample5 – bootstrap sampling  

note that these techniques were chosen as they were discussed in class.


## ML models used

1. M1 – Logistic Regression  
2. M2 – Decision Tree  
3. M3 – Random Forest  
4. M4 – Naive Bayes  
5. M5 – KNN 


## Methodology

1. The dataset was first loaded and checked for class imbalance.
2. Random Oversampling was used to balance the dataset.
3. Five samples were created using different sampling techniques.
4. Each sample was split into training and testing data.
5. All five models were trained on each sample.
6. Accuracy was calculated thereafter. 


#result
	1.	Logistic regression (M1) performed best with bootstrap sampling (sample5) with an accuracy of 99.13%.
	2.	Decision tree (M2) achieved its highest accuracy of 99.56% using bootstrap sampling (sample5).
	3.	Random forest (M3) showed the best performance with simple random, stratified, and cluster sampling (sample1, sample2, sample3), achieving 100% accuracy.
	4.	Naive bayes (M4) performed best with bootstrap sampling (sample5) with an accuracy of 92.79%.
	5.	KNN (M5) achieved the highest accuracy of 99.34% using bootstrap sampling (sample5).



