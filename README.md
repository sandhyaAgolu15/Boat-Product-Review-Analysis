# Boat-Product-Review-Analysis
Understanding customer demands and preferences is crucial for companies to stay ahead of the competition.  This project aims to conduct a sentiment analysis of customer reviews of Boat products and their competitors, with the goal of gaining insights into consumer perceptions and preferences. 

## Data Collection:
We have utilized a dataset that was compiled from information about Boat products, which was sourced from https://www.boat-lifestyle.com/. Additionally, the dataset also includes data from other sources that provide information on rival companies' product reviews. The dataset includes various variables such as ProductName, Price, Discount, Number of Reviews, Rating, Review, and Summary.

## Data Cleaning:
1. Cleaned data of Rate, Price, Discount and No of reviews columns.
2. Renamed column names.
3. Removed null values.
4. Dropped duplicate columns. 

## Text Processing: 
1. Tokenization

   
<img width="216" alt="image" src="https://github.com/sandhyaAgolu15/Boat-Product-Review-Analysis/assets/46163528/5d1ee00c-53f2-4e39-b25a-ded3514771bf">



2. Stop Words Removal


<img width="214" alt="image" src="https://github.com/sandhyaAgolu15/Boat-Product-Review-Analysis/assets/46163528/dbd08a43-9e6f-48d2-b068-681e67f66fd4">




3. Lemmatization with POS Tagging

   
<img width="201" alt="image" src="https://github.com/sandhyaAgolu15/Boat-Product-Review-Analysis/assets/46163528/90bbb2b1-8b25-46af-842d-fde752cb2a97">




## Sentiment Analysis:
1. Using TextBlob to get Polarity


<img width="285" alt="image" src="https://github.com/sandhyaAgolu15/Boat-Product-Review-Analysis/assets/46163528/8800e915-f2fb-4dcb-843b-629aaf678bab">



2. Analysing Polarity to conclude Sentiment



<img width="219" alt="image" src="https://github.com/sandhyaAgolu15/Boat-Product-Review-Analysis/assets/46163528/f515dcba-5d47-4ef8-bc06-0630d0dc40fc">





## Classification of Reviews - Data Modeling:


Building a Classification model to classify reviews into Positive, Negative or Neutral Sentiment
1. Converting text data into vectors using TF-IDF
2. Splitting data into Train and Test
3. Fitting the model and model evaluation

## Classification of Reviews - Results

1. Naive Bayes:


<img width="317" alt="image" src="https://github.com/sandhyaAgolu15/Boat-Product-Review-Analysis/assets/46163528/b73b079c-848e-48f1-b5a8-4a333d8acac9">




2. Logistic Regression:


<img width="320" alt="image" src="https://github.com/sandhyaAgolu15/Boat-Product-Review-Analysis/assets/46163528/e273bcc2-75c9-4c82-be24-1af10aee5b5c">




## Finding the Best Classification Model


<img width="267" alt="image" src="https://github.com/sandhyaAgolu15/Boat-Product-Review-Analysis/assets/46163528/0d86829a-25c1-4e13-825c-25def3ad9bbc">




## Product Segmentation - Results:



<img width="432" alt="image" src="https://github.com/sandhyaAgolu15/Boat-Product-Review-Analysis/assets/46163528/79b63232-a62e-4be0-a61c-aafc37b62d01">




Hence we can observe from the Clusterization plot and conclude that the products with low prices have a higher chance of making Positive impact on the Market.

## Conclusion:
The sentiment analysis model can help the company identify customer sentiment quickly and effectively, enabling it to respond to feedback and improve customer satisfaction.
The product segmentation model can provide the company with insights into the preferences of different customer groups, helping it to tailor its marketing strategies and develop new products.
This analysis can contribute to improving the company's brand image and reputation by identifying areas for improvement in its products and services.


















