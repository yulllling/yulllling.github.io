# IS445 Homework 8

## Chart 1: Number of Licenses by Beauty Profession

This chart shows the number of licenses for different beauty professions in Illinois. The x-axis shows the number of licenses, and the y-axis shows the professions. I use blue bars to make the chart simple and clear. I grouped the data by profession and counted the licenses in each group. I also sorted the results from highest to lowest.

<div id="chart1"></div>

## Chart 2: License Status by Beauty Profession

This chart shows the license status of different beauty professions. The x-axis shows the professions, and the y-axis shows the number of licenses. I use different colors for different license statuses. I grouped the data by profession and license status. Users can click the legend to highlight different license statuses and compare the results.

<div id="chart2"></div>

## Data

[The Data](https://github.com/UIUC-iSchool-DataViz/is445_data/blob/main/licenses_fall2022.csv)

## Analysis

Notebook link will be added here.

<script src="https://cdn.jsdelivr.net/npm/vega@5"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-lite@5"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-embed@6"></script>

<script>
vegaEmbed("#chart1", "/HW5.2/assets/chart1.json");
vegaEmbed("#chart2", "/HW5.2/assets/chart2.json");
</script>
