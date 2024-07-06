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

## [Visualization](https://public.tableau.com/app/profile/sarah.he8574/viz/StarryStickerShopAnalysis/StarryStickerShopSalesAnalysis)
