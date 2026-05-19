# Data Visualization Challenge "Powering the Future: Visualizing Electric Vehicle Trends in Washington State"

This is the data dashboard challenge for the Spring 2025 BIS 412 Advanced Data Visualization course at the University of Washington Bothell. The challenge explores electric vehicle data from Washington State to visualizethe spread and growth of electric vehicle adoption across Washington State.


# Overview

Challenge created by and made for the Spring 2025 BIS 412 Advanced Data Visualization course at the University of Washington Bothell.

- 📊 Challenge created by and made for the Spring 2025 BIS 412 Advanced Data Visualization course at the University of Washington Bothell.
- ✍️ Authored by Team "Cool Name":
    - Amrit Kaur [@amrit-29](https://github.com/amrit-29)
    - Axel Madsen [@axemadsen](https://github.com/axemadsen)
    - Gabriela Marroquin [@gabsml48](https://github.com/gabsml48)
- 🛠️ Edited and supervised by Prof. Gani Nurmukhametov [@gani-nurmukhametov](https://github.com/gani-nurmukhametov)


# Description

The central challenge this dashboard seeks to address is: How can data-driven visualizations help us understand the spread and growth of electric vehicle adoption across Washington State?
As the state pursues ambitious environmental goals, such as reducing greenhouse gas emissions and transitioning to clean energy transportation, understanding where and how electric vehicles are adopted is essential. This dashboard aims to transform raw registration data into accessible, interactive insights that support strategic decisions in policy, business, infrastructure, and research.
The purpose of this dashboard is twofold: to inform and to explore. For stakeholders such as policymakers, transportation planners, and advocacy groups, it provides clear visuals that summarize EV distribution trends and give insights on growth trajectories. For researchers, businesses, and community members, it offers tools for exploring the data through simpler visualizations.
The resulting data visualization dashboard’s goal is to inform and empower multiple stakeholder groups. Transportation departments can use insights to prioritize infrastructure deployment, such as new charging stations in underserved areas. Researchers can apply the findings to measure the effectiveness of policy interventions, while clean energy advocates can use the visual narratives to communicate progress and identify equity concerns in green technology adoption.


# Challenge

Create a dashboard that examines the various aspects of electric vehicle (EV) adoption across Washington State. As such, the dashboard should include the following 4 data visualization charts:
- Chart that analyzes the most common patterns in the overall population of EVs in Washington State: the most popular makes & models, the share of the EVs of different types (Battery EVs vs Plug-in Hybrid EVs), the distribution of production years of EVs etc.
- Chart that analyzes the time series aspect of EV adoption in Washington State, either aggregated at the state level or disaggregated at the county level: the change (increase) in number of EVs across time, both in absolute levels and in percentages relative to the previous time period (month/quarter/year).
- Chart that analyzes the geographical aspect of EV adoption in Washington State: comparative analysis of the counties with highest and lowest numbers of EVs, both in absolute levels and as a share of EVs in total vehicles. Extra challenge: use geospatial data infrastructure to make this chart even more visually appealing by plotting your findings on a map of Washington State.
- Chart that is uniquely developed by each team independently. Feel free to search for another datasets publicly available for Washington State to use it when creating this uniquely determined chart.

In addition to the 4 charts listed above, the dashboard should also include an "About" section that mentions the name of the challenge, names of the dashboard creators (team name and students' names), and the hyperlink to the team GitHub repository of the dashboard. The team is required to complete the Dashboard Report .Rmd file that is provided in the repository with the information relevant to the team's dashboard: 
- documentation of the statistical analysis performed by team
- list of roles and responsibilities (including who has been the primary creator of each chart - each team member is expected to be responsible for at least a single chart)
- summary of key achievements and main challenges team faced when creating the dashboard,
- references list with citations (following APA format) on data sources and any literature used.
  
After you complete this Dashboard Report R Markdown file, knit it as .html file, and push both .Rmd and .html files onto your team repository. Push the Markdown file(s) with your code used when creating a dashboard onto your repository as well.


# Proposed Project Plan

The project will span 3-4 weeks with the following phases and tasks:

1. Data Exploration & Design Ideation
-	Data Import
  -	Import the Electric Vehicle Population Data from the Washgington State
  - Clean the pre-processing of the data
- Initial Sketch
  - Define project scope and objectives
  - Brainstorm and sketch initial dashboard layouts
- Meetings:
  -	Discuss roles and responsibilities and set communication channels among team members.
2. Data Analysis and Design
  -	Perform exploratory data analysis
  -	Identify key metrics and trends
  -	Determine which visualizations best address the purpose
3. Dashboard Build & Development
  - Integrate the refined visualizations into an interactive dashboard framework. 
  - Develop interactive filtering and drill-down capabilities.
  - User Interface & Aesthetics:
  - Focus on the dashboard's overall layout, color schemes, and responsiveness.
  - Incorporate the sidebar with filtering options and a dynamic header.     
4. Testing, Feedback, and Deployment
- Conduct usability testing and gather feedback:
    - Share the dashboard with a small group of target users (stakeholders, peers) to collect feedback on usability and insights.
    - Identify and fix any bugs or usability issues.
- Final Adjustments & Deployment:
    - Finalize the dashboard design, ensuring all visualizations and interactive elements work as intended.
    - Deploy the dashboard on a hosting platform and ensure the live data connection functions.
- Documentation & Final Presentation:
    - Document the design process, coding decisions, and any challenges faced.
    - Prepare a final presentation outlining the project’s insights and outcomes.


# Possible Team Roles

-	Everyone: Develops one original graphic data visualization
-	Project Manager: Oversees the timeline, coordinates team activities, and ensures objectives are met.
-	Data Analyst/Engineer: Handles data cleaning, analysis, and interpretation.
-	UX/UI Designer: Designs the dashboard interface for optimal user experience.
-	Visualization Specialist: Supports static and interactive visualizations.


# Datasets

All the datasets are obtained from Data.Gov portal, [the home of the U.S. Government's Open Data](https://data.gov/), searching for key word "electric and applying filter for Washington state. [This search](https://catalog.data.gov/organization/state-of-washington?q=electric) resulted in five found datasets, and I have included three of them for your perusal:

1. [Electric Vehichle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data): This dataset shows the Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) that are currently registered through Washington State Department of Licensing.
2. [Electric Vehichle Population Size History](https://catalog.data.gov/dataset/electric-vehicle-population-size-history): This dataset shows the number of electric vehicles that were registered by Washington State Department of Licensing each month. The data is separated by county for passenger vehicles and trucks.
3. [Electric Vehichle Population Size History by County](https://catalog.data.gov/dataset/electric-vehicle-population-size-history-by-county): This dataset shows the number of electric vehicles that were registered by Washington State Department of Licensing each month disaggregated on a country level. The data is separated by county for passenger vehicles and trucks. The original dataset includes other U.S. states as well, for your convience, I created a separate subset of this dataset including only the data for Washington state counties. 

The data for all three datasets has been updated on May 17, 2025, so it is very up-to-date. The size of the first dataset exceeds the allowed limit for the files stored at UW GitHub repositories (25 Megabytes), so I created a zip archive with these four .csv spreadsheets.

I expect you to use each of these three datasets when creating different charts, so you will need to provide a correct citation for the datasets you used in your Dashboard Report R Markdown file. 
