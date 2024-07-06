# Starry Sticker Shop Analysis ✨
This is an analysis of the online shop data from my small business, Starry Sticker Shop.

## Data
I downloaded sales and customer review data from 2020 to 2023 from my Etsy shop. There are a total of 266 rows representing 266 sales. I merged and cleaned the DataFrames as necessary. The columns I utilized in my analysis are: `Sale Date`, `Quantity`, `Item Total`, `Date Shipped`, `Ship State`, `Ship Country`, `Processing Time`, `Rating`, `Review`, `Review Category`, `Sentiment`, and `Sentiment Category`.

**Descriptions of Columns**
- `Sale Date`: the date the order was placed
- `Quantity`: the number of items in the order
- `Item Total`: the total price of the sale
- `Date Shipped`: the date the order was shipped out
- `Ship State`: the U.S. state the order was shipped to, if applicable
- `Ship Country`: the country the order was shipped to
- `Processing Time`: the number of days between when the order was placed and when it was shipped out
- `Rating`: the rating the order was given, on a scale of 0 - 5, if applicable
- `Review`: the written review for the order, if applicable
- `Review Category`: the topic a review was about, either Product, Service, or Shipping, if applicable
- `Sentiment`: the sentiment score of the review as determined by TextBlob, if applicable
- `Sentiment Category`: Positive if a sentiment score is >= 0.3, Negative if a sentiment score is < -0.3, and Neutral otherwise, if applicable

## Sales Trend Analysis
With the goal of understanding sales patterns and identify trends, I compared sales performance year-over-year and month-over-month.
![image](https://github.com/sarahhe05/Starry-Sticker-Shop-Analysis/assets/142868875/98ead4f0-acc1-4217-91fe-915c65e1b6c3)

## Product Performance Analysis
To assess the performance of individual products, I considered the amount of sales each item has as well as their ratings.
![image](https://github.com/sarahhe05/Starry-Sticker-Shop-Analysis/assets/142868875/15913e97-4f10-44dd-bd02-268dec2be7c7)
![image](https://github.com/sarahhe05/Starry-Sticker-Shop-Analysis/assets/142868875/7027f563-214d-459b-a8d1-756002cbcbed)

## Customer Feedback Analysis
Understanding customer sentiment is important in identifying areas of improvement. After identifying common themes in customer reviews, I found that 
- for reviews regarding Product: 90% are Positive, 10% are Neutral, and 0% are Negative
- for reviews regarding Service: 75% are Positive, 0% are Neutral, and 25% are Negative
- for reviews regarding Shipping: 67% are Positive, 33% are Neutral, and 0% are Negative

I also mapped out the regions that sales are from and noticed that 257 of all 266 sales are from the United States, distrubuted as shown below
![image](https://github.com/sarahhe05/Starry-Sticker-Shop-Analysis/assets/142868875/761b9841-e2c2-444b-b2ab-bbb1f0fd838e)

## [Visualization](https://public.tableau.com/app/profile/sarah.he8574/viz/StarryStickerShopAnalysis/StarryStickerShopSalesAnalysis)
I made the final visualization using Tableau to create a concise summary of Starry Sticker Shop's performance over the four year period.
![Starry Sticker Shop Sales Analysis](https://github.com/sarahhe05/Starry-Sticker-Shop-Analysis/assets/142868875/1c433005-2fe7-4b5c-ae1b-dd40cefdb35c)
