# Sparkify-Capstone-Project
Determine customer churn for a music streaming company called Sparkify.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Important Files](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
This project uses the following software and python libraries

- Python 3.6
- Anaconda python distributed files
- Pyspark-2.4.1


## Project Motivation<a name="motivation"></a>

Sparkify is a music streaming service just as Spotify and Pandora.

The data provided is the user log of the service, having demographic info, user activities, timestamps and etc. We try to analyze the log and build a model to identify customers who are highly likely to quit using our service, and thus, send marketing offers to them to prevent them from churning.

In this project we'll be performing the following tasks:

1. Data Exploration   
2. Define Churn and label data based on churn definition    
3. Feature Engineering    
4. Data transformation, data splitting and model training
5. Build model and predict the accuracy of the model
    
## File Descriptions <a name="files"></a>
* Sparkify.ipynb : Jputer notebook used for this project


## Results<a name="results"></a>
We have analysed the sparkify dataset and come up with new features to predict churn. We then created a machine learning model and tuned it to improve its performance. We achieved an accuracy score of - and F1 score of - on the test dataset. 

# Conclusion
We have used Random Forest algorithm for the modelling and we were able to get an accuracy score of -- and F1 score of -- on the test dataset. The model peformance can be further improved by creating additional features. Once we are satisfied with this smaller dataset, we can utilize the entire sparkify dataset for better results.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit to Udacity

[Click here to read the post on Medium](https://medium.com/@ronyjoby/sparkify-predict-customer-churn-9545d81b7d77?sk=cc86710b3d2fe0c2cd61b033ae8df96d)
