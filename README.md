# Project-2

Theme: Chicago Food Inspections
Visit the link: [https://food-inspection-ad.herokuapp.com/index.html]<br>

Data Source: https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5/data

Coding approach: HTML, JavaScript, Bootstrap, D3.js, chart.js, leaflet map

Details: 
The food inspection includes the facility such as restaurant, grocery, liqor store and schools.<br> 
The database we have also shows the inspection result, risk level and violation type, etc. 

Layout of the web pages:<br>
Page 1(Home page): Project title/ Description of the website/ Map with inspection of failed result for the last three years(18/19/20) with the clustering markers.<br>
Page 2: Heat map with the details similar to the map in the home page.<br>
page 3: You can enter the business name and address to get the inspecton details, pie chart, bar chart of the last three years, and a line grpah using chart.js (a new javascript library we havent learned in class) of last ten years.<br>
page 4: You can filter the business name and address to get the information of the inspection type, results and violation details.<br><br>
# Specific Requirements<br>

1. Your visualization must include a Python Flask–powered RESTful API, HTML/CSS,
JavaScript, and at least one database (SQL, MongoDB, SQLite, etc.).<br>
2. Your project should fall into one of the below four tracks:<br>
○ A custom “creative” D3.js project (i.e., a nonstandard graph or chart)<br>
○ A combination of web scraping and Leaflet or Plotly<br>
○ A dashboard page with multiple charts that update from the same data<br>
○ A “thick” server that performs multiple manipulations on data in a database prior
to visualization (must be approved)
3. Your project should include at least one JS library that we did not cover.<br>
4. Your project must be powered by a data set with at least 100 records.<br>
5. Your project must include some level of user-driven interaction (e.g., menus,
dropdowns, textboxes).<br>
6. Your final visualization should ideally include at least three views.
