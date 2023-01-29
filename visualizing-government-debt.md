| [home page](https://maxinema5995.github.io/maxine-tswd-portfolio/) | [visualizing debt](https://maxinema5995.github.io/maxine-tswd-portfolio/visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Part 1: (OECD) General Government Debt-to-GDP Ratio in 2021
This government debt bar chart clearly shows the general government debt-to-GDP ratio in 2021 for each country. The countries are ranked by ratio. The OECD-Average ratio is shown in black. 

<iframe src="https://data.oecd.org/chart/6XY0" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6XY0" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2021</a></iframe>

# Part 2: Working with Flourish 
## (Data Visualization I) General Government Debt-to-GDP Ratio by Countries
This set of grid of line charts uses the data from 1995 to 2021 to show the general government debt-to GDP ratio for countries in the OECD. In this graph, we can see the trends for the changes of debt-to-GDP ratio for each country during these years. The countries are displayed in an alphabatical order. 

<div class="flourish-embed flourish-chart" data-src="visualisation/12579309"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## (Data Visualization II) General Government Debt-to-GDP Ratio by Countries in Year 1995-2021
Below are two graphs showing the general government debt-to-GDP ratio by countries in year 1995-2021. As what we see from the bar chart from Part 1, Japan, Greece, Italy, and the USA are the four countries which have the highest general government debt-to-GDP ratio in 2021. Hence in the following two graphs, I am focusing on analyzing these four countries by showing the trends of ratio changes for them from 1995 to 2021, and compare them with other countries in the same time period. 

### Graph I
For the first graph, pie chart is used to give the audience a sense of comparision with other countries. Black is used for Japan as it has the higest ratio in 2021, and black can be a sign of warning; blue for Greece, green for Italy, red for the USA, as those are the colors for these countries' flags. On the top there is a field to select years (1995-2021). Audiences can select different years to see the changes in the ratio comparing with other countries for these four countries. 

<div class="flourish-embed flourish-chart" data-src="visualisation/12585768"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Graph II
For the second graph, Bar chart race is used to show the values of these four countries during these years. This is a dynamic graph to see the changes by years. For other countries, blue is used as default color. For the four countries this graph wants to focus, red is used as red can be a warning color to catch audience's eyes. Audience can choose either to sort the countries from higest to lowest ratio or the lowest to higest ratio. Audience can also use the time slider below to choose certain year and see the corresponding ratio value. 

<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/12585487"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

For part I, the bar chart graph focuses on the certain year -- 2021 to show all countries' ratio value. Audiences can then make comparision among all countries in 2021. But it is impossible to see the trends from 1995 in this graph. The the grid of line focuses on displaying the trends for ratio for all the countries during these years. But it is hard to see the comparision with other countries. 
To explore the data more, it would be great to combine those two: audiences can both see the trends during the years and the comparison in certain years. 

Then I use the pie chart with time slider and the bar chart race to combine these two requirements. Since we have too many countries, it would be great to focus on some of them, like the top 4 countries having greatest ratio in 2021. By using time slider, audiences can see some increasing/decreasing during these years. And they can see the ranking and percertange among all countries. 

[Source Information](https://data.oecd.org/gga/general-government-debt.htm)

# Part 3: Working with Tableau
## General Government Debt-to-GDP Ratio Ranked by Average Ratio
<script type='module' src='https://prod-useast-a.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script><tableau-viz id='tableau-viz' src='https://prod-useast-a.online.tableau.com/t/maxinema/views/OECDdatawalkthru/GeneralGovernmentDebt-to-GDPRatioRankedbyAverageRatio' width='1198' height='635' hide-tabs toolbar='bottom' ></tableau-viz>

