# API4SEC

* **IMPERVA_Statistics.ipynb**

  So, would you like to create an statistics/audit report to see how many visits,hits and threats were per site for each Imperva policy ?

  Again, APIs to the rescue.  I will show you a way to create a report based on timeseries API endpoints provided by Imperva.  The following operations enable  you to retrieve traffic statistics for sites and accounts.

  Whenever you're doing data analysis in Python your most likely using Pandas since it's widely used and, most importantly, one of the best tools available for data analytics.

  This notebook is going to show you a basic example of how you can use Pandas to generate a dataframe with API data, also assumes a little familiarity with Pandas libraries.

  We will use the following Imperva endpoints:

  */api/prov/v1/sites/list* to list sites and */api/stats/v1* to get site statistics.

  For more information about teh use of Imperva API, please visit:
  - [Imperva Sites API](https://docs.imperva.com/bundle/cloud-application-security/page/api/sites-api.htm)
  - [Imperva Traffic API](https://docs.imperva.com/bundle/cloud-application-security/page/api/traffic-api.htm)

  Enjoy!
