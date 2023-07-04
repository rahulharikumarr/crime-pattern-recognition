# crime-pattern-recognition
Deep Learning for Crime Pattern Recognition: A study of Crime Hotspots and High-Risk Areas.

Crime is a global problem that affects individuals, communities, and societies at large. There are many different types of crime, and the rates at which they occur vary widely from country to country. While the need to be able to detect crime as it is happening is a very important part of safety and security, systems that can predict and analyze crimes are just as vital to a safer world. Understanding crime patterns and trends is crucial for effectively addressing the issue. One way to gain insights into crime is through the use of crime data analysis systems. These systems can help law enforcement agencies, policymakers, and researchers to identify patterns and trends in crime, as well as evaluate the effectiveness of different crime-prevention strategies. 

In our study, we used four distinguished approaches: eXtreme Gradient Boosting (XGBoost), CatBoost, Tabnet, along with a hybrid model 1 Dimensional Convolution Neural Network through three individual datasets to compare the results of each approach as well as a comparison between the three datasets. Our results demonstrated a very significant advantage of utilizing feature oriented datasets over a large sample size such as the Chicago dataset. We observed XGBoost provides the best results for Chicago and San Francisco, with 96.51% and 26.50% accuracy respectively. And as for Boston, we obtained best accuracy (20.80%) using the Bagging classifier.


# Results

![results crime](https://github.com/rahulharikumarr/crime-pattern-recognition/assets/52792591/cd397d86-764a-4fcf-aaba-cce7484ccccc)

#Individual Detection Rates for each crime were also compared as part of our research:

## Chicago crime prediction rates(Using an xGBoost model):
![xgboost crime](https://github.com/rahulharikumarr/crime-pattern-recognition/assets/52792591/3c1486dc-30ca-4ba8-b0a0-5e5eaed230e1)

## Boston crime prediction rates(using a Bagging Model):
![bagging crime](https://github.com/rahulharikumarr/crime-pattern-recognition/assets/52792591/a921a19e-a993-49e7-96e9-8253c0a43f8e)

## San Francisco crime prediction rates(Using an xGBoost model):
![xgboost sf](https://github.com/rahulharikumarr/crime-pattern-recognition/assets/52792591/16ecb075-a0d7-4f06-aa08-6f44b480e73b)



