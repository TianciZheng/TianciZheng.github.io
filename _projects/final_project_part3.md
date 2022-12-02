---
name: IS 445 - Final Project Part3 - Group 66
tools: [Python, HTML, vega-lite, Jekyll]
image: assets/pngs/inc5000.png
description: This is the  part 3 of the IS 445 final project created by Group 66
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---
![](/assets/pngs/inc50002019.png)
# <center> The Stories Behind The Fastest 5000 Growing Companies in The U.S.</center>
<br/>

#### <center> Group 66 - Tianci Zheng, Yiqing Li </center>
<br/>
<br/>

## 1. Introduction
Our main dataset is about [Inc.com'5000 fastest growing private companies in 2019](https://data.world/aurielle/inc-5000-2019).
<br/>

## 2. One Central Interactive Dashboard Visualization
<vegachart schema-url="{{ site.baseurl }}/assets/json/final_dashboard_1.json" style="width: 100%"></vegachart>
<center>Fig 1: Central Interactive Dashboard</center>
<br/>

The dashboard aims to provide descriptive information about the 5,000 fastest-growing private companies regarding their industry, locations, revenue, and the lengths they have been awarded to this honor in 2019. Specifically, the left graph, which is a heatmap grid, plots out the states that companies locate and their related industries. Viewing the chart horizontally helps people understand the density of different business types per state. On the other hand, looking at the grid vertically can find the distribution of various industries in the United States. As for the right bar chart, the x-axis is the years that companies are on the Inc 5000 lists, and the y-axis is an aggregate measure of the average revenue. The chart depicts potential relationships between two variables and the number of money companies can earn. Moreover, looking at them holistically as the dashboard allows people to use the left grid as a filter to select specific industries or geographic locations so as to see their performances.

## 3.Contextual Visualizations
<br/>

### 3.1 Total revenue by industry

One direction we focused on is the total revenue. The treemap(fig 2) is created by Gautam Anand<sup>(1)<sup>

![](/assets/pngs/industryandrevenue.png)
<center>Fig 2: Total Revenue by Industry in 2014</center>
<br/>

<vegachart schema-url="{{ site.baseurl }}/assets/json/contextual_1.json" style="width: 100%"></vegachart>
<center>Fig 3: Total Revenue by Industry in 2019</center>
<br/>
### 3.2 Average Employee
<center><vegachart schema-url="{{ site.baseurl }}/assets/json/contextual_2.json" style="width: 100%"></vegachart></center>
<center>Fig 4: Average Employee Amount for Companies founded within 30 years </center>

## 4.Conclusion
Test

## 5. Citation
1. Anand, G. (2017, January 10). INC. 5000 Companies. Tableau Public. https://public.tableau.com/app/profile/gautam1546/viz/INC_5000Companies/INC_5000CompaniesandRevenue



<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/TianciZheng/TianciZheng.github.io/main/cleaned_inc5000-2019.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>

