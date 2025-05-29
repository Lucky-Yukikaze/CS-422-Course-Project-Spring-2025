### Data Analysis and Mining of Tiktok Users' Browsing Behavior

**Author** Wencan Wu CWID:A20567176

#### The trained model has a large volume and cannot be uploaded to GitHub. Please check the compressed file submitted in attempt 2, thank you.Some data visualization images cannot be displayed properly when viewing ipynb files online on GitHub, but they can be displayed normally after downloading them.

#### Abstract

This project visualizes and analyzes the browsing data of Tiktok in a period of time from the perspective of users, authors and works. Based on data analysis, cluster analysis is conducted on users and authors to train a binary classification model for predicting likes in browsing behavior.

#### Background Introduction

Tiktok users' browsing video behavior records, including who and whose works they saw, as well as relevant information (user city, etc.), and behavior description information (like or not).

Browsing behavior involves different activity subjects, such as users, authors, works, etc. By synthesizing browsing data and developing different characteristics for different subjects to describe their characteristics,using data analysis methods to statistically analyze browsing behavior data, obtain characteristics of different subjects, and conduct data analysis and mining on the characteristics of different subjects to serve business optimization, etc.

#### Rationale

In the context of data mining, data analysis and mining of Tiktok users' browsing behavior is of great significance. Data analysis and mining of Tiktok users' browsing behavior can understand users' interests and preferences, optimize user experience, improve the quality and attractiveness of content, and at the same time provide more accurate targeted delivery services for advertisers to achieve data-driven operational decisions.

#### Research Question

By comprehensively browsing data and developing different features for different subjects to describe their characteristics,
Using data analysis methods to statistically analyze browsing behavior data, obtain characteristics of different subjects, and conduct data analysis and mining on the characteristics of different subjects to serve business optimization, etc

#### Data Sources

Data set introduction: the data set published by the community, including more than 1.7 million Tiktok users' browsing behavior in 2019.

#### Table of Contents and Ideas

1.Feature Construction and Analysis
Based on data fields in browsing behaviors, we established descriptive metrics for users, authors, and creative works, along with classified statistical results.
    1.1 Feature Metric Construction

2.Data Analysis
Visualized analytical exploration of characteristics for different entities using statistical metric data.
    2.1 User Data Visualization Analysis
    2.2 Author Data Visualization Analysis
    2.3 Creative Work Data Visualization Analysis

Data Mining
Implemented advanced machine learning algorithms to explore data value based on previous analyses.
    3.1 User-Author Clustering Analysis (K-means Clustering Exploration)
    3.2 Association Rules
    3.3 Like Prediction in Browsing Behaviors (Binary Classification Prediction)

#### Method Summary

Data Analysis and Mining Project Based on Python Language.

-Pandas data grouping statistics
-Pyecharts Data Visualization
-K-means algorithm clustering, including evaluation indicators and k-value selection, etc
-Comparative selection and optimization of binary classification models

#### Results

Based on statistical indicator data, visual data analysis of the characteristics of different subjects (users, authors, works) has been completed.

Then, based on data analysis, machine learning algorithms are used to mine the data. Completed user author clustering analysis (Kmeans clustering exploration) and like prediction in browsing behavior (binary classification prediction).The prediction accuracy of this optimized model is as high as 99%. but the AUC value of the model is low.

#### Next steps

The platform's user base has been steadily growing, but analyzing monthly activity based on only two months of data is still not accurate enough. More data support is needed.
Improve the binary classification model.

#### Conclusion

Cluster models can be applied to determine user value, such as the first type of users who have relatively low views, likes, and completion rates. These users tend to pay more attention to the first half of the video content, and their interests can be judged by their dwell time. However, their usage time is relatively long, reflecting product dependence, and to some extent, they are considered core users. You can use dwell time to determine preferences and optimize recommendation algorithms.

This model can also be applied to improve the author's creative efficiency. The results show that authors with high views, high likes, and high views usually use more music, publish more works, and visit more cities than other authors, indicating that authors need to accumulate a lot of creative experience and rich experience to create more popular videos.

By liking, we can determine users' preferences and evaluate the quality of their works. The binary classification model used to predict whether users will like can be applied to provide self media companies with a means of content optimization and advertising placement. The prediction accuracy of this optimized model is as high as 99%.However, the AUC value of the model is relatively low and further improvement is needed.

### Bibliography 

Tan, Pang-Ning, Michael Steinbach, Anuj Karpatne, and Vipin Kumar. 2019. Introduction to Data Mining. 2nd ed. Beijing: China Machine Press.
