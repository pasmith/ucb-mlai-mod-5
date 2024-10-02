# Overview
This repo contains an analysis of the "In-Vehicle Coupon Recommendation" data set from the UCI Machine Learning Repository.

### Data source:
In-Vehicle Coupon Recommendation [Dataset]. (2017). UCI Machine Learning Repository. [https://doi.org/10.24432/C5GS4P](https://doi.org/10.24432/C5GS4P).

### Repository Organization:
- `data\`: this folder contains the data set that was examined
- `data\coupons.csv`: the data set
- `prompt.ipynb`: this file contains the code and analysis for this project
- `README.md`: this page summarizing the project repository and its content

## Summary of Findings

The "In-Vehicle Coupon Recommendation" data set contains data regarding drivers that accept coupons sent to their mobile device when they are near the location of the vendor issuing the coupon.

There are several categories of establishments including bars, coffee shops, and several types of restaurants ranging from fast food establishments to more expensive restaurants.

This analysis looked at the drivers that accepted bar and coffee shop restaurants.

Please refer to the jupyter notebook [prompt.ipynb](prompt.ipynb) in this repository for the detailed technical analysis.

### Bar
The average coupon acceptance rate for bar coupons is 41.2%. However, drivers that go to bars tend to accept coupons. 76.2% of drivers who go to bars more than 3 times a month, and 69.0% of drivers over the age of 25 who go to bars once a month, and 71.4% of drivers traveling with adult passengers accepted coupons.

In contrast, 58.7% of the drivers who go to bars at least once a month but who were under the age of 30, or who go to cheap restaurants more than 4 times a month and make an income less than $50k accepted coupons.

We can hypothesize that drivers that tend to go to bars and have disposable income are likely to accept bar coupons.

### Coffee Shops
Drivers who tend to go to coffee shop are very likely to accept coffee shop coupons at a rate of 65.9%, as long as the coupons are convenient. If the coupon requires the driver to go in the opposite direction, or go out of their way, right then, then the rate drops to 47.4%. In contrast, if the coupon is convenient, same direction, or next day for example, the acceptance rate is as high as 73.0%.

Other factors don't seem to influence the likelihood that a driver who tends to go to coffee shop will accept coffee shop coupons.

There does appear to be an opportunity to attract drivers that don't tend to go to coffee shops. The best strategy appears to be to send coupons that will expire the next day. Drivers traveling alone have an almost 55% likelihood of accepting a next day coupon.

## Next Steps and Recommendations

The data for both groups really suggested that customer loyalty, the tendency to go to bars and coffee shop, was a key factor in determining whether a driver was likely to accept a coupon.

In the case of coffee shop coupons, convenience was also a factor. Requiring drivers to change their travel plan seem to discourage drivers from accepting coupons. However, giving drivers coupons that expire the next day seems to increase the likelihood that the driver would accept the coupon.

It would be interesting to see if the same holds for more expensive venues like bars and expensive restaurants. Is the sensitivity to how convenient it is to redeem the coupon related to the cost and coupon value? In other words, would drivers be more likely to consider coupons that expire within a few hours and require them to go out of their way for expensive restaurants or bars?

Business should also try to understand what factors lead conclusively to drivers not accepting coupons. We saw that for coffee shops, convenience was such a factor. Are there others? What are the detracting factors for the other establishment types? This understanding would help business be more efficient in their coupon campaigns.

Lastly, establishments should try to determine what factors can help draw new customers to become regular loyal customers. In the case of coffee shops, we saw that next day coupons could be effective at drawing new customers. Can bars and restaurants do the same? Would that be effective for those establishments?
