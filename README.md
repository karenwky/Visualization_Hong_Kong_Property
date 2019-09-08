# Visualization_Hong_Kong_Property
With data scraped from Hong Kong Property [website](https://en.hkp.com.hk/find-property/), a simple EDA(Exploratory Aata Analysis) project is conducted. 

### Data Source
1. [Transaction History](https://app2.hkp.com.hk/utx/default.jsp?lang=en)<br/>
Having transaction data within 3 years, explore the distribution of property transaction in Hong Kong.

2. [Find Property](https://en.hkp.com.hk/find-property/#list)<br/>
Scraping property details such as number of bedrooms and selling price, discover the correlation between various features. 

### Findings
Check out [Google Slides]() presentation. <br/>
<br/>
![Property Transactions in HK by District](/images/by_district.png)<br/>
Two clusters can be simply divided according to the data. For the purple districts, only a few number of estates have relatively high number of transactions in the district. On the contrast, for the cyan districts, relatively high number of estates have high number of transactions in the district. The purple districts are having a more skewed distribution than the cyan districts. <br/>
<br/>
![Box Plot](/images/box_plot.png)<br/>
Most of the number of transactions are within the range 200. N.T. East(grey box) has the highest upper extreme and highest median for number of transaction. Kowloon Central(purple box) has the highest number of outliers for number of transaction. <br/>
<br/>
![Bar Chart](/images/bar_chart.png)<br/>
From the *total* number of transaction data, slightly difference is shown compared with distribution data by estate. Although N.T. East has the highest upper extreme and highest median for number of transaction(refer to the boxplot above), it is only the third highest district in total number of transaction. But with a lot of outliers, Kowloon Central is the district with highest total number of transaction. <br/>
<br/>
<img src="/images/3d_scatter.png" alt="3D Scatter Plot" width=600><br/>
The efficiency ratio is mostly between the range 70 to 90 percent. 


Check out the complete rundown with [Jupyter notebook](). 

### Skills Acquired
* Pandas
* Beautiful Soup
* Regex text cleaning 
* Seaborn
* Matplotlib
