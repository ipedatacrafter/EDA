Project Name - FedEx Logistics Performance Analysis
Project Type - EDA
Project Summary –
Optimizing FedEx Logistics Through Data Analysis
In today’s fast-paced, globally connected market, FedEx Logistics plays a pivotal role in managing supply chains across various industries and regions. With the rapid growth of eCommerce and global distribution networks, maintaining efficient logistics operations is critical to staying competitive. This project focuses on analyzing data from FedEx Logistics to uncover insights that can optimize shipment processes, minimize costs, and enhance customer satisfaction. The dataset contains information on shipment modes, countries, vendors, line item values, weights, freight costs, delivery delays, and more, allowing for a comprehensive analysis of the company’s logistics performanctisfaction.
Business Findings From Data:
1.	Count of Shipments by Country:
Based on the shipment count, it's evident that 
South African countries lead with the highest 
volume of consignments being shipped. This suggests a strong demand 
or active trade routes within that region, 
potentially driven by industries such as mining, agriculture, 
and manufacturing.Following closely behind 
are Nigeria and Cote d Ivoire, and at least are Zimbabwe and Tanzania
which also see significant shipment activity. 
Vietnam's position could be due to its role as a manufacturing hub in Southeast Asia, while Zimbabwe's 
shipments might be related to its exports in mining, 
agriculture, or other key commodities. 
This trend indicates a diverse global trade landscape with strong regional markets.
<img width="624" height="201" alt="image" src="https://github.com/user-attachments/assets/dcb05a26-ea61-41f5-8f37-5d0655a1606d" />
Distribution of Shipment Modes
It is clear that more than 63% of consignments are delivered by air, indicating a strong preference 
for this mode of transportation, likely due to its speed and efficiency. 
Following air transport, trucking accounts for 27% of the deliveries, 
suggesting that it plays a significant role in domestic distribution or 
shorter regional routes. Ocean freight, at 4%, is the least utilized method, which may 
reflect longer delivery times and logistical challenges associated with shipping by sea. 
Additionally, air charter services make up 5% of the total, 
which may be used for specialized shipments requiring rapid delivery. 
This distribution highlights the varying needs and priorities in logistics,
with air transport being the dominant choice for time-sensitive consignments.
<img width="624" height="248" alt="image" src="https://github.com/user-attachments/assets/247a9200-13f8-406e-a004-d8a8b99a477a" />
Average Freight Cost
 The analysis reveals that the average freight cost is $11,076.78, with a 
right-skewed distribution indicating that most shipments are below 
this average. While lower-cost consignments are more frequent, there are a 
few high-value shipments that significantly influence the average. 
Very few shipments exceed $50,000, suggesting that high-cost logistics are less common. 
This insight can help optimize logistics strategies by identifying the factors 
driving higher costs and exploring ways to reduce them.
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/ae3ebc15-9c0a-4ce6-80d0-a14b4759bc4f" />
Line Item Quantity Distribution
The distribution shows the most common quantities
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/d87566a3-01ee-44c5-aee9-fbeac8d3c948" />
Weight Distribution (Kilograms)
The box plot for shipment weights in kilograms indicates 
that there may be a lack 
of data or very little variability in the weights, 
as the plot appears mostly empty. 
This suggests that the majority of shipments fall 
within a narrow weight range or that 
there are no shipments with significantly high or low weights. 
Without distinct quartiles or 
outliers visible, it is challenging to assess the overall 
distribution and characteristics of the 
shipment weights. This might warrant further investigation 
into the dataset to determine if any data points 
are missing or if the shipments are consistently uniform in weight
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/1f30d8e8-2ce2-4948-83de-14b255f42391" />
Vendors with highest orders
The bar chart illustrates the top vendors based on the number of orders.
SCMS from RDC stands out with a significantly higher order count
(over 5000) compared to other vendors. 
The remaining vendors, such as Ogenics, Ltd and S. 
BUYS WHOLESALER, have relatively low order 
counts (around 1000 or less), showing a vast disparity. 
This suggests that SCMS from RDC plays a dominant role in procurement, 
while the other vendors are less active in comparison.
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/3267b459-1539-45f8-a4f7-5f23f04202eb" />
Bi-Variate Analysis
Average Weight by Shipment Mode
The bar plot reveals that air transport handles relatively lighter shipments, 
with an average weight between 1000 to 1500 kg, 
likely due to speed and cargo limitations. 
In contrast, truck transport carries significantly heavier shipments, 
averaging 6500 kg, 
while ocean and rail shipments have even higher averages, around 
6800 kg and 7000 kg, respectively. 
This indicates that air is used for lighter, more urgent goods, 
while ground and sea are preferred for bulkier cargo.
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/93822d9e-8e43-43de-abf9-2a66146321a1" />
Delivery Delays by Shipment Mode
The bar plot presents delivery delays by shipment mode. 
Air shipments show a slight delay close to zero days, indicating they are typically on time. 
Truck shipments experience moderate delays of around 10 days on average. 
Air charter shows the most significant delays, exceeding 15 days, 
while ocean transport faces delays just under 5 days. 
This suggests that air charters are the least 
reliable in terms of timeliness, while standard 
air shipments are the most punctual. 
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/8572e597-94e9-4491-83ec-4c700100a756" />
Total Shipments Over Time
The chart depicts the total number of shipments over time, 
highlighting trends and potential seasonal patterns from 2006 to 2016. 
We observe an initial gradual increase in shipments between 2006 and 2009, 
followed by notable fluctuations in volume from 2010 onwards. 
Peaks are visible at multiple intervals, 
indicating potential periods of high demand, 
while some sharp drops suggest potential off-seasons or disruptions. 
The most significant activity occurred around 2013-2014, 
where shipment counts approached or exceeded 250. 
After 2015, there's a visible decline, possibly indicating a 
slowdown in operations or changing market conditions. 
This pattern may reflect seasonal or 
business-cycle-driven variations in shipment volumes.
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/1a1841dd-ea78-47a9-88c0-89b1a4bcbce7" />
Line Of Items Across Diffrent Shipment Mode
The box plot visualizes the distribution of items 
across different shipment modes. 
It shows that FedEx has the highest median number of items shipped, 
followed by Truck and Air Charter. 
The interquartile range (IQR) for Truck is the smallest, 
indicating a more consistent number of items shipped compared to other modes. 
The outlier for Other suggests a significantly higher 
number of items shipped in one or more months. Overall, 
the plot highlights the variability in item shipments 
across different modes and identifies 
FedEx as the most consistent performer in terms of shipment volume
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/d640f168-b244-4a5d-bb2e-e49b72f226a7" />
Freight Cost In Comparison to Weight
The scatter plot illustrates the relationship between 
freight cost and weight for a set of shipments. 
The general trend is that as the weight of a shipment increases, 
so does the freight cost. 
However, there is also a degree of variability around this trend, as evidenced by 
the scatter of the data points. This suggests that factors other than weight, 
such as distance, shipment mode, or item type, may also influence freight costs. 
Additionally, the plot reveals a few potential outliers, 
which could be due to unusual shipments or errors in the data.
Overall, the scatter plot provides a visual representation of 
the relationship between freight cost and weight, 
highlighting the general trend while also indicating the 
presence of additional factors that may affect pricing.
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/25514727-ed55-4b49-bec3-dd29e0e3467d" />
Highest Paying Countries based on Freight Cost
The bar chart ranks the top 10 countries based on their total freight costs. 
Nigeria emerges as the highest-paying country, followed by China and Rwanda. 
The chart visually compares the relative freight costs among these countries, 
highlighting the significant differences in expenditure. 
It's evident that Nigeria's freight costs are substantially 
higher than those of the other countries listed. 
The chart offers a clear overview of the countries with the highest freight costs, 
allowing for easy identification and comparison.
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/2072ad4b-f519-44ed-a1e7-b6e0589e8b96" />
Shipment Mode in comparison to Freight Cost
The box plot compares the distribution of freight costs across different shipment modes. 
It shows that Air Charter has the highest median freight cost, 
followed by Truck and Sea. The interquartile range (IQR) for Sea is the smallest, 
indicating a more consistent freight cost compared to other modes. 
The outlier for Truck suggests a significantly higher freight cost in one or more months. 
Overall, the plot highlights the variability in freight costs 
across different modes and identifies Air Charter as the most expensive option.
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/bc855c48-147c-4587-ba88-6fda1fa7997f" />
Multi-Variate Analysis
Freight Cost by Country, Shipment Mode, and Vendor
The scatter plot illustrates the relationship between freight cost 
and weight for a set of shipments across different modes and top 10 countries. 
The general trend is that as the weight of a shipment increases, so does the freight cost. 
However, there is also a degree of variability 
around this trend, as evidenced by the scatter of the data points. 
This suggests that factors other than weight, such as distance, 
shipment mode, or country, may also influence freight costs.
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/71b281ba-1559-4b83-b4d8-63cc190a6c40" />
Line Item Value in comaprison with Freight Cost by Vendor and Shipment Mode
The scatter plot illustrates the relationship between the line item value and freight cost for a set of shipments, 
considering the effects of vendor and shipment mode. 
The general trend is that as the line item value increases, 
so does the freight cost. However, there is also a degree of variability around this trend, 
as evidenced by the scatter of the data points. 
This suggests that factors other than line item value, such as vendor, 
shipment mode, or other variables not included in the plot, may also influence freight costs.
<img width="624" height="265" alt="image" src="https://github.com/user-attachments/assets/382ae8df-99cf-4c30-8cbe-47e9e65bf499" />
Freight Cost by Shipment Mode, Fulfill Via, and Country
The box plot compares the distribution of freight costs across different shipment modes, 
fulfillment vias, and countries. 
It shows that FedEx Ground has the highest median freight cost, 
followed by FedEx Express and FedEx Economy. 
The interquartile range (IQR) for FedEx Economy is the smallest, 
indicating a more consistent freight cost compared to other modes. 
he outliers for FedEx Ground and FedEx Express suggest significantly 
higher or lower freight costs in one or more months.
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/9fa75842-2543-480f-8f6e-79b6d21b4eca" />
Correlation Heatmap
The correlation heatmap reveals strong positive 
relationships between line item quantity and value, 
and a moderate positive correlation between weight and freight cost. 
Weaker positive correlations exist between line item insurance and freight cost. 
These findings suggest that the quantity and value of items, 
as well as weight, are significant factors influencing freight costs.
<img width="624" height="235" alt="image" src="https://github.com/user-attachments/assets/ea7b1b49-6a21-4d41-a665-e300355cca5c" />








