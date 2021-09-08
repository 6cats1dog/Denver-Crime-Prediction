![img](https://github.com/6cats1dog/Denver-Crime-Prediction/blob/main/Denver-Police-Car-and-Night-View-of-City.jpeg)
# Denver Crime Prediction
In this capstone project, we attempt to predict crime in Denver's neighborhoods and the impact of the neighborhoods demographic features

## **Background** 

Crime is a challenging social problem across major cities and metropolitan areas across the United States. When we look at the statistics leading up to 2021 the results are astounding. In Denver, business burglaries are up by 143 percent, carjackings are up by 140 percent and homicides are up 81 percent since 2019. As crime increases, it is important to try to find novel ways to implement crime prevention, and this project's goal is to use that through prediction, focused on neighborhoods and time of day.

## **Business Problem**

The goal of this project is to predict crime that will occur, based on the location in Denver's 78 nieghborhoods. Predicting crime will help solve the challenge of allocating resources were they are most needed, leading to safer communities and crime prevention.  

This project will be helpful for various different populations. It will be helpful for those that wish to move to the Denver area, as they will be able to determine what area they would like to move to. Also, it will be helpful for locals and tourists alike in the sense that they will be able to determine what places should be avoided or at what time their risk of being a victim of a crime might be higher. Most importantly, I believe that this could help in the allocation of resources whether it would mean a more equal distribution of police resources or better allocation of city funds to put in place preventative measures to make more affected communities safer. The goal is to raise awareness to the increase in crime, and the neighborhoods in Denver that are requiring the most help reducing this issue.

## **Methodology**

* Build a model that can predict the most common crimes occurring in Denver’s neighborhoods

* Correlate demographic features to particular crime categories such as theft or assault

* Accomplished using Denver’s Open Data Catalog

* Use supervised models such as XGBoost, Decision Trees and Random Forest to predict crime.

## **Results**

The results for our models were as follows:

* Random Forest Model: 24%
* Decision Trees Model: 32%
* XGBoost Model: 27%

Although these are not satisfactory results, there is understanding as to the challenges that were faced during modeling. The complexity of the models with all the features created challenges correlated with predictive models for crime. Research has failed to produce efficient models when it comes to large datasets such as the one that we worked with. In some models, high levels of accuracy were able to be achieved, however these results were limited to small datasets with limited features. The important features that need to be considered when using Machine Learning in order to predict crime is the computational speed, robustness and the scalability of our data. It is important to note as well that a small change in the data could lead to a large change in structure of our data.

## **Recommendations Proposed**

## **Conclusion and Future Work**
In an extension to the work that has been completed, it is planned to add more classification models to hopefully increase the crime prediction accuracy and hopefully enhance overall performance. It is also the hope to include previously excluded features from the demographic portion of our dataset. We have the option to add gender, education level, earnings levels and race into our model. It will be interesting to see if any of these demographics make a sizable impact on the performance of our model.

Also, it will be helpful in the future to continue including more data from the Denver crime dataset to see if there are more noticeable trends in the future. This framework can also hopefully be extended to other major metropolitan cities such as Chicago and Los Angeles to see if there may be other pivotal features that can increase model performance. The goal is to hopefully increase the audience to the work of using Machine Learning programs to help inform local law enforcement and community leaders to keep neighborhoods safe.
