# [The Data Library for Python  - Quick Reference Guide (Access layer)](https://developers.lseg.com/en/article-catalog/article/the-data-library-for-python-quick-reference-guide-access-layer)
This is a quick reference guide for the Data Library for Python on different asset types

If you’re new to the library, a shallow dive into LSEG APIs landscape, including the introduction to data library can be found in article [Summary of Common LSEG Refinitiv APIs](https://developers.lseg.com/en/article-catalog/article/summary-of-common-lseg-refinitiv-apis)

- [How to use the Data Library](https://developers.lseg.com/en/article-catalog/article/summary-of-common-lseg-refinitiv-apis#HowtousetheRDPythonLibrary)
- [Where to go to figure out the available fields that I can access using the Refinitiv Data Libraries (such as the RD Python Library)?](https://developers.lseg.com/en/article-catalog/article/summary-of-common-lseg-refinitiv-apis#WheretogotofigureouttheavailablefieldsthatIcanaccessusingRDP)

_Please note that the data library in Codebook is the version 1 (Refinitiv Data Library). It will be upgraded to the newer version, version 2 - LSEG Data Library soon._

- _After the rebranding and release of LSEG Data Library 2.0, the Refinitiv Data Library will become " Feature Complete", but we will continue to support it and provide maintenance releases. This is essential for customers who cannot migrate to the LSEG Data Library 2.0. However, new features will only be added to the LSEG data library._

In this article, we are focusing on using the access layer, which is the easiest way to get data. It provides simple interfaces allowing you to rapidly prototype solutions within interactive environments such as Jupyter Notebooks. It has been designed for quick experimentation with our data and for Financial Coders specific needs. (To learn more about Data Library for Python’s layers: [example codes can be found here](https://github.com/LSEG-API-Samples/Example.DataLibrary.Python/tree/lseg-data-examples/Examples))

![ld-lib-sessions](https://github.com/user-attachments/assets/443fd469-8314-45ff-b59d-a001d689e435)

Table of contents
Here’s what included in this quick reference guide.

1. Search
2. Symbology
    - Convert symbols, Get data - get RIC from bond, Get data - get CUSIP and international CUSIP, Get data with Screener, Get data with Peers, Get data of instruments with all available fields, Get data of instruments with specific fields, Get constituent with Chain object
3. Timeseries
    - Get data with field level parameter, Get data with request level parameter (global parameter), Get history
4. Company guidance
5. Earnings
6. Analyst recommendations
7. Industry Analysis / The Reference data Business Classification (TRBC)
8. Ownership data
9. Corporate actions data
10. Volatility
    - Volatility, Equity implied volatility, Futures implied volatility
11. Portfolio and Lists
    - Portfolio, List, Monitor, Index/exchange constituents as of certain date, Index leavers/joiners
12. Fixed income data
    - Bond status, Fixed income securities core reference data, Bond pricing, Bond analytics, Historical bond pricing, Historical analytics, Credit default swaps
13. Pricing streams
    - Using pricing streams with events, Using pricing streams as a data cache, Get a snapshot for a subset of instruments and fields
