**INFO**:
- ARP MitM Ettercap dataset used can be found here:
	- https://archive.ics.uci.edu/ml/datasets/Kitsune+Network+Attack+Dataset
	
- The goal of this project was to use machine learning to classify malicious packets quickly and efficiently

Code for the following sections can be found in the following files:

a) Project Writeup:

- NicholasNuti_KitsuneNetworkAttack.pdf

b) Dataset Visualization:

-  Dataset_Visualization - ARP MitM_dataset.ipynb


c) Dataset Cleaning:

- The results from dataset cleaning were unsuccessful
- So the bad results can be found in: 
	
	- Logistic Regression with IQR (Unsuccessful Results) - ARP MitM_dataset.ipynb
	- Logistic Regression with Z-score (Unsuccessful Results) - ARP MitM_dataset-Copy1.ipynb

d) Related Work:

- Can be found in the project writeup PDF

e) Feature Extraction:

- Feature Extraction was done using Extra Trees Classifier and Select K Best Classifier
- Results can be found in the following file:
	
	-  FeatureSelection.ipynb


f) Model Development:

- Classification models were constructed in the following files:
	
	- Logistic Regression - ARP MitM_dataset.ipynb
	- Random Forest Classifier - ARP MitM_dataset.ipynb
	- LDA - ARP_MitM_dataset.ipynb
	- QDA - ARP_MitM_dataset.ipynb


g) Fine-tune model

- Optimization for Random Forest Classifier did not need to be done
- Use the following for Random Forest Classifier when trying to find most optimal model:
	
	- Random Forest Classifier - ARP MitM_dataset.ipynb

- When optimizations were possible they were done in the following files:
	
	- TUNING - Logistic Regression - ARP MitM_dataset.ipynb
	- TUNING - LDA - ARP_MitM_dataset.ipynb
	- TUNING - QDA - ARP_MitM_dataset.ipynb

h) Performance

- All performance metrics for most optimal models can be found in the following files:
	- Random Forest Classifier - ARP MitM_dataset.ipynb
	- TUNING - Logistic Regression - ARP MitM_dataset.ipynb
	- TUNING - LDA - ARP_MitM_dataset.ipynb
	- TUNING - QDA - ARP_MitM_dataset.ipynb

