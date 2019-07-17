EXPLORATORY DATA ANALYSIS
# Framing Data with DataFrames
CHANNELING OPEN DATA INTO BUSINESS FRAMEWORKS

At the outset of any challenge, but especially for the complex and ambiguous ones that data scientists often face, structuring a thought process to approach the fundamental issue is one of the initial tasks. Many industries employ subject matter experts that have domain-specific knowledge, where unique paradigms of thinking are continually developed, taught and enhanced.

A functional organizational structure separates employees with specific skills into departments such as Human Resources, Sales, Marketing, Finance and Engineering, etc. This can produce a silo effect, in which useful information is created, but not necessarily shared. In response, companies assemble cross-functional teams to facilitate sharing and learning across the organization.

These teams can increase overall company effectiveness because they strengthen the firm’s interdependent internal network. For example, strategic decisions can be improved by incorporating, say, information and insights inferred by data scientists. So let’s take a look at how rapidly growing data can be channeled into intuitive frameworks that are familiar to business leaders.

[Continue reading the full story featured in Towards Data Science, a Medium publication...](https://towardsdatascience.com/framing-data-with-dataframes-d9b7ce012be5?source=friends_link&sk=0866bef9af6443371ada8b3ed6753e67)

## Repository Contents

* [Project Features](#project-features)
* [Data Products](#data-products)
* [Output Results](#output-results)
* [Contribute](#contribute)

## Project Features
PET CARE INDUSTRY | BUSINESS INTELLIGENCE | BCG GROWTH-SHARE MATRIX | FEATURE ENGINEERING

[View the interactive chart of The BCG Growth-Share Matrix in Plotly...](https://plot.ly/~adam.c.dick/2/growth-share-matrix-of-licensed-dogs-in-new-york-by-neighborhood/)

<p align="center">
  <img src="/img/01_Growth_Share_Matrix_of_Licensed_Dogs.jpeg" title="BCG Growth-Share Matrix">
</p>

- [x] **The BCG Matrix**<br>
Data-driven visualization of the pet care industry in New York City based on constituent growth rates and market share, creating four quadrants called Dogs, Question Marks, Stars and Cash Cows.
- [x] **The BCG Matrix: Dogs**<br>
Low-growth, low-share markets that typically struggle to break-even. The conventional wisdom of analysts is to liquidate business in this area.
- [x] **The BCG Matrix: Question Marks**<br>
High-growth, low-share markets that have both potential and risk. New businesses target this area through a select and divest strategy.
- [x] **The BCG Matrix: Stars**<br>
Question Marks that have been widely adopted to become market leaders. Continued growth pushes firms to invest due to high competition.
- [x] **The BCG Matrix: Cash Cows**<br>
Mature markets where entrenched players can maintain their position with minimal investment, allowing them to milk reliable cash flows.
- [x] **Competitor Concentration**<br>
Concentration Ratios (CR) and Herfindahl-Hirschman Index (HHI) of the total market share held by the top firms in the industry as well as the geographic density by neighborhood.
- [x] **Market Size**<br>
5-Year Compound Average Growth Rate (CAGR) from 2014 to 2019 of licensed dogs for each New York City neighborhood.

## Data Products
YELP FUSION API | NYC OPEN DATA | REQUESTS

The American Pet Products Association (APPA) [estimates](https://www.americanpetproducts.org/press_releasedetail.asp?id=191) that the pet care industry will exceed $75 billion in 2019, increasing by 3.9% over the previous year. Consumer spending categories are led by pet food ($32 billion), veterinary care ($19 billion) and supplies & OTC medicine ($16 billion).

**[New York State Department of Health Zip Codes](https://www.health.ny.gov/statistics/cancer/registry/appendix/neighborhoods.htm)**
* 5 Boroughs
* 42 Neighborhoods
* 178 ZIP Codes

**[Yelp Pet Stores and Pet Services](https://www.yelp.com/fusion)**
* 1,502 unique pet stores and services actively operating in 2019

**[NYC Dog Licensing Dataset](https://data.cityofnewyork.us/Health/NYC-Dog-Licensing-Dataset/nu7n-tubp)**
* 122,000 licensed dogs in New York City

## Output Results
PYTHON | PANDAS | SQL | SQLITE3 | JSON | TIME | PLOTLY | SEABORN | MATPLOTLIB | NUMPY

**[New York City Neighborhoods](https://github.com/acdick/framing_data_with_dataframes/blob/master/src/01_Neighborhoods.ipynb)**

**[Pet Stores and Services](https://github.com/acdick/framing_data_with_dataframes/blob/master/src/02_Pet_Stores_and_Services.ipynb)**

**[Licensed NYC Dogs](https://github.com/acdick/framing_data_with_dataframes/blob/master/src/03_Dogs.ipynb)**

**[Exploratory Data Analysis](https://github.com/acdick/framing_data_with_dataframes/blob/master/src/04_Exploratory_Data_Analysis.ipynb)**
* Competitor concentration
* Market size
* The BCG Growth-Share Matrix

**First 10 Neighborhoods in New York, Mixed Format (Wide and Long ), NYS Dept. of Health**<br>

<p align="center">
  <img src="/img/02_First_10_Neighborhoods_Mixed_Format.png" title="First 10 Neighborhoods Mixed Format">
</p>

**First 10 Neighborhoods in New York, Long Format**<br>

<p align="center">
  <img src="/img/03_First_10_Neighborhoods_Long_Format.png" title="First 10 Neighborhoods Long Format">
</p>

**First 10 New York Pet Stores and Pet Services Actively Operating in 2019, Yelp Fusion API**<br>

<p align="center">
  <img src="/img/04_First_10_Pet_Stores.png" title="First 10 Pet Stores">
</p>

**Concentration Ratios for the Top 8 Firms in the New York Pet Care Industry**
* CR4 of top four firms of 8.9%
* CR8 of top eight firms of 11.9%
* HHI of 31 out of 10,000 (high competition)

<p align="center">
  <img src="/img/05_Concentration_Ratios_for_Top_8_Firms.png" title="Concentration Ratios for Top 8 Firms">
</p>

**Concentration Ratios for the Top 8 Neighborhoods in the New York Pet Care Industry**
* CR4 of top four neighborhoods of 30.6%
* CR8 of top eight neighborhoods of 49.9%
* HHI of 448 out of 10,000 (high competition)

<p align="center">
  <img src="/img/06_Concentration_Ratios_for_Top_8_Neighborhoods.png" title="Concentration Ratios for Top 8 Neighborhoods">
</p>

**First 10 of 121,713 New York Licensed Dogs from 2014–2022, NYC Open Data**<br>
<p align="center">
  <img src="/img/07_First_10_Licensed_Dogs.png" title="First 10 Licensed Dogs">
</p>

**Market Share and Growth Rate (2014–2019) of Pet Care Industry for First 10 Neighborhoods in New York**<br>

<p align="center">
  <img src="/img/08_Market_Share_and_Growth_Rate.png" title="Market Share and Growth Rate">
</p>

## Contribute

**Contact**
* [Email](mailto:adam.c.dick@gmail.com)
* [LinkedIn](https://www.linkedin.com/in/adamcdick/)
* [Medium](https://medium.com/@adam.c.dick)
* [Scholar](https://scholar.google.com/citations?user=eMO88ogAAAAJ&hl=en)

**License**
* [MIT License](https://github.com/acdick/framing_data_with_dataframes/blob/master/LICENSE)