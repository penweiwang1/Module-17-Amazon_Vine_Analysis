# Module-17-Amazon_Vine_Analysis
## Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis is to able to read, extract, and transform Big Data using Pyspark via cloud services, such as Google Colab.

This project analyzes the Amazon Vine program to determine if the product reviews of Vine members are biased compared to that of Non-vine members.

## Results: 
### How many Vine reviews and non-Vine reviews were there?

A total of 46 Vine reviews
<img width="432" alt="Screen Shot 2023-02-12 at 8 55 38 PM" src="https://user-images.githubusercontent.com/115126898/218356726-8e40c488-ad07-4045-9120-a092aed4bf49.png"> 

A total of 7320 Non-vine reviews
<img width="432" alt="Screen Shot 2023-02-12 at 8 56 53 PM" src="https://user-images.githubusercontent.com/115126898/218356727-79cd5885-f83e-44ad-a338-ffe3f744819a.png"> 

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There were 14 5-star vine reviews
<img width="814" alt="Screen Shot 2023-02-12 at 8 58 01 PM" src="https://user-images.githubusercontent.com/115126898/218357131-ba0cf25a-09a5-42d3-ba17-58d9009002b3.png">

There were 3561 5-star Non-vine reviews
<img width="894" alt="Screen Shot 2023-02-12 at 8 58 32 PM" src="https://user-images.githubusercontent.com/115126898/218357133-3707fcf5-1599-48bc-a62d-28ae13db3a46.png">

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
30% of Vine reviews were 5 stars
<img width="552" alt="Screen Shot 2023-02-12 at 8 59 50 PM" src="https://user-images.githubusercontent.com/115126898/218357573-b31ba015-d15f-4e1d-a329-1e09ee4c8da7.png">

50% of non-Vine reviews were 5 stars
<img width="609" alt="Screen Shot 2023-02-12 at 9 00 05 PM" src="https://user-images.githubusercontent.com/115126898/218357574-e1f3a298-9399-47d5-8622-693da0f92331.png">

## Summary: 
Based on the percentage of 5-star reviews, there does not seem to have a positivity bias for the Vine program reviews as it has 20% less 5-stars reviews than that of Non-vine reviews.

However, since this is just a small sample of the reviews, such that there were only  a total of 46 vine reviews, addtitional analysis could be performed on a larger group to improve accuracy and determination of the bias

