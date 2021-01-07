# Materials-Informatics-Ti-alloy-Oxidation 


This project is very special to me as this was my first End-2-End (conceptualization to ML model) project. The core objective is to develop a ML model which can predict the "Oxidation rate constant" (corrosion rate) of Ti alloys which is critical to determine their life span. This is critical to aerospace industries as the Ti alloys are critical component of jet engines. This model may help to ascertain when different components of jet engines will require replacement in order to prevent any engine failure. 

I started with data collection. The data was collected from various experimental papers. I compiled the Ti alloy composition, oxidation time, conditions and others factors which are relevant to predict the oxidation/corrosion rate. The absence of these values in the text prohibited the use of webscraping method.
Over 200 relevant research papers were manually scanned following which about thirtyfive papers were finalized from which the entire dataset was created. Different papers use different measurement units, hence I changed all them to a standard unit format (for all the features). 

In this study, I have used four different ML models:- (a) Support Vector Regressor, (b) Random Forest Regressor, (c) Gradient Boosting Regressor, and (d) Xtreme Gradient Boosting. For each of these ML models, the hyperparameter optimization was performed using the Randomized Search method with a 10 fold cross validation. 

Among all the ML models, the Xtreme Gradient Boosting model gives the best prediction as indicated by the root mean squared error and coefficient of determination. 

For this project, I am grateful to Prof. Takayuki Narushima and Dr. Ryoji Sahara for their support and guidance.  
