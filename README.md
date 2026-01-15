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

:man_cook: The Process <br>
---
I started by looking for countries with the oldest recorded data for renewable energy so I had ample of data to work with, this led me to Norway. <br> <br>

Then, I looked for resources where I could get said data. This was harder than expected as I everything I came across was locked behind a paywall unitl I asked a friend who told me about a website called ["Our world in data"](https://ourworldindata.org/), I would find all necessary data in the format of an excel file for not just Scandanavian countries but the whole world. <br><br>

This started the ETL (Extract, Transform and Load) process.<br>
* <b>Extract</b>: Downloaded Excel files from OWID’s public data portal.
* <b>Transform</b>: Filtered for Norway, Sweden, Denmark, Finland
* <b>Load</b>: Loaded cleaned tables into Power BI

The next step was to choose the appropriate chart, data and formulas to accurately display the result. 
* Appropriate chart: Used Designing Effective Tables and Graphs by Stephen Few as a guide.
* Data: Based on the question I needed to answer I selected the relevant country, time, and renewable energy variables which were then aggregated to support comparison and trend analysis.
* Formulas: I created calculated measures to aggregate total electricity generation, separate renewable and non-renewable output, and calculate the share of renewables in total electricity production, enabling clear comparison across countries and over time.

After creating the dashboard, I wrote a report that addressed the main analytical questions by interpreting the visualisations and translating the results into clear insights. <br>

:seedling: Overall Growth
---
This project strengthened my ability to analyze complex datasets, structure data for meaningful comparisons, and create dashboards that clearly communicate insights. I also improved my data storytelling skills, learning to turn raw numbers into actionable findings. Overall, it boosted my confidence in making analytical decisions and presenting results in a professional, understandable way.

:runner: Running the Project
---
The repository includes the Power BI dashboard file (.pbix) along with the Excel datasets used in the analysis. To explore the dashboard:

1. Download the repository to your local machine.

2. Open the .pbix file using Power BI Desktop (free download from Microsoft if needed).

3. Ensure the included Excel datasets are in the same folder or properly linked to the Power BI file.

4. Interact with the visuals to explore trends, comparisons, and insights across countries.

Note: All data used in the dashboard is included, so no external data connection is required.

:movie_camera: Video
---

