# git-homework
GitHub Assignment Question 3
--
This repository contains an analysis of meterological data taken from the Met Office and Bureau of Meterology 
comparing the monthly average rainfall (1855-2015) in Melbourne and Oxford between the months Feburary and December 

To run this analysis use the following commands:
--
To create a combined csv containing data in Oxford and Melbourne run
```
Rscript scr/combine-data.R 

```
The output of the combine-data.R script is average-rainfall.csv 

To create a png graphical output illustrating these trends run

```
Rscript src/make-plot.R

```
The output of make-plot.R is result.png 

The input data is in `data` and the results are in `output`.
Information about data sources can also be found in 'data' and 'scr' contains the r scripts required to run this analysis 
