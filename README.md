# Amazon_Vine_Analysis
Working with Big Data, Spark, AWS

# Overview of the analysis of the Vine program:
The Amazon Vine program is a program where Amazon will reward someone who writes a review for a product. For this analysis, I chose the kitchen product category and using the dataset, I wanted to determine if there was any kind of bias from the participants of this program. This is determined by checking to see if there is a correlation between a positive and paid reviews.

# Results
* How many Vine reviews and non-Vine reviews were there?
![paid_total](https://github.com/julianneitliong/Amazon_Vine_Analyis/blob/ac098144f69aa5793ca9511f0a275119bde0b7a5/paid_total.png)
![unpaid_total](https://github.com/julianneitliong/Amazon_Vine_Analyis/blob/85abe287ef9b1c1281e45d88e82ac2e55d46a957/unpaid_total.png)

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
![paid_reviews](https://github.com/julianneitliong/Amazon_Vine_Analyis/blob/2646f339b2ca2741d128146264d112c0b0bdc67b/paid_reviews.png)
![unpaid_reviews](https://github.com/julianneitliong/Amazon_Vine_Analyis/blob/397284db07b2da02467cd07b07883037ca471117/unpaid_reviews.png)

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![vine_percent](https://github.com/julianneitliong/Amazon_Vine_Analyis/blob/3efef1b23bcbbdbb09443a048928911c777303d1/vine_percent.png)
![unpaid_percent](https://github.com/julianneitliong/Amazon_Vine_Analyis/blob/259d45a303efb49c04d69a819ad15b1e1b44eca3/unpaid_percent.png)

# Summary of Results
Looking at the results of this analysis, there is a much larger amount of unpaid total number of reviews (97,839) versus number of paid reviews (1207) found in the top 20 helpful reviews cateogry. This difference shows that most of the dataset includes unpaid reviews, showing that the vine program may not be incentivizing customers to review their products.

Looking at the number of paid 5-star reviews (509) versus the number of unpaid 5-star reviews (45858), there is large difference between the two, showing that there is likely no bias when it comes to customers being incentivized to leave 5-star reviews through the vine program.

#### Additional analysis
To further this analysis, I would use Natural Language Processesing to analyze the review_body column to understand what customers saying in the text of their reviews. I would perform a sentiment analysis of the review_body text to properly categorize the review as postive, negative, or neutral. This may be helpful in understanding whether or not there is a bias in paid and unpaid reviews using the vine program.

