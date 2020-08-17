# Shopee Code League - Sentiment Analysis

## Background
At Shopee, we always strive to ensure the customer’s highest satisfaction. Whatever product is sold on Shopee, we ensure the best user experience starting from product searching to product delivery, including product packaging, and product quality. Once a product is delivered, we always encourage our customer to rate the product and write their overall experience on the product landing page.

The rating and comments provided for a product by our buyers are most important to us. These product reviews help us to understand our customers needs and quickly adapt our services to provide a much better experience for our customers for the next order. The user's comments for a product ranges from aspects including delivery services, product packaging, product quality, product specifications, payment method, etc. Therefore it is important for us to build an accurate system to understand these reviews which has a great impact on overall Shopee’s user experience. This system is termed: "Shopee Product Review Sentiment Analyser".

## Task
In this competition, a multiple product review sentiment classification model needs to be built. There are ~150k product reviews from different categories, including electronics, furniture, home & living products like air-conditioner and fashion products like T-shirts, rings, etc. For data security purposes, the review ids will be desensitized. The evaluation metrics is top-1 accuracy.

## Sample Dataset
|review_id|review|rating|
|:---|:---|:---|
|11576|It's working properly. Very quick heating capability. Good product with this price thanks|5|
|10293|Excellent service by the staff, helpful and polite. Great experience overall.|5|
|01820|The delivery was fast but the packaging was not that good, the price is reasonable, overall the product is ok.,|4|
|32090|Package not that well|2|
|....|....|....|

## Evaluation Metric
Categorization Accuracy

## Results
|Public Leaderboard|Private Leaderboard|
|:---|:---|
|0.61322|0.61950|

## Reference
**Jupyter Notebook**
<br>
https://github.com/shermanpch/shopee-sentiment-analysis/blob/master/shopee-sentiment-analysis.ipynb

**Shopee Code League - Sentiment Analysis**
<br>
https://www.kaggle.com/c/shopee-sentiment-analysis
