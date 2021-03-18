# kmeans-mall-customers

This repository consist on the exploratory analyses using the kmeans algorithm of a fictional dataframe on keegle of the cusomers of a mall.

There are 200 customers and their anual income(k$), spendding score (1-100), Age and Gender, in this code I use the kmeans to separate 5 profiles of customers.

Pandas_profiling is used to generate a detailed report to the complete DataFrame and a individual report for every group.

The last part calculate some information and create a dict for every group, showing the mean of the relation of anual income x spending score, the mean age of the group and if it's majoritary male or female.

We can detect that groups 0,1 and 3 have a similar income_score_relation, and similar mean ages, so we can presume the this three groups are consistent spenders. 
Group 2 have the bigger income_score_relation, that means the this group have a big annual income but don't have a big spending score, the major difference of this group that is the only group that are majority Male.
Group 4 have the lowest income_score_relation, so it spends more than it earns, and this group is also composed with the lowest mean age, so we can assume that composed of yung peaple.

This is a small dataset, so we can't assume that the data analysed here is based on a cause and effect situation, but it can be a start to study the behavior of the customers.

This repo is just for some tests of the kmeans and every sugestion, doubt or tips are wellcome!
