# Dashboard
## Building a DIY disease tracking dashboard
### Click the link to access Jupyter Notebook via Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/amberlie03/Dashboard/HEAD?urlpath=%2Fdoc%2Ftree%2Fvoila%2Frender%2FDashboard.ipynb)
### Click the link to access Voila view via Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/amberlie03/Dashboard/HEAD?urlpath=voila/render/Dashboard.ipynb)

During the Pandemic, Public Health England (PHE) launched a Covid-19 dashboard. This timely service came with an Application Programming Interface (API) allowing users programmatic access to the data for the purpose of creating visualisations or data analysis. Interestingly, it also included a wrapper library written in Python, that made access to the data seamless. At the end of 2023, the PHE dashboard was replaced by the UK Health Security Agency dashboard (UKHSA dashboard). This new API, at the time of writing in the Beta stage, includes data on various infectious diseases including respiratory and gastrointestinal, bloodstream infections, and vaccine-preventable diseases. The data are better organised and documented, and many of the quirks of the old API have been fixed. An interesting feature of the new system is that all of its code has been open-sourced.

The data was extracted from UKHSA dashboard using an API wrapper to the convert the raw data to JSON format. The data that we are looking at shows the rolling average number of cases over the 7 day period per 100,000 population ending on the dates shown. New cases are reported by specimen date - the date the first sample that identified the infection was taken from an individual. We explore the rolling mean of cases across different age groups for the year of 2020.
