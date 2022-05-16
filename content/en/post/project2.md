---
date: 2021-08-30T10:58:08-04:00
description: "Analyzing Reviews on App TAMPIL on Google Play Store"
featured_image: "/images/SENTIMENT.png"
title: "Project 2: Sentiment Analysis Of TAMPIL'S Application"
---

* This project analyzes the reviews given by Users on the TAMPIL application on the Google Play store. The TAMPIL application is a platform for hosting webinars or community events and partners using the TAMPIL video conference service. This application is owned by PT Bisa Artificial Indonesia, which is located in Bandung, West Java, Indonesia.

* This project is my last project or Final Project as a participant in Master On Job Training at BISA AI Academy, which is carried out for 1 month. The data provided is data from the reviews of users of the TAMPIL application on the Google Play store. This data is in the form of a CSV file and has a time span from May 2020 to September 2021.

* I use Python to analyze the data above, which in the analysis process displays the properties of the data, such as data types, data dimensions, missing values and how to overcome them or handle Missing Values, and so on. In addition, I also added a new column named “Sentiment”, which contains Positive, Neutral, and Negative values. These values come from Review Text and Ratings given by Users, provided that if the Star Rating is above 4, then it is a positive one. If the Star Rating is equal to 3, then it is classified as Neutral, and also, if the Star Rating is below 3, then it is classified as negative.

* I also do Pre Processing Data or clean text data from some symbols, delete emoticons, and so on so that the data looks cleaner. After that, I display or visualize the cleaned data using WordCloud, each displaying a positive, neutral, and negative Review Text. Based on the WordCloud visualization, there are several insights that can be taken; namely, TAMPIL application users respond positively to the many events and webinars that are considered very useful for users. However, users also highlight and respond negatively to the TAMPIL application because it often exits itself or Force Closes when used.

[Link To GitHub Repository](https://github.com/kamiludin/ds_bisaai_project)

{{< figure src="/images/Sentiment_Analysis.png" >}}
