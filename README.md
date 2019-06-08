# Predict-the-Segment-Hotstar

Hackathon project

Predict the Segment - Hotstar
- Determining the demographics of customers is one of the most key tasks in the
advertising domain. Advertisers usually want to target customers based on demographic attributes. However, it is difficult to get demographic data from all the customers since that can add friction to the user experience. - At Hotstar, we have detailed information on all the content that customers watch, let’s call it “watch patterns” and we’d like to use this signal to fine tune demo-targeting. - We are seeking a machine learning based solution using which we can learn patterns
from customers whose watch patterns are already known. In this competition, the task is to generate predictive models that can best capture the behavior. Participants are free to use any open source external data.


Data Set Information :
A zipped file containing train, test and sample submission files are given. The training dataset consists of data corresponding to 200,000 customers and the test dataset consists of 100,000 customers. Both training and test data is in the form of json dict, where key is masked user ID and value is an aggregation of all records corresponding to the user as described below.
Description ID: a unique identifier titles: titles of the shows watched by the user and watch_time on different titles in the format “title:watch_time” separated by comma, e.g. “JOLLY LLB:23, Ishqbaaz:40”. watch_time is in seconds genres: same format as titles cities: same format as titles tod: total watch time of the user spreaded across different time of days (24 hours format) in the format “time_of_day:watch_time” separated by comma, e.g. “1:454, “17”:5444”. dow: total watch time of the user spreaded across different days of week (7 days format) in the format “day_of_week:watch_time” separated by comma, e.g. “1:454, “6”:5444” segment target variable. consider them as interest segments. For modeling, encode pos = 1, neg = 0

Helpful techniques
- Try different clustering techniques to segment users and use those outputs as features
to your machine learning models. - Data cleaning and feature creation should be novel. Go with your intuition.

