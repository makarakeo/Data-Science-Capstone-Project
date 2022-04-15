# Data-Science-Capstone-Project
This Capstone is the 10th (final) course in [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) specialization, and it actually summarizes in the form of project all materials that have been learned during this specialization.
## Project Background
SpaceX is the most successful commercial space enterprise, making space travel accessible to the general public. On its website, the business promotes Falcon 9 rocket flights for 62 million dollars; other suppliers charge upwards of 165 million dollars per launch; much of the savings comes from the fact that SpaceX can reuse the first stage. As a result, if we can figure out if the first stage will land, we can figure out how much a launch will cost. We'll make a prediction based on public data and machine learning models about whether SpaceX will reuse the first stage. 
## Questions to be answered 
- How do factors like payload mass, launch site, number of flights, and orbits influence the first stage landing's success? 
- Does the percentage of successful landings rise over time? 
- What is the best binary classification algorithm that may be applied in this case?
## Methodology
  ### 1. Data collection methodology
  - Using SpaceX Rest API
  - Using Web Scrapping from Wikipedia
  ### 2. Performed data wrangling
  - Filtering the data
  - Dealing with missing values
  - Using One Hot Encoding to prepare the data to a binary classification
  ### 3. Performed exploratory data analysis (EDA) using visualization and SQL
  ### 4. Performed interactive visual analytics using Folium and Plotly Dash
  ### 5. Performed predictive analysis using classification models
  - Building, tuning and evaluation of classification models to ensure the best
  results
## Data Collection
Data collection process involved a combination of API requests from SpaceX REST API and Web Scraping data from a table in SpaceX’s Wikipedia entry.
We had to use both data collection methods in order to get complete information about the launches for a more detailed analysis. 
- Data Columns are obtained by using SpaceX REST API: 
  FlightNumber, Date, BoosterVersion, PayloadMass, Orbit, LaunchSite, Outcome,   Flights, GridFins, Reused, Legs, LandingPad, Block, ReusedCount, Serial,   Longitude, Latitude 
- Data Columns are obtained by using Wikipedia Web Scraping: 
  Flight No., Launch site, Payload, PayloadMass, Orbit, Customer, Launch   outcome, Version Booster, Booster landing, Date, Time
## Conclusion
- The Decision Tree Model is the best algorithm for this dataset. 
- Launches with a low payload mass show better results  than launches with a larger payload mass. 
- Most of the launch sites are in proximity to the Equator line and all the sites are in very close proximity to the coast. 
- The success rate of launches increased over the years. 
- KSC LC-39A has the highest success rate of launches  from all the sites. 
- Orbits ES-L1, GEO, HEO, and SSO have a 100% success rate. 
