# tanzania_mobile_money

BACKGROUND

The training dataset contains demographic information and what financial services are used by approximately 10,000 individuals across Tanzania. This data was extracted from the FSDT Finscope 2017 survey and prepared specifically for this challenge.
Each individual is classified into four mutually exclusive categories:
No_financial_services: Individuals who do not use mobile money, do not save, do not have credit, and do not have insurance
Other_only: Individuals who do not use mobile money, but do use at least one of the other financial services (savings, credit, insurance)
Mm_only: Individuals who use mobile money only
Mm_plus: Individuals who use mobile money and also use at least one of the other financial services (savings, credit, insurance)
This dataset is the geospatial mapping of all cash outlets in Tanzania in 2012. Cash outlets in this case included commercial banks, community banks, ATMs, microfinance institutions, mobile money agents, bus stations and post offices. This data was collected by FSDT.


CONCLUSION


After analysing the dataframe of Tanzanian mobile money users containing 7094 records, it is clear that the people still prefer using cash and other fanancial services over mobile money. Young people are active mobile money users than old people, so there is still a large number of people who are not using the mobile money services. I think with the right campaigns the mobile money service providers can reach more clients. Married people are target for the mobile money services as they is more of them using it. Traders make more money but not most of them use the mobile money services, so they are also the right target market to approach.
An intensive campaign to introduce the mobile money services to potential clients will definetly attract more people in using it and grow its subscription as there is still a large number of people who are not using it. Most people in our data stay in the rural areas of the country. They rely on trading to make money as they stay near the shore so its easy for them to ship their goods to other places. They rely on agriculture as their main source of production.

Requered packages

from IPython.display import display, HTML
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import folium 
import webbrowser
from folium.plugins import MarkerCluster
