# Amazon_Vine_Analysis

## Overview:
### Purpose:

Analyze Amazon reviews written by members of the paid Amazon Vine Program to determine if there is any bias toward favorable reviews from Vine Members in the chosen dataset.

### Resources:

Software: Amazon Web Services (AWS),pgAdmin 4, Google Colaboratory (Colab) Notebook and PySpark 3.0.3

Dataset: [Toys Review Dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Toys_v1_00.tsv.gz)

### Results:
- How many Vine reviews and non-Vine reviews were there?
    - Vine Reviews: 1,266
    - Non - Vine Reviews:62,028

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    - 5 Star Vine Reviews: 432
    - 5 Star Non - Vine Reviews:29,982
 
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    - Percentage 5 Star Vine Reviews: 34%
    - Percentage 5 Star Non - Vine Reviews: 48%
  
 ### Summary:

There were 1,266 Vine reviews with 432 of those being 5 star reviews which is 34% of 5 star reviews.I The amount of 5 star Vine reviews (432) is significantly lower then the 5 star non-Vine reviews (29,982).I therefore conclude that there is no positivity bias for reviews in the Vine Program based on these results.

We could do some statistical testing to further look into other factors to see if there is any further indication of positivity bias. We could broadern our positivity bias parameters and also look at what the total number and percentage of Vine 4 star reviews vs. Non-Vine 4 star reviews are. 

