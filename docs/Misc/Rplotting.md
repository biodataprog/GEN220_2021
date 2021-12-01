# Plotting and Data viz with R

# Data visualization

good guide includes Claus Wilke's [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/index.html) and [associated code](https://github.com/clauswilke/dataviz)

# Reading in data

```R
library(dplyr)
library(tidyverse)

tblr <- read.csv("data.csv",sep=",")

hist(tblr$V1)

```

# tidyverse

Data framework in R called [tidyverse](https://www.tidyverse.org/).

In particular visualizing data with [ggplot](https://ggplot2.tidyverse.org/)

# data loading

Using [readr](https://readr.tidyverse.org/)

# data filtering

Using [dplyr](https://dplyr.tidyverse.org/)
