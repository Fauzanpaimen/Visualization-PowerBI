![Icon](https://github.com/Fauzanpaimen/Visualization-PowerBI-/blob/main/Image/icon.jpg)

# Visualization (PowerBI)



I don't have a personal account for Power BI, so I will share a snapshot of the dashboard I created using Power BI. Since my dashboard mostly contains internal data for my previous company, I will mask or cover all the sensitive information. [Slide Show](https://www.canva.com/design/DAGMPL8nAUA/_iIZ0MxLGD9Xwv1uoYgIJQ/edit?utm_content=DAGMPL8nAUA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)



-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------


# 1)Anomaly Detection (POC)

This dashboard is created to visualize output for POC anomaly detection. If the indicator is red, there is anomalous data in the PDF within the folder. For this POC, it is assumed that there is no duplicated data between PDFs within the folder.

- Data is extracted from PDFs, then output is saved in JSON format.
- Power BI will connect to the folder of the JSONs.
- Data transformation is done in Power Query.
- DAX is utilized for green-red indicators.

## Dashboard

![Image](https://github.com/Fauzanpaimen/Visualization-PowerBI-/blob/main/Image/Anomaly.jpg)


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------


# 2)DCRMS Dashboard

Document, Content & Record Management Standard (DCRMS). CRMS Source Compliance Dashboard provides measurement and transparency of unstructured data condition at source system for business reference. The measurement focused on Metadata Completeness, Retention and Duplication at File Level in source system.

This dashboard is connected to a Neo4j database, which is a graph database. It connects via API and queries data using Cypher. Additionally, it pulls metadata from five different sources within Neo4j. Utilized Power Query for data transformation and DAX for calculations.

This dashboard shows both overall data and data for each source. You can navigate to a detailed page for each source. The red dot box shows a button you can click.

## Dashboard

![Image](https://github.com/Fauzanpaimen/Visualization-PowerBI/blob/main/Image/DCRMS01.jpg)
<pre>[Main Page]> The homepage displays overall data from all sources. There are buttons that allow you to hover over them to navigate to other pages.
</pre>
![Image](https://github.com/Fauzanpaimen/Visualization-PowerBI/blob/main/Image/DCRMS02.jpg)
<pre>[Main Page]> Page that show duplicate across source.
</pre>
![Image](https://github.com/Fauzanpaimen/Visualization-PowerBI/blob/main/Image/DCRMS03.jpg)
<pre>[Sub Page]> Main page for Specific source.
</pre>
![Image](https://github.com/Fauzanpaimen/Visualization-PowerBI/blob/main/Image/DCRMS04.jpg)
<pre>[Sub Page]> Page for checking duplicates in a specific source.
</pre>
![Image](https://github.com/Fauzanpaimen/Visualization-PowerBI/blob/main/Image/DCRMS05.jpg)
<pre>[Sub Page]> Page for checking incomplete metadata in a specific source.
</pre>
![Image](https://github.com/Fauzanpaimen/Visualization-PowerBI/blob/main/Image/DCRMS06.jpg)
<pre>[Sub Page]> Page for checking retention period in a specific source.
</pre>


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------


# 3)Nebula Dashboard

Nebula Dashboard to monitor progress from 4 pillars: business development, product, operations, and marketing.

This dashboard is connected to Excel in the SharePoint and sharepoint list, leveraging data modeling to connect between tables. DAX is used for calculations.

## Dashboard

![Image](https://github.com/Fauzanpaimen/Visualization-PowerBI/blob/main/Image/Nebula1.jpg)
<pre>[Home Page]> The homepage. There are buttons that allow you to hover over them to navigate to other pages.
</pre>
![Image](https://github.com/Fauzanpaimen/Visualization-PowerBI/blob/main/Image/Nebula2.jpg)
<pre>[Business Development Page]> Page that show Business Development progress.
</pre>
![Image](https://github.com/Fauzanpaimen/Visualization-PowerBI/blob/main/Image/Nebula3.jpg)
<pre>[Product Page]> Page that show Product progress.
</pre>
![Image](https://github.com/Fauzanpaimen/Visualization-PowerBI/blob/main/Image/Nebula4.jpg)
<pre>[Operation Page]> Page that show Operation progress.
</pre>
![Image](https://github.com/Fauzanpaimen/Visualization-PowerBI/blob/main/Image/Nebula5.jpg)
<pre>[Marketing Page]> Page that show Marketing progress.
</pre>


