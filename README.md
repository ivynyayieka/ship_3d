# [3D printing will reduce cost and time necessary for ship repair but impact on labour force is complex](https://ivynyayieka.github.io/ship_3d/)

This is an analysis in which I explore trends in the shipbuilding and repair industry as 3D printing takes root. <br/>

#### Getting the Data

Much of the data was collected by copy-pasting since it was not too much in volume <br/>

Sources: 
* Gross output data from [U.S. Bureau of Economic Analysis (BEA)](https://apps.bea.gov/iTable/?reqid=150&step=2&isuri=1&categories=ugdpxind#eyJhcHBpZCI6MTUwLCJzdGVwcyI6WzEsMiwzXSwiZGF0YSI6W1siY2F0ZWdvcmllcyIsIkdkcHhJbmQiXSxbIlRhYmxlX0xpc3QiLCIyMzciXV19)<br/>
* TEU data from [Department of Transportation](https://explore.dot.gov/views/MonthlyContainerPortTEUs/TEUs?%3Aembed=y&%3AisGuestRedirectFromVizportal=y)<br/>
* Labour data from [U.S. Bureau of Labor Statistics](https://www.bls.gov/oes/current/naics4_336600.htm)<br/>
* US Navy ships volume data from [US Navy](https://www.secnav.navy.mil/fmc/fmb/Documents/24pres/Budget_Highlights_Book.pdf)<br/>
* GIS data from [Natural Earth](https://www.naturalearthdata.com/downloads/)<br/>

#### Charting the data

Per instructions, I made the charts in Microsoft Excel. Plotting revealed increases in terms of both total production and total employment in the industry since 2016 and 2020 respectively. 

![gross output](gross_bln_USD.png)
![employment](labour_pic.png)

#### Mapping the ports
I mapped the major ports highlighted by the [Department of Transportation](https://explore.dot.gov/views/MonthlyContainerPortTEUs/TEUs?%3Aembed=y&%3AisGuestRedirectFromVizportal=y) using QGIS. <br/>
I geocoded the data using Google Spreadsheets Extension Geocode by Awesome Table

![gross output](/another_us_port.png)

#### Tech
Microsoft Excel, Geocode by Awesome Table, QGIS
