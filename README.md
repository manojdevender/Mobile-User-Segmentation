# Mobile-User-Segmentation
case study on unsupervised learning

Domain

Mobile

Business Context

A key challenge for Mobile App businesses is to analyze the trend in the market to
increase their sales/usage.
We have access to the user's demographic characteristics, geolocation, and mobile
device properties. This grouping can be done by applying different criteria like user’s
data, their age group, phone brand compatibility and so on.
The machine learning clustering algorithms can provide an analytical method to cluster
user segments with similar interests/habits.This will help App/mobile providers better
understand and interact with their subscribers.

Objective

We will be clustering the users into groups by selected features that significantly
distinguish different brands from each other and understand which factors are
responsible for making the clusters

Dataset description

events.csv - Event data has an event id, location detail (lat/long), and timestamp,
when the user is using an app on his device

gender_age.csv - details of users age & gender

phone_device.csv - Device ids, brand, and models name. here the brands names are
in Chinese, you can convert it in english using google for better understanding but we
will not do it here.

Further study
1. Try KPrototypes algorithm to cluster the data
a. https://medium.com/@guruprasad0o_o0/notes-on-k-prototype-for-clusterin
g-mixed-typed-data-e80eb526b226
b. https://medium.com/datadriveninvestor/k-prototype-in-clustering-mixed-attri
butes-e6907db91914
2. Try kmodes library to cluster the data
a. https://pypi.org/project/kmodes/
Proprietary content. © Great Learning. All Rights Reserved. Unauthorized use or distribution prohibited. 3
b. https://medium.com/@davidmasse8/unsupervised-learning-for-categoricaldata-dd7e497033ae

#PCA
#k-means clustering
#Scaling
#Silhouette Coefficient
