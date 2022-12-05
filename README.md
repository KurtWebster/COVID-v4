# CovidWebsite-py
The purpose of this website was to provide better insight into COVID statistics. Government updates would show absolute figures, whereas proportionate figures are more relevant. E.g. reporting that the US has more positive cases than the UK is not helpful, considering the US also has more citizens than the UK. It is more logical to compare countries and regions by the percentage of population testing positive.

## Description

1. At the top of the website there is an option to view positive COVID tests or COVID deaths.
2. The World map indicates the number of cases / deaths as a proportion of each country's population on a given day. The larger the bubble, the more cases in proportion to the population size. Hovering over a bubble will provide more detail. A slider is available at the bottom to move through time. Further options are available on the right to zoom, save image, reset, etc.
3. The UK map works in the same way as the World map, but shows cases as a proportion of the population for UK counties.
4. The table contains simple data at a regional level.
5. The charts show 6 useful UK wide daily metrics: total cases, total tests taken, proportion of tests that returned positive, number of hospital admissions from COVID, number of hospital beds taken by COVID patients, number of mechanically ventilated beds taken by COVID patients.

## Getting Started

### Dependencies
* Python 3.10.1, with the following Python packages
  * Flask
  * Pandas
  * Numpy
  * Requests
  * Datetime
  * Bokeh
 
 ### Data Sources
 * https://api.coronavirus.data.gov.uk/v2
 * https://raw.githubusercontent.com/owid/covid-19-data/master/public/data/owid-covid-data.csv
 * http://a.basemaps.cartocdn.com
