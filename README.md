# Twitter-Sentiment-Analysis-informal

This is a repository containing all the resources i.e data, notebooks etc., of our minor project. List of team members include:
1. [Vansh](https://github.com/vansh45)
2. [Anamika](https://github.com/ANAMIKA1410)
3. [Utkarsh](https://github.com/utquarsh027)
4. [Gargi](https://github.com/gargi-09)




# Twitter Sentiment Analysis


### ABSTRACT:- 
With the evolving behavior of different types of social networking sites like Instagram, twitter, snapchat etc , the data posted by people i.e the users of a particular social site is increasing drastically . So much so that almost millions and billions of data may be textual, video or audio is posted per day. This is because there are millions of users of a particular site. These users intend to share their thoughts, views related to any topic of their choosing. Some of these users even post in vain. These posts are short hence only meant to express a particular view of a particular user regarding a particular thing. In this paper we aim to derive the feelings behind these posts. For this we have chosen twitter as a social networking site. The posts in this social networking site are known as tweets. In this paper we scrutinize methods of preprocessing and extraction of twitter data using python and then train as well as test this data against a classifier in order to derive the sentiments behind tweets. 


### INTRODUCTION 
According to millions of people are using social network sites to express their emotions, opinions and disclose about their daily lives. However, people write anything such as social activities or any comment on products. Through the online communities provide an interactive forum where consumers inform and influence others. Moreover, social media provides an opportunity for businesses to give a platform to connect with their customers such as social media to advertise or speak directly to customers for connecting with the customer's perspective of products and services.
Sentiment analysis (SA)tells users whether the information about the product is satisfactory or not before they buy it. Marketers and firms use this analysis data to understand about their products or services in such a way that it can be offered as per the user‟s requirements.
Textual Information retrieval techniques mainly focus on processing, searching or analyzing the factual data present. Facts have an objective component but there are some other textual contents which express subjective characteristics. These contents are mainly opinions, sentiments, appraisals, attitudes, and emotions, which form the core of Sentiment Analysis (SA). It offers many challenging opportunities to develop new applications, mainly due to the huge growth of available information on online sources like blogs and social networks. For example, recommendations of items proposed by a recommendation system can be predicted by taking into account considerations such as positive or negative opinions about those items by making use of SA.

### PROBLEM STATEMENT: 
Despite the availability of software to extract data regarding a person’s sentiment on a specific product or service,organizations and other data workers still face issues regarding the data extraction
Sentiment Analysis of Web Based Applications Focus on Single Tweet Only
Difficulty of Sentiment Analysis with inappropriate english




### METHODOLOGY:
This project has been divided into 2 phases. First, literature study is conducted, followed by system development. Literature study involves conducting studies on various sentiment analysis techniques and methods that are currently in use. In phase 2, application requirements and functionalities are defined prior to its development. Also, architecture and interface design of  the program and how it will interact are also identified. In developing the Twitter Sentiment Analysis application,  several tools are utilized, such as Python Shell 3.9 and Notepad.


The proposed method for sentiment analysis in this paper could be represented in 5 stages, each of which are listed below:
A. Data Collection 
B. Data Preprocessing 
C. Feature Selection 
D. Model Selection E. Model Evaluation



##### Data collection 
Data collection is the first phase for analysis as there needs to be data for us to do analysis on. In our experimentations we have used the python programming language as a tool. Being that said, data collection in this particular analysis could be carried out in two ways. First way is to collect preorganized data from different sites such as kaggle and from github from dataset of other projects.


##### Data Preprocessing 
The pre-processing of data implies the processing of raw data into a more convenient format which could be fed to a classifier in order to better the accuracy of the classifier. Here, in our case the raw data which is being extracted from twitter using csv files from github is initially totally unstructured and bogus as the availability of various useless characters seems very common in it. 


##### Feature Selection
The preprocessed dataset has many distinctive properties. In the feature extraction method, we extract the aspects from the processed dataset. Later this aspect are used to compute the positive and negative polarity in a sentence which is useful for determining the opinion of the individuals .
Some examples features that have been reported in literature are:
Opinion Words And Phrases
Position Of Terms
Words And Their Frequencies:
Syntax


##### Model Selection 
Once the data is being pre-processed, this data is to be fed to a classification model for further processing. There are different classification algorithms on which these models are built on. 
KNN or k-Nearest Neighbour algorithm represents a machine learning technique used for classifying a set of data into its given target values (in our case positive , neutral or negative).KNN could also be used for regression problems but is widely used for classification problems.


##### Model Evaluation
By applying  technique we can derive the generalized evaluation parameters. These parameters include:  
Accuracy
Precision
Recall


### RESULTS AND DISCUSSION 
We used the twitter dataset publicly  labeled datasets using various feature extraction techniques. We used the framework where the preprocessor is applied to the raw sentences which make it more appropriate to understand. Further, the different machine learning techniques train the dataset with feature vectors and then the semantic analysis offers a large set of synonyms and similarity which provides the polarity of the content.As a result, program will be categorized sentiment into positive and negative, which is represented in a pie chart and
html page Although, the program has been planned to be developed as a web application.. Therefore, further enhancement of this element is recommended in future study.


### REFERENCES:
https://ijisrt.com/wp-content/uploads/2019/02/IJISRT19FB242.pdf
https://arxiv.org/ftp/arxiv/papers/1601/1601.06971.pdf
https://www.researchgate.net/publication/301408174_Twitter_sentiment_analysis







