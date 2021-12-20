## Amazon_Vine_Analysis

## Overview: 
Using an Amazon dataset, this project used Google Colab, PySark, PgAdmin, and an AWS RDS instance to Extract, Transfer, and Load.  This project analyzed Amazon reviews written by members of the paid Amazon Vine program.  The intent was to determine if there was any bias toward favorable reviews from Vine members in the dataset.

## Results:
- How many Vine reviews and non-Vine reviews were there?

![total_paid_reviews](https://github.com/doloresbryant83/Amazon_Vine_Analysis/blob/main/total_paid_reviews.png)

![total_unpaid_reviews](https://github.com/doloresbryant83/Amazon_Vine_Analysis/blob/main/unpaid_5_star_review.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![paid_5_star_review](https://github.com/doloresbryant83/Amazon_Vine_Analysis/blob/main/paid_5_star_review.png)

![unpaid_5_star_review](https://github.com/doloresbryant83/Amazon_Vine_Analysis/blob/main/unpaid_5_star_review.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![paid_5_star_percentage](https://github.com/doloresbryant83/Amazon_Vine_Analysis/blob/main/paid_5_star_percentage.png)

![unpaid_5_star_percentage](https://github.com/doloresbryant83/Amazon_Vine_Analysis/blob/main/unpaid_5_star_percentage.png)


## Summary
32% of the 5-star reviews were paid in comparison to 55% of the 5-star reviews were unpaid.  Further, of the 61 paid reviews, 20 of them were 5-star reviews.  It is my assessment that there is no unfavorable bias between paid and unpaid reviews. 
