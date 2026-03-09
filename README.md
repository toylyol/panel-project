# Patient Panel Dashboard | A Portfolio Project
I have not added a new project to my portfolio site in a while, so I am starting a patient panel dashboard project. This is a popular way for health organizations to track general trends for a cohort of patients living with a particular chronic condition—despite my personal feelings about dashboards (and that very real risk of fatigue!)[^1].

## Objectives
* Update my portfolio site with a realistic project.
* Apply lessons learned from [Julia Silge's recent R-Ladies presentation](https://www.meetup.com/rladies-abuja/events/312978180/) re: working with larger-than-memory data from your laptop (without the benefit of a enterprise-level cloud platform like Databricks).
* Test [dashboard functionality in Quarto](https://quarto.org/docs/dashboards/).
* Explore [synthetic Medicare data](https://data.cms.gov/collection/synthetic-medicare-enrollment-fee-for-service-claims-and-prescription-drug-event) that is supposed to mirror what is found in the Chronic Conditions Warehouse.
* Find a way to incorporate some of my favorite data visualizations.
* Add some interactivity without needing a Shiny server.

## Plan
Normally, I keep a rough outline of the final data product in my head. This time, I sketched out a basic wireframe:

![This is a low-fidelity wireframe for a patient panel dashboard portfolio project. It featues a title ("T2DM Patient Panel | Physical Activity") and three buttons in the navbar. There is a note indicating that the three buttons will link to the homepage, a page with geographic data, and the source code (in that order). Under the navbar, the dashboard is divided into two columns. The left column has three items: a card with percent of panel exercising at least three days a week, a beesward plot, and a diverging bar chart. There are notes with arrows noting that the beeswarm plot will show HbA1c while the diverging bar chart will show self-management survey scores. The right column has a grayed out box with a map icon. There is a note explaining this will be an interactive choropleth map displaying walk score data. Finally, the note credits Flaticon.com for the map icon.](patient-panel-project-wireframe.svg)

Once I actually get a good look at the (fake) data, I may rearrange the left-hand side of the dashboard to improve the flow. 

[^1]: I refuse to give up em-dashes because they are now associated with AI-generated content. I used them first! Em-dashes, like Oxford commas, will only be pried for my lifeless fingers. Blame it on too many Victorian novels in my formative years😂.
