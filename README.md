# H1B-Requests-Data-Visualization


**[Tableau Dashboard URL](https://public.tableau.com/profile/chen.ma#!/vizhome/H-1BRequestSummary-backup/Dashboard1)**

Each year, employers submit requests for H1B nonimmigrant workers to U.S. Department of Labor Employment and Training Administration Office. The requests data are publicly disclosed, including information on employer location, prevailing wage, job title etc. 

Built upon H1B request data, this dashboard is created for international employees seeking a job in the U.S. as software engineer, data scientist, data analyst and business analyst. Consumers of this dashboard can use it to support job decision in terms of target state, city and job title. 

**Design** I started with thinking about the needs and expectations of target users(myself included) and how they can benefit from H-1B data. Narrowing down the topics to where to work and how much is the pay, the intuitive visualizing format is maps for location and scatter plot for pay information. Assuming that target users have basic statistics knowledge, a regression line is drawn on scatter plot to see dynamic trend and a boxplot is provided to see the variance of pay. 

In terms of interaction, two global filterings(Job Group and Year) are provided at left top. It is also intuitive to click on the map and view specific information on other charts about the selected state.

**Experience** Tableau is similar to Excel pivot table at first glance. But as I use it more, the intuitive interaction design make it easy to explore with data and identify trends and insights. The most impressing design is the “Marks” function, where users can easily manipulate with colors, sizes and labels. The interactive feature of Tableau’s charts is also amazing. Users can easily highlight and group, exclude outliers, and drill-down to raw data.

**Challenges** I’ve also came across challenges with Tableau. Data processing is not easy compared with Excel and other programing languages. When connecting to large dataset in online database like Bigquery, refreshing speed depends on the Internet connection and it can be very frustrating because Tableau updates the chart every time a new variable is added to columns or rows.

In sum, Tableau is a great tool to explore data for individual users and a powerful business intelligence tool to incorporate multiple database, and design shared interactive dashboards across organization.
