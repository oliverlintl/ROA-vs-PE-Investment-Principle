# ROA vs PE Investment Principle

## The Magic Formula
This project adopts the investment principle covered in Joel Greenblat's book [*The Little Book that Still Beats the Market*](https://www.amazon.com/Little-Book-Still-Beats-Market/dp/0470624159/ref=pd_lpo_1?pd_rd_i=0470624159&psc=1). The overarching principle is simple. When it comes to stock picking, we should look for company that are profitable, and have relatively low share price. And to measure these two aspects. We choose two metrics: **Return on Asset (ROA)** and **Price to Earning Ratio (PE)**. <br>
### Return on Asset (ROA)
ROA not only measures a company's profitability, but if also measures how efficient a company is at turning profit using their total assets. Although there is a downside of using ROA to compare company across different industry. For example, ROA of a tech firm can be very different from that of a food company. 
### Price to Earning Ratio (PE)
We use PE to compare a company's share price to its earning per share. In our project we will use trailing PE as oppose to forward PE, as trailing PE reflect historical information and forward PE attempts to predict the future. 
### Ranking
We use ranking to normalize the metrics and compare companies. We rank ROA and PE seperatly at first. Higher the ROA, higher a company would rank in ROA ranking. And it is the opposite when it comes to PE. The company would rank high if they have a low PE. Note, company with negative PE would be set to the bottom of the ranking, because they are not profitable thus has no point being included to the PE ranking. <br> 
Finally, after ranking ROA and PE, we sum the ranking from both metrics and use it as a score for each company. A low final score means a stock is relatively profitable and under valued compared to other stocks in the comparison. 
