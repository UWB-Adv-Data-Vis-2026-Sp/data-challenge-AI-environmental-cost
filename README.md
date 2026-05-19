# Data Visualization Challenge "Beyond the Algorithm: Visualizing the Environmental Cost of AI"

This is the data dashboard challenge for the Spring 2026 BDATA 412 Advanced Data Visualization course at the University of Washington Bothell. The challenge explores the environmental impact of artificial intelligence tools in the various dimensions (energy, heat, water).


# Overview

Challenge created by and made for the Spring 2026 BDATA 412 Advanced Data Visualization course at the University of Washington Bothell.

- 📊 Challenge created by and made for the Spring 2026 BDATA 412 Advanced Data Visualization course at the University of Washington Bothell.
- ✍️ Authored by Team 1:
    - Dhanshika Vijayaraj [@dhanshika-v](https://github.com/dhanshika-v)
    - Sumit Patel [@SumitUW](https://github.com/SumitUW)
    - Ethan Morris [@EthanMors](https://github.com/EthanMors)
- 🛠️ Edited and supervised by Prof. Gani Nurmukhametov [@gani-nurmukhametov](https://github.com/gani-nurmukhametov)


# Description: From Team 1's proposal

Every time someone uses an AI tool, there's a physical cost most people don't think about. Running a large language model requires electricity, and cooling the servers that power it requires water. At small scale that's not a big deal, but AI has scaled up fast. This dashboard challenge asks teams to visualize the environmental footprint of AI and data centers across three dimensions: energy consumption, water usage, and carbon emissions. The goal is to make something usually abstract and technical feel concrete and understandable. The central question driving this challenge: how big is AI's environmental impact, and how does it compare to things we already have a sense of scale for?

This is primarily an informational and analytical dashboard. The data should tell a story, but users should also be able to explore it on their own and form their own conclusions. A few questions that shape the intent:
- Why does this matter? Because data centers are being built right now at a record pace, and the public rarely gets a clear picture of what that means environmentally.
- Is there a claim worth investigating? Some argue AI companies are overstating their sustainability commitments while underreporting actual consumption. The data can help test that.
- Are there trends to show? Yes. Energy use from data centers has been climbing steadily, and projections suggest the growth is accelerating as AI workloads increase.
- Do we want one interpretation or many? Multiple. The data is genuinely uncertain in places, and the dashboard should reflect that rather than hide it.

The most realistic audience for a class dashboard is curious students and instructors who want to engage with a current policy debate backed by real data. Beyond that, this type of visualization would be useful for environmental policy researchers, journalists covering tech and climate, and people inside tech companies who work on sustainability reporting. Anyone trying to evaluate whether AI companies' green pledges hold up against their actual resource use would find value in it.

Teams working on this challenge should try to address the following through their visualizations:
- How has data center energy consumption changed over time in the U.S. and globally?
- How does AI's electricity use compare to other energy-intensive industries like steel, aluminum, and aviation?
- How much water do data centers use for cooling, and how does that vary by region?
- What are the estimated carbon emissions tied to AI workloads, and how do they compare to other familiar sources?
- How much transparency do major tech companies actually provide in their sustainability reports, and do the numbers add up?


# Challenge

Create a dashboard that examines the various aspects of the environmental impact of artificial intelligence tools. As such, the dashboard should include the following 4 data visualization charts:
- Chart that analyzes the time series aspect of increasing AI tools usage in the past decade (subject to the data available), either aggregated at the country level using the world data or disaggregated at the state level of the United States across time, both in absolute levels and in percentages relative to the previous time period (month/quarter/year). Proposed variables: energy usage, water usage, increased carbon emissions etc.
- Chart that compares the environmental impact of data centers against the impact of traditional industries like steel manufacturing, aviation, oil and petrochemistry etc.
- Chart that examines the geographical aspect of increasing AI tools usage in the past decade, either aggregated at the country level using the world data or disaggregated at the state level of the United States. Extra challenge: use geospatial data infrastructure to make this chart even more visually appealing by plotting your findings on either the world map or the U.S. map.
- Chart that is uniquely developed by each team independently. Feel free to augment your research project with another publicly available datasets when creating this uniquely determined chart.

In addition to the 4 charts listed above, the dashboard should also include an "About" section that mentions the name of the challenge, names of the dashboard creators (team name and students' names), and the hyperlink to the team GitHub repository of the dashboard. The team is required to complete the Dashboard Report .Rmd file that is provided in the repository with the information relevant to the team's dashboard: 
- documentation of the statistical analysis performed by team
- list of roles and responsibilities (including who has been the primary creator of each chart - each team member is expected to be responsible for at least a single chart)
- summary of key achievements and main challenges team faced when creating the dashboard,
- references list with citations (following APA format) on data sources and any literature used.
  
After you complete this Dashboard Report R Markdown file, knit it as .html file, and push both .Rmd and .html files onto your team repository. Push the Markdown file(s) with your code used when creating a dashboard onto your repository as well.


# Proposed Project Plan

The project will span 3-4 weeks with the following phases and tasks:

1. Design
- Tasks
  -	Download EIA CSV and Our World in Data energy files.
  -	Look through the Kaggle data center dataset to see what columns are actually usable.
  -	Sketch two or three dashboard layout ideas.
  -	Assign roles.
  -	Do a first pass at loading data into R and checking for problems.
- Deliverables
  - Sketches
  - Data loaded in R
2. Prototype
- Tasks
  -	Clean and reshape data:
      - standardize units (convert everything to TWh),
      - handle missing years,
      - join datasets where needed.
   - Build a first draft line chart of U.S. and global data center energy use over time.
   - Make a rough summary table.
- Deliverables
  - Working rough visualization.
3. Build
- Tasks
  -	Refine the line chart.
  -	Add a second visual comparing AI energy or water use to other industries.
  -	Add explanatory text and source notes.
  -	Start thinking about how the dashboard layout reads as a whole.
- Deliverables
  - Near-final dashboard draft. 
4. Deploy
- Tasks
  -	Share with a few classmates for feedback.
  -	Revise based on what they find confusing.
  -	Polish labels, color, and theme.
  -	Host on shinyapps.io.
  -	Final check on all citations and data source notes.
- Deliverables
  - Live hosted dashboard. 


# Possible Team Roles

-	Everyone: Develops one original graphic data visualization
-	Data Wrangler: downloads and cleans the datasets. Main job is getting the EIA and Our World in Data files into a format R can actually work with -- standardizing units, handling gaps, joining tables. Also responsible for documenting what was changed and why.
-	Visualization Lead: owns the ggplot code. Handles the main chart designs, picks colors and themes, and makes sure the visuals are actually readable by someone who didn't build them.
-	Writer/Analyst: writes the contextual text that sits alongside the visuals. Explains what the data shows, flags limitations, and handles citation formatting for the references page.
-	Deployment Lead: gets the dashboard live on shinyapps.io or a similar platform. Coordinates the feedback round in week four and manages final revisions.


# Datasets

Datasets available in the archived zip folder. The exact description to be updated.

