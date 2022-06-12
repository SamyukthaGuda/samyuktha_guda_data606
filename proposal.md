**UMBC DATA606 Data Science Capstone Project**

## Capstone Project Proposal ##

# “We turn fertile lands into deserts by using ineffective farming technologies. There is no future until we return to effective farming and save the soil.” 
## Team: Roles and Responsibilities ##

In this project, we will be presenting a website in which the following applications would be implemented; Crop recommendation, Fertilizer recommendation, and Plant disease prediction, respectively.

# Samyuktha Guda #

Crop recommendation application - Data cleaning, Visualization, Decision tree, naive, SVM, Logistic regression, XG-boost

**Samyuktha Jalagam**

Fertilizer recommendation application – Data Visualization using Matplotlib, Decision tree, naive, SVM, Logistic regression, XG-boost

**Nikhitha Alla**

Plant disease prediction application - Image pre-processing, ResNet 50 classification, Feature extraction

**What is your issue of interest (provide sufficient background information)?**

Agriculture is an integral part of India's socio-economic fabric. Farmers' failure to choose the best crop for the land using non-scientific and traditional methods is a severe problem in a country where farming employs approximately 58 percent of the population. Farmers have occasionally failed to select suitable crops based on the condition of the soil, sowing season, and geographic location. As a result, people commit suicide, leave agriculture, and seek employment in cities. To address the problem mentioned above, this study proposed a system to assist farmers in crop selection by considering all the factors such as sowing season, soil condition, and geographic location. Precision agriculture is also being implemented with modern agricultural technology and is evolving. This project uses machine learning approaches like Random Forest and Decision Tree to predict which crop is best for which soil type based on the data sets. According to previous studies, 42 percent of agricultural production is lost, and this is due solely to the rising rate of plant leaf disease losses. This plant leaf disease detection technique can be used to detect a disease from the input images to solve this significant problem. Image pre-processing, image segmentation, and feature extraction were all part of this process.

**Why is this issue important to you and/or to others?**

Farming is one of the major sectors that influences a country’s economic growth. In a country like India, the majority of the population is dependent on agriculture for their livelihood. Agriculture is becoming more prominent as new technologies emerge, as it is used not only to feed a large population but also in various applications. Plants are significant in our lives because they provide energy and help to combat global warming. Many diseases affect plants today, causing devastating economic, social, and ecological losses, among other things. As a result of it, it is critical to identify plant diseases accurately and quickly. 
Furthermore, 48% of farmers do not want their children to be involved in agriculture and instead prefer to live in cities. This is because farmers frequently make poor crop selection decisions, such as choosing a crop that will not yield much for the soil, planting in the wrong season, etc. The farmer may have purchased the land from others, so the decision was made without prior experience. A reduced yield will always come from poor crop selection. It is challenging to survive if the family relies entirely on this income. To address all these issues, with the resources at our disposal, we would like to present a system to solve by providing predictive insight and guidance on crop sustainability based on machine learning models trained using critical environmental and economic parameters.

**What questions do you have in mind and would like to answer?**

         How to safeguard the soil from losing its fertility owing to poor farming techniques?
         How to treat crop disease organically rather than using heavy fertilizers?
         How to Cultivate the right crop in the right soil to reduce the risk of soil property degradation?

**Where do you get the data to analyze and help answer your questions (creditability of source, quality of data, size of data, attributes of data. etc.)**

Here, we will be considering datasets for exploring and analyzing the suitable crop data from various trustworthy sources, including data.gov.in and kaggle.com. 
The data sets are for the states of Maharashtra and Karnataka. State, district, year, season, type of crop, the area under cultivation, production, and so on are all included in the data. Other datasets with state and district specifications include the soil type as an attribute. This soil type column is extracted from the primary data set and merged. 

Data:
https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

This dataset consists of about 87K rgb images of healthy and diseased crop leaves which is categorized into 38 different classes. The total dataset is divided into an 80/20 ratio of training and validation sets preserving the directory structure. A new directory containing 33 test images is created later for prediction purposes.

**What will be your unit of analysis (for example, patient, organization, or country)?**

In this project, we are going to analyze the crop that is suitable for a particular location based on input details. The unit of analysis here is the yield of a particular country and my unit of observation is crop selection. And my unit of observation for the second part would be fertilizer selection.

**What variables/measures do you plan to use in your analysis (variables should be tied to the questions in #3)?**

We will be using state, district, crop, area, and temperature in our analysis.

**What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?**

In this project, we are planning to use machine learning approaches like Random Forest and Decision Tree to predict the crop based on soil type. We are also planning to use neural network techniques, such as Back Propagation and Principal Component Analysis, to identify the fungi disease (PCA). Before cultivation, the crops were ranked using Decision Tree Learning. An Artificial Neural Network will be implemented to predict crop disease and recommend measures to treat the crop organically. The random forest algorithm would be implemented to analyze crop features. Finally, we are planning on deploying our project in an AWS EC2 instance. We are also using image processing techniques.
 ![image](https://user-images.githubusercontent.com/78180757/173258426-c6f6f81c-f06e-4b0a-8832-1b1046492440.png)


**How do you plan to develop/apply ML and how do you evaluate/compare the performance of the models?**

![image](https://user-images.githubusercontent.com/78180757/173258273-cbcdfe8d-b965-4d58-bc4b-e7ba29e901de.png)
 
**What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practical applications, etc)?**

The fundamental goal of this project is to investigate and analyze different techniques for detecting plant leaf disease using image processing techniques and propose improvements in existing classification techniques for plant leaf disease detection using machine learning. The proposed system assists farmers in selecting the appropriate crop by delivering information that regular farmers are unaware of, reducing crop failure and improving output. It also helps them avoid losing money.
Despite the many solutions that have recently been suggested, there are still open challenges in developing a user-friendly crop recommendation application. The proposed solution aims to address these limitations by creating a user-friendly application that considers rainfall, temperature, soil type, and other factors that directly affect cultivation. The main goal is to increase the number of crops grown throughout the season.

