# :chart_with_upwards_trend: Change-in-renewable-energy
An interactive dashboard to show changes in different forms of renewable energy found in Norway. <br>
The report has detailed information about the findings of this project along with Data sources, ETL, structure and DAX formulas.

:star: Tools
---
* Power BI
* Excel

:bar_chart: Description of Analysis <br>
---
Here is what the different analysis shows you.
* First analysis shows renewable share of four Scandinavian countries.
* Second analysis shows change in renewable energy sources for Norway from 2005 - 2023. 
* Third analysis compares Norways renewable energy generation to it's three Scandanavian neighbours.
* Fourth analysis is a prediction/forecast for Norway's energy generation to the year of 2030.

:dart: Slicer <br>
---
The slicer can be used to change between the four available Scandanavian countries. The slicer only changes values you see in the first analysis.<br> 
* Denmark
* Finland
* Sweden
* Norway

:man_cook: The process <br>
---
I started by looking for countries with the oldest recorded data for renewable energy so I had ample of data to work with, this led me to Norway. <br> <br>

Then, I looked for resources where I could get said data. This was harder than expected as I everything I came across was locked behind a paywall unitl I asked a friend who told me about a website called ["Our world in data"] (https://ourworldindata.org/), I would find all necessary data in the format of an excel file for not just Scandanavian countries but the whole world. <br><br>

This started the ETL (Extract, Transform and Load) process.<br>
* Extract: Downloaded Excel files from OWID’s public data portal.
* Transform: Filtered for: Norway, Sweden, Denmark, Finland
* Load: Loaded cleaned tables into Power BI






