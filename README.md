# D3 Playground



Here, I’ve used D3 (Data Driven Documents) to visualize a few interesting & publically available datasets. 
This work is heavily ~~stolen~~ borrowed from the [D3 source](https://d3js.org) and [Mike Bostock's Blocks](http://bl.ocks.org/mbostock).

Projects so far:
* [NYC Recycling Diversion Rate](https://github.com/tejeffers/d3-playground/blob/master/index_recycling.html)
	- Data downloaded from the NYC OpenData [Dashboard](https://nycopendata.socrata.com)
	- Data represents one month (May, 2010) of trash and recycling data
	- Plotted over 5 boroughs by Community Districts
	- Darker green indicates a greater percentage of trash was diverted to recycling (total recycling / total waste)

![Recycling_Map](https://github.com/tejeffers/d3-playground/blob/master/diversion_rates.png)

* [NYC SAT Scores by High School](https://github.com/tejeffers/d3-playground/blob/master/index_SAT.html)
	- Data downloaded from [Data.gov](https://catalog.data.gov/dataset/sat-results-e88d7)
	- Data represents the most recent school level results for New York City on the SAT
	- Records contain 2012 College-bound seniors mean SAT scores taken during SY 2012.
	- On click, circles are re-sized and re-colored to reflect average Reading, Math, or Writing SAT scores for each school
	- Darker blue, orange, or green represents higher reading, math, or writing scores, respectively


![SATscores_Map](https://github.com/tejeffers/d3-playground/blob/master/SATscores.png)