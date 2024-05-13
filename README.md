![Icon](https://github.com/Fauzanpaimen/Visualization-PowerBI-/blob/main/Image/icon.jpg)

# Visualization (PowerBI)



I don't have a personal account for Power BI, so I will share a snapshot of the dashboard I created using Power BI. Since my dashboard mostly contains internal data for my previous company, I will mask or cover all the sensitive information.


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


