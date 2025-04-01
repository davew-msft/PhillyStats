# PhillyStats Research

_this repo and code is still very rough_

* Start [here](./PhillyStat%2001-Setup.ipynb)
  * this notebook has a lot of documentation for problem space as well as the Fabric/Spark code to setup you environment with the latest data from Carto.  
  * there are a lot of testing/wip queries at the bottom which will fail and can be ignored for now
  * to actually load the data change `DownloadLatestData = 1`
* [Analytics workbook](./PhillyStats-Analytics.ipynb)
  * this notebook is trying to construct a dataset for predictive analytics to indicate whether a property exhibits the _7 factors_.  
    * `philly_flattened_properties` table
  * code is not near complete but has a number of attempts at analyzing the data.  
* [Walking the LLC Chain](./PhillyStats02-LLC-Analytics.ipynb)
  * **this is the important notebook**
  * walks the LLC and property chains given the available data.  

_Data provided in the sftp server is as of 4/1/2025_

The data can be downloaded in parquet format.  Send me an email for instructions.  

[Last call video](https://livesend.microsoft.com/i/ausnMbyIY6eBJ2agORgaxsQMbsqBv3xIpslURsCRCiToZJI6IuVTcYCg0WQuxgXrvBenmg1wOjiYdwTtL0pgtBFiQx___5Olr3DfwxlE798WTbiYe7yV3QjL8PLUSSIGNV___MVrwhR)