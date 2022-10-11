# Adventure Works Sample Data

|[![](https://docs.microsoft.com/en-us/power-bi/guidance/media/dax-sample-model/adventure-works-logo-150x150.png)](https://github.com/jchinchillaMSFT/ww-csu-psk-synapse-retail/tree/main/Sample/AdventureWorks)|
|:---:|
|[View data files](https://github.com/jchinchillaMSFT/ww-csu-psk-synapse-retail/tree/main/Sample/AdventureWorks)|



## Data Files

The sample data extracted from the Adventure Works database has ten data files:

|Data File|Description|
|-----|-------|
|**ChannelType.csv**|Channel Types can be either **Reseller** or **Internet**|
|**Country.csv**|List of Countries with ISO Country Names|
|**Customer.csv**|Describes customers and their geographic location. Customers purchase products online (Internet sales).|
|**Date.csv**|There are three relationships between the **Date** and **Sales** tables, for order date, ship date, and due date. The order date relationship is active. The company's reports sales using a fiscal year that commences on July 1 of each year. The table is marked as a date table using the **Date** column.|
|**Product.csv**|Stores finished products only.|
|**Reseller.csv**|Describes resellers and their geographic location. Reseller on sell products to their customers.|
|**Sales.csv**|Stores rows at sales order line grain. All financial values are in US dollars (USD). The earliest order date is July 1, 2017, and the latest order date is June 30, 2021.|
|**SalesOrder.csv**|Describes sales order and order line numbers, and also the sales channel, which is either **Reseller** or **Internet**. This table has a one-to-one relationship with the **Sales** table.|
|**SalesTerritory.csv**|Sales territories are organized into groups (North America, Europe, and Pacific), countries, and regions. Only the United States sells products at the region level.|
|**Location.csv**|Gepgraphy list of City, Zipcode, State/Province and Country Id from the Country.csv data file |

## Power BI Dasboard

A sample Power BI Dashboard and Details report is included:

|Power BI|
|-----|
|![Alt text]([https://assets.digitalocean.com/articles/alligator/boo.svg](https://github.com/jchinchillaMSFT/ww-csu-psk-synapse-retail/blob/f887add868d68e6d046dbe8cd6e5025d7f9f2e82/Sample/PowerBI/Retail%20Analytics%20Dashboard.png) "Retail Analytics Dashboard")|
