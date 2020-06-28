# Covid-19 India Cases Per Million Visualization
## Covid-19 Cases per million visualization

This notebook is a work towards creating a visualization of number of cases per million in top 7 seven states in India in terms of number of comfirmed cases.

## Libraries Used:
1. pandas
2. numpy
3. requests
4. datetime
5. matplotlib
6. random

## Steps undertaken:
1. Scraped html table from [wikipedia](https://en.wikipedia.org/wiki/List_of_states_and_union_territories_of_India_by_population) on indian statewise population.
2. Got data on cases timeseries from the [covid19india.org](http://api.covid19india.org/) API.
3. Data exploration and cleaning for both data from Wikipedia and covid19india.org.
4. A small analysis to smoothen the curves and do some calculated fields.
5. Visualized top seven states(Pareto, 80/20 rule), using matplotlib.

## Final result
![image info](https://github.com/hisham2k9/covid_cpm_india/blob/master/cpm.png?raw=true)
