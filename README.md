Dengue Prediction Model (Singapore)
Predicting weekly dengue outbreaks in Singapore using climate data and ML models.

Data Sources
Dengue cases: Weekly reports from data.gov.sg

Weather data: Mean temperature & rainfall from WeatherSpark

Objective
Build a model to predict high-risk dengue outbreak weeks based on weather patterns to support proactive public health interventions.

Preprocessing
Filtered years 2014–2018

Removed dengue hemorrhagic fever (DHF) cases

Merged weather + dengue data

Labeled outbreaks: 1 if dengue cases > 225

Models Tested
Model	                Accuracy	Precision	 Recall	 RMSE
Logistic Regression	  96.2%	      0.50	    0.48	 0.194
K-Nearest Neighbors	   84.9%	    0.50	    0.42	 –
Decision Tree	        52.8%	      0.50	    0.26	 –

Best Model: Logistic Regression

Key Findings
Dengue outbreaks correlate with higher temperatures (28–29°C) and low rainfall.

Logistic regression performed best and generalized well.

🛠️ Tech Stack
Python, pandas, scikit-learn, seaborn, matplotlib
