# Whiskey_Auction

### Project Overview
The dataset in  this project is sourced from free open Whiskey Auction API by Mixed Analytics. This project leverages Power BI to analyse and visualize data from lists of whiskey auctions. The objective is to provide insights into pricing trends, popular brands, and auction dynamics, helping enthusiasts and investors make informed decisions.

### Data Source
Whiskey_Auction: The primary dataset used in this project is an API with a JSON format file(https://whiskyhunter.net/api/auctions_data/?format=json). Contains detailed information about Whiskey Auction Bid throughout the years starting in 2005.

### Tools 
Python: The programming language
Microsoft Power BI: For data transformation, cleaning, preparing data for analysis, and creating interactive and visually appealing charts for making a report.

### Cleaning and Preparing data

Initially, I transferred the API link of the JSON file to Microsoft Power BI. Then transformed the data by: 
- Renaming the table name and Columns neatly
- Removing any unnecessary column 
- checking the data type for each column
- Handling missing values like Null, None, or Empty  values. If there is either remove or use techniques to fill the empty value. For example, by using backfill or forward-fill.
 I was satisfied with the auction data, so I decided to close and apply my data from the power query editor to modelling and visualisation to carry out the analysis.

### Exploratory Analysis(EDA)
- What is the total Whiskey Auction Bid?
- What are the top 5 Whiskey Auction?
- 
### Data Analysis
I have used a line and stacked column chart for my data visualisation
The chart has a title: “Sum of winning bid mean, Max and Min by Auction name”

- Configuring the Axis:
  - The auction_name field is dragged to the X-axis to display the names of different auction houses.
  - The fields Sum of winning_bid_max, Sum of winning_bid_mean, and Sum of winning_bid_min are dragged to the Y-axis to represent the corresponding values.
- Each bar in the chart represents one auction name.
- Each bar indicates the sum of the maximum, mean, and minimum winning bids respectively.
- The height of the bars indicates the total value of these sums, giving a comparative view of 
  auction performance.

*The sum of the maximum winning bid for each Acution is represented by a light Blue colour.*
*The sum of the mean winning bid for each auction is represented by dark blue light.*
*The sum of the minimum winning bid for each auction is represented by orange.*


[The fields Sum of winning_bid_Max, Mean, and Min.pdf](https://github.com/user-attachments/files/16321066/The.fields.Sum.of.winning_bid_Max.Mean.and.Min.pdf)





### Results/Findings
- Sotheby's Whisky Auctions stands out significantly, with the highest sums for maximum, mean, 
  and minimum winning bids. This indicates that Sotheby's consistently attracts higher bids 
  across all metrics compared to other auction names or houses.
- Whiskey Auktion Berlin, eBay Whiskey Auction, and European Whiskey Auctions are among the 
  lowest auction Houses Winning Bids. This indicates that they have fewer high-value Bids.
- The consistent pattern of the bars indicates a distribution where the sums of maximum bids are generally higher than the mean and minimum bids. 

  **Note:** This signifies maximum bids usually represent the highest single bid in an auction.

**Conclusion:**
This line and stacked column chart which is similar to the bar chart provides a comprehensive overview of the performance of various auction names or houses in terms of the maximum, mean, and minimum winning bids.

It allows for easy comparison and analysis of which auction names or houses are achieving the highest bids and how their performance varies across different metrics.


### Recommendation
Sorting and Ordering:
Consider grouping auction houses into categories (e.g., top tier, mid-range, lower tier) based on their total sums of winning bids for more structured comparisons.


### Limitation

### Reference
https://mixedanalytics.com/blog/list-actually-free-open-no-auth-needed-apis/






