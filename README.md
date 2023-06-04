# consolidated_analyses_01_04

## Analyses 1
### Executive Summary
Our Exploratory Data Analysis (EDA) of NYC real estate markets, particularly Richmond Hill in Queens, revealed key trends and insights. Residential sales lead the market, accounting for $145.3 billion in Queens, with Richmond Hill standing out at $4.56 billion. Sales distribution in 2021 showed a significant upsurge during the summer months, hinting at heightened real estate activities during this period. We also observed a positive correlation between property size and sale value, with larger, high-end properties greatly influencing the average prices.
The EDA also assessed the five-year sales transaction growth rate, Compound Annual Growth Rate (CAGR), and total revenue. Positive sales transaction growth trend was noticeable from 2017-2021 across NYC, Queens, and Richmond Hill. Queens and Richmond Hill demonstrated a CAGR of 4.96% and 4.76% respectively from 2003-2021, indicating steady growth over this timeframe. Richmond Hill registered a notable total revenue of $1.7 million in 2021, ranking second in Queens borough.
Our analysis suggests that Richmond Hill is a good new real estate office location. We must examine additional factors in more detail to make an informed decision. Specifically, we should look at metrics like property age, sale price per square foot, sale price per unit, and days on the market. These data points can give us deeper insights into the local real estate market. Additionally, we should consider operational costs, potential competition, and how our strategic objectives align with company goals. While we can use growth predictions and the CAGR to guide our analysis, we should be cautious since past performance doesn't always predict future results. Considering all these factors, we can determine if Richmond Hill is the right place to establish our new real estate office.

### Problem Understanding and Definition
The objective of this project is to provide data-driven insights that will guide the strategic decision-making of a real estate brokerage firm planning to open an office in New York City. The primary question to be answered is: Which neighborhood should the firm choose for their office location to maximize opportunities and minimize risks?

### Data Cleaning and Preparation
The initial stage of our analysis involves data cleaning and preparation in Power BI. This process will help maintain data quality and accuracy for subsequent analytical procedures. The steps include:
1.	Filtering out invalid year entries in the Year_Built field.
2.	Removing properties with 0 Gross_Square_Feet, which can skew size calculations.
3.	Excluding properties with Sale_Price values below $10,000, which are likely errors.
4.	Removing rows with blank Building_Code_ID, corresponding to Building Type.
5.	Converting ID fields to text format to prevent unwanted numerical operations.

### Exploratory Data Analysis
#### Five – Number Summary
Our EDA focused on comparing residential and commercial property transactions across various neighborhoods and boroughs, emphasizing Richmond Hill in Queens. The analysis revealed that residential transactions involving smaller properties were more common across all areas. However, commercial transactions, while less frequent, had potential for larger property sizes in particular regions, such as Jamaica in Queens. (Figure 1)
Richmond Hill typically features smaller properties in terms of Gross Square Feet (GSF), translating to lower sale prices compared to neighborhoods with larger properties. Nonetheless, differences are apparent across boroughs, with Manhattan featuring significantly larger properties and higher sale prices. (Figure 2)
A clear correlation between Gross Square Feet and Sale Price emerged, pointing to the fact that larger properties command higher prices. This finding is important, as areas with higher prices could present profitable opportunities due to their direct impact on revenue potential and indication of market activity.

#### Total Sales by Property Type – Boroughs, Neighborhoods
Borough-wise, Manhattan led in total sales for commercial and residential properties, followed by Brooklyn, Queens, and the Bronx. However, in Queens, residential sales significantly exceeded commercial sales, suggesting a predominantly residential real estate market, a trend observed across other boroughs except for Manhattan.
Neighborhood-wise, Richmond Hill registered the highest total residential sales in Queens and showed significant commercial and mixed property sales, indicating a diverse real estate market. Although other neighborhoods like Forest Hills and South Jamaica also had high residential sales, their commercial and mixed property sales were lower. Jamaica stood out with high sales across all property types. (Figure 3)
Sales Distribution in 2021 – NYC, Queens, Richmond Hill
For NYC and Queens, sales transactions peaked in August and were lowest in December, revealing a seasonal pattern. (Figure 4)
However, Richmond Hill showed a more consistent sales distribution across the months. The neighborhood saw smaller peaks in June and August but maintained a steady transaction rate throughout the year. (Figure 5)

In conclusion, while NYC and Queens show a clear seasonality pattern in sales volume, Richmond Hill demonstrates less seasonality, maintaining consistent transactions throughout the year. Richmond Hill's steady sales and alignment with broader Queens and NYC market trends make it a potential candidate for a new real estate office. However, other variables, such as local market conditions, property prices, and competitive landscape, must be considered before making the final decision.

#### Sales Transaction Expected Growth Rate
NYC and Queens witnessed significant growth in transaction numbers from 2017 to 2021, despite a downturn in 2020, likely due to the pandemic. Specifically, NYC transactions increased from 27,270 to 60,537, while Queens grew from 10,623 to 17,133. (Figure 6)
Contrastingly, Richmond Hill maintained stable transaction numbers ranging between 307 and 438 during this period, despite experiencing a downturn in 2020 and a slight recovery in 2021.

In conclusion, while NYC and Queens showed substantial growth in sales transactions, Richmond Hill demonstrated resilience and stability. Hence, Richmond Hill presents potential as a suitable neighborhood for a new real estate office, given its steady performance and alignment with the Queens and NYC market trends. However, considerations of local demand, supply conditions, property prices, and market competition remain crucial factors in making a final decision. (Figure 7)

#### Compound Annual Growth Rate (CAGR)
Among all boroughs, Brooklyn exhibited the highest CAGR at 6.73%, while Manhattan showed a negative growth rate at -3.34%. The Queens borough displayed moderate growth at 4.96%. Within Queens, Jamaica had the highest neighborhood CAGR at 5.44%, while Forest Hills experienced the lowest growth at 0.82%.
Applying the CAGR to predict the expected number of transactions for 2022, Queens could have approximately 23,338 transactions, and Richmond Hill around 400.
Despite its low growth rate, Forest Hills emerged as a high-value neighborhood, indicated by the largest maximum gross square feet and a high maximum sale price among the examined Queens neighborhoods. (Figure 8)
In conclusion, Richmond Hill shows robust growth, aligning closely with the broader Queens borough growth trend, indicating it could be a suitable neighborhood for a new real estate office. However, these predictions are based on past trends and must be evaluated alongside factors like local demand, supply conditions, property prices, and market competition, as future market conditions may vary.

#### Total Revenue
This analysis examined total revenue for 2021 with revenue calculated based on a 5% commission on residential sales and 12.5% market penetration.
Borough-wise, Manhattan leads with over $268 million in revenue, attributed to its high-value real estate market. Brooklyn follows with approximately $125 million, while Queens ranks third, generating around $90 million. These numbers indicate lower property prices in Queens despite a significant number of transactions. Staten Island and the Bronx have about $25 million in comparable revenues, considerably lower than the other boroughs.
Forest Hills generates the highest revenue among Queens' neighborhoods, over $3 million, consistent with earlier analyses indicating larger, high-end properties. Richmond Hill is the second-highest revenue earner, with around $1.7 million, reflecting its strong real estate market. In contrast, Jamaica Bay has the lowest revenue of about $50k, suggesting fewer transactions, lower-priced properties, or both. (Figure 9)
Comparing these revenue figures with sales trends observed in previous analyses, higher sales volume does not necessarily translate into higher revenue, particularly in areas where property prices are lower. The revenue seems to align more closely with the property prices in the areas than with the number of transactions.
The standout point here is the significant disparity in revenue between boroughs and neighborhoods. It's interesting to see how the property prices and market activity in each borough or neighborhood directly affect the revenue generated. Such insights can be crucial for real estate companies when planning their strategies or deciding where to open new offices.


## Analysis 2
### Executive Summary
Our analysis of Richmond Hill's real estate market compared to other Queens neighborhoods and insights from the "NYC Real Estate Expansion: Analytics for Location and Specialization" report shows that opening a new real estate brokerage office in Richmond Hill is feasible and potentially profitable. Here are the key findings: 
1.	Trend Analysis: The average sale price per square foot in Richmond Hill has consistently increased over the past few decades, reaching $285.52. This trend indicates a growing and resilient real estate market. 
2.	Comparative Market Evaluation: Richmond Hill is a more affordable option than other neighborhoods in Queens, with an average sale price per square foot of $285.52 compared to Queens' average of $335.81. The market has potential to attract investors. 
3.	Market Stability: The real estate market in Richmond Hill is more stable than other Queens neighborhoods, with a lower standard deviation in prices ($72.12 versus $91.41). This stability reduces investment risks and is attractive to prospective homeowners. 
4.	Market Position: While the average sale price per square foot in Richmond Hill is lower than the Queens average, it offers an affordability advantage that could attract diverse clients. 
Richmond Hill's affordable real estate market is consistently growing and stable, making it attractive to home buyers and investors. However, it's important to remember that external factors like economic fluctuations, policy changes, or unforeseen events can impact the market's stability and growth trends. Additional analyses such as Time Series Forecasting, Spatial Analysis, Multiple Regression Analysis, Cluster Analysis, and Market Demand Analysis can help confirm Richmond Hill's potential for a new brokerage office.

### Problem Understanding and Definition
This analysis aims to examine the Average Sale Price Per Square Foot trend in Richmond Hill, compare it against other neighborhoods within the Queens borough, and evaluate the prospective profitability and viability of establishing a new real estate brokerage office in Richmond Hill. Through this analysis, we aim to uncover data-driven insights to help drive strategic decisions for expanding real estate operations.

### Data Cleaning and Preparation
The initial stage of our analysis involves data cleaning and preparation in RStudio. This process is crucial to maintain data quality and accuracy for subsequent analytical procedures. The steps include:
1.	Joining the NYC_Transaction_Data with the neighborhood and borough tables to provide a comprehensive dataset that allows for thorough comparative analysis.
2.	Creating a function that calculates the total sale price, total gross square feet, and average price per square foot for a given property type in a specific borough and, optionally, in a particular neighborhood. This function will operate for each year of sales data provided in the DataFrame. Within this function we:
a.	Implement filters to include properties where the sale price >= $10,000, and gross square feet > 300 to eliminate outlier properties that may distort the analysis.
b.	Create a new column, SALE_YEAR, by extracting the year from the SALE_DATE column using the year() function from the lubridate package. The DataFrame is then grouped by SALE_YEAR.
c.	Calculate each group's total gross square feet, total gross square feet, and average price per square foot, excluding NA values. This aggregation will provide a macro view of the property landscape within the specified parameters.
3.	Creating line plots to compare the average price per square foot for selected neighborhoods with Richmond Hill from 2003 to 2021. These visualizations will provide insights into market trends and price fluctuations over time.
4.	Developing a function that computes summary statistics, including standard deviation, for further quantitative analysis. This function will measure the dispersion or spread in property values, contributing to a fuller understanding of market volatility.
By carefully preparing our data with these steps, we ensure a sound basis for a good and accurate analysis of the NYC real estate market dynamics.

### Exploratory Data Analysis
#### Line Plots: Comparing Richmond Hill with Other Neighborhoods
1.	The general trend of the average price per square foot in Richmond Hill shows a consistent increase from 2003 to 2021. Despite experiencing a slight dip from 2008 to 2012, likely due to the global financial crisis, it shows a stable recovery and growth from 2012 onwards, demonstrating resilience in the real estate market. (Figure 5) (Figure 8)
2.	Compared to other neighborhoods, Richmond Hill is less volatile. When the average price per square foot in different neighborhoods, like Forest Hills, Kew Gardens and South Ozone Park, shows significant fluctuations, Richmond Hill tends to maintain a steadier trend. This trend means that while Richmond Hill may not have the highest average sale price per square foot, it also doesn't have the lowest values. (Figure 1) (Figure 2) (Figure 3) (Figure 6)
3.	Other neighborhoods, like South Ozone Park and Kew Gardens, are more volatile than Richmond Hill. They have experienced more significant fluctuations, especially in response to external factors like the 2008 financial crisis. On the other hand, Richmond Hill has shown more consistency, with gradual and steady growth, particularly since 2012. (Figure 2) (Figure 3)
4.	Richmond Hill's average price per square foot is generally lower than the larger Queens average. However, the growth rate in Richmond Hill is like that of Queens, suggesting that while properties in Richmond Hill may be less expensive, they offer comparable growth potential. (Figure 11)
5.	The similarities and differences between Richmond Hill and other neighborhoods indicate potential opportunities for a new real estate brokerage office. Despite its lower average price per square foot, Richmond Hill's consistency and resilience could be advantageous. It may appeal to many clients, from those seeking more affordable properties to those looking for steady real estate growth. (Figure 4) (Figure 7) (Figure 9)
Based on the data and analysis, Richmond Hill may be a good location for a new real estate brokerage office. The stable and consistent growth in the average price per square foot makes it an attractive location. Furthermore, compared to the larger Queens area, it offers similar growth potential but at a generally lower price point, which could appeal to various clients.

#### Summary Statistics: Comparing Richmond Hill with other Neighborhoods.
Compared to other neighborhoods in Queens, the summary statistics provide additional insights into Richmond Hill.
1. Minimum and Maximum: The average price per square foot in Richmond Hill varies from $196.74 to $436.24. These figures suggest that Richmond Hill has experienced significant growth but still has lower prices than Forest Hills and Jamaica Estates. The minimum sale price is higher than in specific areas such as Jamaica, South Jamaica, and Jamaica Bay.
2. Median: Richmond Hill's median average price per square foot is $277.38, which is lower than the larger QUEENS median of $310.38. These values imply that properties in Richmond Hill are typically more affordable than the borough average. (Figure 12)
3. Standard Deviation: Richmond Hill's standard deviation is $72.12, lower than the borough average of $91.41. Forest Hills, Kew Gardens, and Jamaica Estates have higher standard deviations, indicating more price volatility. These values suggest that price fluctuations in Richmond Hill are less volatile than in Queens. (Figure 12)
4. Mean: Richmond Hill's mean (average price per square foot) is $285.52, which is less than the QUEENS mean of $335.81. We expect these mean values since QUEENS includes more affluent neighborhoods that raise the average. However, it also indicates that properties in Richmond Hill are generally more affordable, which could benefit a real estate brokerage. 

Considering the above information, Richmond Hill is a promising new real estate brokerage office location. Its lower volatility suggests stability and less risk for potential investors. It also offers a range of properties with generally more affordable prices than the Queens average, which may attract a wider variety of clients. The consistent growth in property prices indicates a healthy market, providing a favorable environment for real estate businesses to succeed.


## Analysis 3
### Executive Summary
This analysis aimed to provide valuable insights for establishing new real estate brokerage offices in New York City, explicitly focusing on Richmond Hill's viability as a potential location. The analysis used a two-pronged approach to categorize neighborhoods based on their real estate market dynamics and compare Richmond Hill's residential property prices to other neighborhoods.
In the first phase, we grouped neighborhoods into two clusters using the K-means clustering algorithm based on median sale price, number of sales, and price per square foot. Cluster 1 (red) included neighborhoods with higher median sale prices, fewer sales, and a higher price per square foot, while Cluster 2 (blue) contained neighborhoods with lower median sale prices, more sales, and a lower price per square foot. We found Richmond Hill classified as part of Cluster 2.
The second phase involved comparing Richmond Hill's residential property prices to other neighborhoods using Welch's t-tests. The results indicated that Richmond Hill's property prices were lower than neighborhoods such as Jamaica, Jamaica Hills, Jamaica Estates, Forest Hills, and Kew Gardens but higher than Jamaica Bay (Queens) and South Jamaica. There is no significant difference in the mean sale price of properties in Richmond Hill and that of Ozone Park, while its property prices were significantly lower than Woodhaven's.

Overall, the results confirm our previous analyses’ findings and suggest that Richmond Hill could be a good location for a new real estate brokerage office. Despite the potential for lower commission amounts due to relatively lower property prices, the neighborhood's vibrant real estate market and affordability compared to surrounding areas could attract more potential buyers and facilitate more transactions.

### Problem Understanding and Definition
This analysis aims to use descriptive statistics, k-means clustering, and t-tests to compare residential property costs with other neighborhoods. These insights will aid in identifying expansion opportunities and aligning strategic decision-making with market trends. The challenge is to deliver accurate data interpretations amidst potentially complex and varied information.


### Data Cleaning and Preparation
We began by cleaning and preparing our data in RStudio. To ensure data accuracy and relevancy, we applied the following filters to our dataset: 
1.	Only records from 2009 onwards were considered. 
2.	We also excluded properties sold for less than $10,000 to eliminate extreme outliers. 
3.	Similarly, we removed properties smaller than 300 square feet and included only residential property types in the analysis.
This cleansing and filtering process produced a more refined dataset, enabling us to generate more accurate and meaningful insights during our exploratory data analysis. Consequently, our subsequent analyses, such as descriptive statistics generation, k-means clustering, and t-tests, will yield more reliable and insightful results that can better inform strategic decision-making.

### Exploratory Data Analysis
#### Five – Number Summary: Residential Sale Price and Gross Square Feet
We analyzed the Residential Sale Prices and Residential Gross Square Feet of Richmond Hill since 2009 and compared them with other neighborhoods in Queens using five-number summaries. This analysis picks up where our previous analysis ends, covering market trends, growth rates, sales distributions, and correlations between property size and sale value.
The Gross Square Footage data analysis shows that Richmond Hill properties range from a minimum of 504 sqft to a maximum of 60,000 sqft. The median residential gross square footage of Richmond Hill is 1,616 sqft, indicating that properties in Richmond Hill are slightly smaller than those in Jamaica, Jamaica Estates, and Kew Gardens. (Figure 1)

The analysis of Residential Sale Prices reveals that the prices in Richmond Hill vary from $10,000 to $10,000,000, with a median price of $475,000. The price range is lower than Jamaica Estates and Forest Hills but higher than South Jamaica and Jamaica Bay. The analysis also highlights that Richmond Hill's lower quartile sale price is relatively higher than that of South Jamaica and Jamaica Bay, reinforcing the affordability advantage we identified in Analysis 2.

These insights confirm that Richmond Hill is an affordable, stable, and consistently growing real estate market, appealing to homebuyers seeking affordability and investors looking for potential growth opportunities. (Figure 2)

In conclusion, the analysis of the five-number summary on Residential Sale Prices and Gross Square Feet from 2009 to 2021 reaffirms Richmond Hill's status as an attractive real estate market. It offers a combination of affordability and growth potential, attracting a broad spectrum of homebuyers and investors. For a more detailed understanding of the market conditions, further analysis will focus on property type proportions, mean and standard deviations of Residential Sales Prices and Gross Square Feet, property type proportions, and transaction counts.

#### Descriptive Statistics: Proportions, Means, Standard Deviation, and Transaction Count.
This analysis includes a comprehensive KPI set covering various aspects of the real estate market, such as property type proportions, transaction counts, residential sale price average and standard deviation, gross square feet, correlation, and coefficient of variation (CV) since 2009.
Richmond Hill is a dynamic real estate market with a high transaction count of 5,451, predominantly residential properties (0.89). Its mean residential sale price is approximately $504,549, which is lower than the overall Queens' mean of $704,176, highlighting its affordability advantage. Additionally, the standard deviation of the residential sale price in Richmond Hill is relatively lower, indicating a less volatile market than in other neighborhoods.
The mean residential gross square footage in Richmond Hill is 1830 sqft, smaller than some neighborhoods but not far from the overall Queens with a mean of 2415 sqft. As expected, Richmond Hill has a strong correlation (0.71) between residential sale prices and gross square feet, implying that property size significantly influences sale prices. (Figure 3)

These insights could help understand future cluster analysis, potentially grouping Richmond Hill with neighborhoods that demonstrate similar patterns. The transaction count, property type proportions, average sale price, and correlation between price and size could all be defining factors for such clustering.
In conclusion, Richmond Hill's real estate market is predominantly residential, dynamic, and affordable. Its properties show a strong correlation between size and price, making it an attractive prospect for investors and homebuyers. These findings are consistent with our previous analyses, further underpinning Richmond Hill's potential as a viable real estate office expansion location.

#### Cluster Analysis: Data Preparation and KPIs
We conducted a thorough cluster analysis of 256 neighborhoods across the five boroughs of New York City. The process included data preparation, selecting Key Performance Indicators (KPIs), scaling the data, and treating outliers. 
To ensure relevance, we filtered the real estate transactions to include only those with a sale price of at least $10,000 and properties larger than 300 square feet from 2009 onwards. We selected three KPIs: median sale price, number of sales, and price per sqft, based on their variance and correlation analyses, providing unique and relevant clustering information. These KPIs allowed us to segment neighborhoods meaningfully for insight generation. (Figure 4)
To achieve accurate and meaningful results, we scaled the data to ensure all KPIs were on a similar scale, and we analyzed six outlier rows across the three KPIs. We judged their impact on the overall analysis to be minimal and kept them in the data.
In the next step we determined the appropriate number of clusters using the Elbow method and performed k-mean clustering on the scaled data. It is important to note that although the chosen KPIs and the presence of outliers influence the insights from the cluster analysis, the insights derived present a valuable starting point for further exploration and analysis. (Figure 5)

#### Cluster Analysis: Visualizing the Clusters
Using a scatter plot matrix, we could visualize the clusters and understand the relationships between our Key Performance Indicators (KPIs): median sale price, number of sales, and price per square foot.
The scatter plot matrix highlighted a clear distinction between the two types of neighborhoods. The red cluster represented neighborhoods with a broader range of median sale prices and a positive correlation between the number of sales and median sale price. The blue cluster, in contrast, showed more uniform median sale prices and a weaker correlation between the number of sales transactions and median sale price.
The correlation matrix provided further insights. A negative correlation (-0.352) between the median sale price and the number of sales suggested that more expensive neighborhoods tend to have fewer sales. Conversely, a strong positive correlation (0.815) between the median sale price and the price per square foot indicated that neighborhoods with higher prices also tend to have a higher price per square foot. An inverse relationship was seen between the number of sales and the price per square foot (-0.311), suggesting that neighborhoods with more sales tend to be more affordable. (Figure 6)
Upon examining the clusters, Richmond Hill and other neighborhoods of interest were found in Cluster 2 (the blue cluster). This segmentation suggests that these neighborhoods have a more uniform median sale price and a weaker correlation between the number of sales and median sale price, reflecting a more stable and predictable real estate market.

Given the nature of the blue cluster, Richmond Hill may be a suitable location for a new real estate brokerage office. The uniform price range and weaker correlation between the number of sales and price indicate a potentially stable and predictable market that could appeal to a brokerage, as it may offer more predictable commissions and be less susceptible to large market fluctuations. (Figure 7) (Figure 8)
In conclusion, the EDA revealed two distinct clusters in the New York City real estate market, each with unique characteristics and trends. The neighborhood of Richmond Hill falls within a segment that might be advantageous for a new real estate brokerage office due to its more stable and predictable real estate market. It is important to note where k =3, Cluster 3 (Richmond Hill and other neighborhoods) showed a weak positive relationship between the number of sales and the price per square foot. This is not ideal, considering the strong correlation we previously found between sales price and gross square footage. In the next step, we will supplement these findings by comparing prices across neighborhoods using the Welch Two sample t-test.

#### Hypothesis Test – Comparing Residential Sale Prices
Our analysis examined the average prices of residential properties in different neighborhoods. We used t-tests to determine if there were any significant differences in the mean property prices between Richmond Hill and the other neighborhoods.
Here are the key insights we gained from our t-test analysis:
1. There is a significant difference in the mean property prices between Richmond Hill and Jamaica, Jamaica Hills, and Jamaica Estates. Richmond Hill has lower mean property prices, and the p-values confirm the statistical significance of this difference. (Figure 9) (Figure 10)
2. Richmond Hill has higher mean property prices than Jamaica Bay (Queens) and South Jamaica, and again, the p-values confirm the statistical significance of this difference.
3. There is no significant difference in the mean property prices between Richmond Hill and Ozone Park, as the p-value is above 0.05. However, there is a significant difference between Richmond Hill and Woodhaven, with Richmond Hill having lower average prices. (Figure 11)
4. Richmond Hill's mean property prices are significantly lower than those of Forest Hills and Kew Gardens, as indicated by the low p-values. (Figure 12) (Figure 13) (Figure 14)

These insights confirm the existence of two distinct neighborhood clusters consistent with previous analyses. They also show that Richmond Hill's property market is more affordable than other neighborhoods, which could attract more potential buyers and lead to more transactions and commissions. However, lower prices also mean lower commission amounts, and this is a trade-off a real estate brokerage may need to consider.

In conclusion, our analysis provides valuable insights into residential sale price differences. While Richmond Hill is a good location with a less volatile market and unique pricing, the lower property prices may result in smaller commission amounts.
