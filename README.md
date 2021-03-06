# Tiru_portfolio   

[PROJECT 1: Capstone Project: E-Commerce Data Analysis: Product Categorization And Sales Prediction]( https://github.com/Wale-Agboola/UMBC_CAPSTONE_2022/blob/main/Capstone_Product_Categorization_Sales_Prediction.ipynb)

This Capstone project is a group of two Wale-Agboola and me. It is mainly focused how the unsupervised machine learning algorithm (NLP topic modeling) appled in E-commerce data to categorize products based on their description.

*	- Wrangled 2 years of daily UK based online shopping retailer’s data.
*	- Applied various NLP techniques for preprocessing the text data.
*	- Built topic modeling (LDA model) to categorize (cluster) products by their description. 
*	- Performed time series data analysis and prepared the data before constructing the prediction model.
*	- Applied various prediction models and evaluated them for prediction and forecasting sales and demands for each product category.
      *	- Apllied LSTM model and found overfitted to most of the clusters, however, it performed very well in forecasting future sales.
      *	- Built stacking model to ensamble the performance of base-models (ExtraTreesRegressor,AdaBoostRegressor,RandomForestRegressor,LinearSVR) and enable to run the same boosted model against all clusters.
      
* WordCloud -  to show the clean tokens after the preprocessing function applied on the text data.
![WordCloud](https://github.com/twubghub/Tiru_portfolio/blob/main/images/wordcloud.png) 

* LDA Visualization - shows the 10 bubles that represent topics(clusters) and the blue bare represents the overall frequency of each word in the corpus.
![PyLDAviz](https://github.com/twubghub/Tiru_portfolio/blob/main/images/pyldavis.png)
![Total and Average Sales](https://github.com/twubghub/Tiru_portfolio/blob/main/images/sales.png)
* Stacking prediction graph
*
![Stacking Prediction](https://github.com/twubghub/Tiru_portfolio/blob/main/images/stacking.png)
* LSTM Prediction graph
*
![LSTM Prediction](https://github.com/twubghub/Tiru_portfolio/blob/main/images/LSTM_prediction.png)
* LSTM Forecasting graph

![LSTM Forecasting](https://github.com/twubghub/Tiru_portfolio/blob/main/images/LSTM_forecasting.png)


[PROJECT 2: Computer Vision for Object Detection](https://github.com/twubghub/All_projects/blob/main/Deep_Learning_project_final.ipynb)


 The project is a group project which focused on building models to detect objects on roads for self driving cars. There are about 11 classes such as cars, truck, signals, pedstrians and others in this project then constructed object detection models to classify, locate and label those classes. 


* Analyzed the dataset

* Visualized the data

* Built models

* Test and Evaluated models

* Used NMS to avoide overlapped bounding boxes
![Object detection model 1's output](https://github.com/twubghub/Tiru_portfolio/blob/main/images/object_detection.png)

![Object detection model 2's output](https://github.com/twubghub/Tiru_portfolio/blob/main/images/object_detecion2.png)
![Object detection model 3's output](https://github.com/twubghub/Tiru_portfolio/blob/main/images/object_detection3.png)

[PROJECT 3: COMPUTER VISION PROJECT](https://github.com/twubghub/All_projects/blob/main/Project%203_Computer_Vision.ipynb)

![](https://github.com/twubghub/Tiru_portfolio/blob/main/images/Computer_Vision_pic.png)

This project is a group project manily focused on big data analysis to classify 10 classes of animal images using convolutional neaural network on spark enviroment and hadoop distribution file system (HDFS) used for storage purpose.
 * Downloaded the data from kaggle and Prepared it to store it to local HDFS.
 *  Analyzed the data using spark programing and rearrange the data to fit it into the models.
 *  Trained many convolutional neaural network (CNN) models by changing their parameters to get a better performance accuracy.
 *  Visualized and concluded the results that have gotten from different models.
 
 ![](https://github.com/twubghub/Tiru_portfolio/blob/main/images/heatmap_port.png)
 
 
 ![](https://github.com/twubghub/Tiru_portfolio/blob/main/images/Acccuracy_Curve_Port.png)



[PROJECT 4: CLASSIFICATION PROJECT](https://github.com/twubghub/All_projects/blob/main/Project4_DryBeanData.ipynb)
This project is about classification that provides a method to obtain uniform dry beans seed varieties by using machine learning algorithms to classify them with better accuracy than the existing one which was 93.3%.

![](https://github.com/twubghub/Tiru_portfolio/blob/main/images/DryBeans_image.png)
* Implemented EDA such as dsplaying the data, cleaning the data by removing the duplicated data, avoiding outliers using interquartile range method then Balancing classes using SMOTE method.
* Prepared the data and fitted models. we trained many models and applied various techniques to get a better accuracy perforamnce.
* Evaluated  models, so among the models we used Bagging, SVM nonlinear kernel and keras TensorFlow models provided the highest accuracy more than 95%. 
* Concluded the result. Keras provided the highest accuracy for unseen(test) data with 95%.

![](https://github.com/twubghub/Tiru_portfolio/blob/main/images/SVM_Classifier_Port.png)

![](https://github.com/twubghub/Tiru_portfolio/blob/main/images/Training%20and%20validation%20curve_Port.png)

[PROJECT 5: STOCK PRICE PRIEDICTION BASED ON SENETIMENT ANALYSIS](https://github.com/twubghub/All_projects/blob/main/NLP_Project_model_Final%20(1).ipy)

Natural Languge Processing (NLP) project on senetiment analysis for stock price prediction from social media data source such as Twitter, Reddit and Wallstreet.
* Collected public opinion text data from social medias(Twitter and Reddit) and the stock price from wallstreet.
* Applied EDA, 
* Applied NLP to get numeric values of sentiments and see the trend of stock price whenever change in sentiments by applying Random Forest Classifier model.
* Built Random Forest Regressor to predict stocks' prices based on public opinion.
*  Evaluated models
*  Visualized results

![](https://github.com/twubghub/Tiru_portfolio/blob/main/images/Reddit.png)
![](https://github.com/twubghub/Tiru_portfolio/blob/main/images/Apple_stock.png)

[PROJECT 6: EXPLORATORY DATA ANALYSIS AND HYPOTESIS TESTING OF SURVEY DATA](https://github.com/twubghub/All_projects/blob/main/project_1_Notebook.ipynb)

* Applied EDA for 2019 NHIS data; displaying, cleaning and visualising the data.
* Implemented hypotesis testing such as, T-test, Z-test, Chi-Square, Anova and so on to test the relationship of different variables and their significant impact into one   another.
* Concluded the outcomes on different groups based on those various satastical tests.

![Percentage distribution of BMI by Sex](https://github.com/twubghub/Tiru_portfolio/blob/main/images/prot-graph.png)
![BMI vs Cholostrol](https://github.com/twubghub/Tiru_portfolio/blob/main/images/Cholostrol_port.png)

