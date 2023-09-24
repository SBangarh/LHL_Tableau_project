# Final-Project-Tableau

## Project/Goals
1. My overall goal is to use Tableau and wildlife collision data from the FAA to understand the impact of damage caused by wildlife.
2. I will attempt to develop different visualizations to communicate my question(s) or topic of interest
3. I want to practice committing for frequently
4. I want to attempt to tell a story with my data analysis using Tableau specifically (I can come back in the future and use Python)
5. Have fun

## Process
I chose my data set - FAA Wildlife collisions
I loaded the data into Tableau
I performed some EDA (limited to Tableau) to better understand the data and identify any trends, outliers, or eye catchers
Once I gained a better understanding of the data, I started to synthesize questions that I could answer with the data (found in the results section)
I made dashboards from the visuals to answer a main question, but added interactivity such that the user could explore other scenarios
I saved the Tableau worksheet and used the figures in presentation. 

## Results
(Fill in which Option you chose, either 1 or 2. List the dataset you selected for the project if you selected Option 2. Also, discuss the visualizations you created, and why. For Option 2, also identify what your data question was, and how you went through the prompts.)

I chose option 2 and the FAA Wildlife Strikes data.

My analysis indicated that over 95% of collisions were due to birds and the majority of collisions did not cause damage. I also found that the number of collisions with wildlife have increased year over year and there is no apparant trend in cost. Furthermore, the majority of collisiosn occur in California, Texas, Florida, and New York. The majority of collision with birds occur in Q3 which indicates seasonality - perhaps migration. The number of collisions is expected to increase, the average cost - monetary - is expected to decrease, but there is uncertainty over the days out of service. In sum, the airline industry should care because the number of collisions is going to increase, and while the average monetary cost is expected to decrease, the historic trends for both costs - monetary and days out of service - are chaotic which makes risk management more difficult. 

My overall question was, "Why care about wildlife strikes?," and then I developed some more as I analyzed the data.
My inital analysis indicated that the majority of collisions were from birds, and I decided to further bird collisions in the data.
My data question(s) were the following:
    Dashboard 1 - Overview
        What is the composition of all collisions with respect to damage and animal categories?
        Is there a pattern to cost - monetary and days out of service for collisions?
        Where are the collisions - total collisions - occurring on a state level and over time?
    Dashboard 2 - Birds
        For birds specifically, what was the composition for amount of damage and time of day in which the collisions occurred?
        Which species resulted in the most hits and what was the average height of the collision per species?
        What is the forecast for bird collisions over the next 6 years?
        Is there a seasonality for collisions?
    Dashboard 3 - Cost
        What is the average cost - monetary and days out of service - for each bird species over time and by state? Is there a pattern in costs?
    Dashboard 4 - Forecast
        What are the forecasts for total collisions over time and average cost - monetary and days out of service - for the amount of damage and time of day.  

The first dashboard was an overview and its purpose was to show the breakdown of collisions, the breakdown of wildlife, the strikes by location, total cost($ and days out of service), and the total collisions YTD. I used a treemap as I thought it gave a better visual breakdown between the two possible categories. I used a table to show wildlife composition as it wasn't that relevent to my analysis and the information was relatively simple. It also provided a method for the user to explore different animal categories. I used a map to communicate the states as it was more concise than the other possibilities. I used line graphs to illustrate trends over time as it could communicate an up, down, or other trend.

For the second dashboard visuals, I used a bar graph to communicate the percent of bird collisions segregated by the damage amount and time of day as their were multiple categories and it would be easier to see the height difference as opposed to a complicated table. I used a line graph to forecast the number of collisions as it was easier to communicate a trend than other visuals. I also used a line graph to illustrate seasonality of collisions trends. I used a highlighted table to show the total number of collisions per bird species and a bar graph to illustrate the average height of the collisions.

For the third dashboard, I used maps with clusters to communicate the average cost - monetary and days out of service - as it was easier and more concise to communicate data for 48 states this way. I also used a line graph to communicate the cost trends over time. I used a highlighted table to show total collisions and percentage of collisions per bird species. 

In the forth dashboard, I used line graphs to forecast collisions and average cost - monetary and days out of service. I also used a bar graph to communicate collisions based on time of day and amount of damage. 

## Challenges 
The ambiguity when determining your own questions. There are so many rabbit holes to go down, but not all are relevent. Tableau was relatively easy to learn and use, but I didn't really feel engaged with the software throughout the two weeks. I struggled with defining my own questions, I redefined my questions a lot too which, in theory, is good, but when combined with the rabbit holes I did become distracted. I think if I used Tableau in my tech stack for a project it would have been better as I could have better explored the data and relationships in python, then visualized them in Tableau.
I also procrastinated for some reason, perhaps I didn't have a proper plan. I will have to analyze my approach once feedback is given. 

## Future Goals
My overall goal is to use Tableau in combination with another tool for a project as opposed to itself.
I would like to develop a general plan to utilize when analyzing data that I struggle with. 

