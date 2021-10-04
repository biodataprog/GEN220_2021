# Homework 1

Homework can be submitted via the github link which will create a repository for you with basic template of files you can edit to solve the homework. See the the table for homework submission links which will help you create a github repository in the class team.

[https://piazza.com/ucr/fall2021/gen220001/resources](https://piazza.com/ucr/fall2021/gen220001/resources)

1. Create a Github account using [GitHub Accounts](https://github.com)
2. Submit the homework by creating a repository through github classroom [Homework 1](https://classroom.github.com/a/ePEVSi3q)
3. Write a shell script called `count_fires.sh` which does all of the following.
   * Download a comma delimited datasets from data.gov file which are listing of fires in several decades. (hint use `curl`). 
     * [1990s](https://gis.data.cnra.ca.gov/datasets/653647b20bc74480b335e31d6d81a52f_4.csv) - [Dataset info](https://catalog.data.gov/dataset/1990s-b2103)
     * [2000s](https://gis.data.cnra.ca.gov/datasets/653647b20bc74480b335e31d6d81a52f_12.csv) - [Datset info](https://catalog.data.gov/dataset/2000s)
     * [2010s](https://gis.data.cnra.ca.gov/datasets/653647b20bc74480b335e31d6d81a52f_11.csv) - [Dataset info](https://catalog.data.gov/dataset/2010s)
   * Print out the number of fires for each decade (hint use `wc`)
   * Print out the number of fires in each year (hint use `cut` and `uniq`)
   * Print out the largest fire (hint use `sort`) - use the `GIS_ACRES` column
   * Print out the total acerage burned in each year.
