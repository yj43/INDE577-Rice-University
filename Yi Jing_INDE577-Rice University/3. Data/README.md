## Introduction
Online auctions for trading goods and services provide a convenient environment for malicious money-makers to conduct different types of fraudulent activities such as Shill Bidding (SB). This type of fraud is difficult to detect due to its similarity to normal bidding behavior.
The set of SB data we use is obtained through eBay auctions of a large number of popular products, which contains various behavioral data of auctioneers, such as Bidder Tendency, Bidder Ratio, Last Bidding, etc. And, two response variables are provided, one is class, which marks whether the observation is normal behavior bidding. The other is Winning Ratio, which marks the rate that a shill bidder competes in auctions.
In the project, various machine learning techniques were used on the data, trying to find out the features that are significant for fraud bidding recognition, make accurate predictions for future bidding, to achieve the purpose of anti-fraud.

The dataset contains 6321 instances and 13 attributes. Detailed infomation of them is shown as follows.

## Attribute Information
Record ID: Unique identifier of a record in the dataset.
Auction ID: Unique identifier of an auction.
Bidder ID: Unique identifier of a bidder.
Bidder Tendency: A shill bidder participates exclusively in auctions of few sellers rather than a diversified lot. This is a collusive act involving the fraudulent seller and an accomplice.
Bidding Ratio: A shill bidder participates more frequently to raise the auction price and attract higher bids from legitimate participants.
Successive Outbidding: A shill bidder successively outbids himself even though he is the current winner to increase the price gradually with small consecutive increments.
Last Bidding: A shill bidder becomes inactive at the last stage of the auction (more than 90\% of the auction duration) to avoid winning the auction.
Auction Bids: Auctions with SB activities tend to have a much higher number of bids than the average of bids in concurrent auctions.
Auction Starting Price: a shill bidder usually offers a small starting price to attract legitimate bidders into the auction.
Early Bidding: A shill bidder tends to bid pretty early in the auction (less than 25\% of the auction duration) to get the attention of auction users.
Winning Ratio: A shill bidder competes in many auctions but hardly wins any auctions.
Auction Duration: How long an auction lasted.
Class: 0 for normal behaviour bidding; 1 for otherwise.

## Reference
Alzahrani A, Sadaoui S. Scraping and preprocessing commercial auction data for fraud classification. arXiv preprint [Web Link]. 2018 Jun 2.
Alzahrani A, Sadaoui S. Clustering and labeling auction fraud data. InData Management, Analytics and Innovation 2020 (pp. 269-283). Springer, Singapore.