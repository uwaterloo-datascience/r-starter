# Summary Sheet

Data analysis is important for any type of role as a data scientist. 
R is an open source language built around data analysis. Equiped 
with the right libraries in the Tidyverse, R is an incredibly productive 
tool do transform and explore data. 

## Tidy Data:

Tidy data is a standard way of mapping the meaning of a dataset to its structure. A dataset is messy or tidy depending on how rows, columns and tables are matched up with observations, variables and types. In tidy data:

* Each variable forms a column.
* Each observation forms a row.
* Each type of observational unit forms a table.
* A single observational unit is stored in multiple tables.

The library we need to make data tidy is in `tidyr` which provides:

* `seperate`
* `gather`
* `union`
* `spread`

## Data Transformation

dplyr is a powerful R-package to transform and summarize tabular data with rows and columns.
which provides:

-   `select()`: select columns
-   `filter()`: filter rows
-   `arrange()`: re-order or arrange rows
-   `mutate()`: create new columns
-   `summarise()`: summarise values
-   `group_by()`: allows for group operations in the “split-apply-combine” concept

aside: the pipe operator, `%>%`. dplyr imports this operator from another package (magrittr). This operator allows you to pipe the output from one function to the input of another function. Instead of nesting functions (reading from the inside to the outside), the idea of of piping is to read the functions from left to right.

## Data Visualization

ggplot2 is one of the most elegant and most versatile. ggplot2 implements the grammar of graphics, a coherent system for describing and building graphs.

Ggplot provides a way to visualize data by providing:

- `ggplot`
- `aes(...)`
- `geom_*`
- `facet_*`
- `scale_*`


