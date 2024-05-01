# NSIR-interact-with-databases

Taught by John Lee Spring Quarter of 2024 Northwestern University's Research Computing and Data Services as part of the [Next Steps in R](https://github.com/nuitrcs/Next-steps-in-R) workshop series.

## Getting Started

-   Download the materials to your machine by clicking on the green "Code" button on the top right and selecting "Download ZIP".
-   Unzip the downloaded folder, and double-click on the .RProj file to open up the R Project in RStudio.
-   Open `interact-with-databases.Rmd` and work through the materials.

## Concepts

- Connect to a databse with `DBI`
- Extract data from the database using `dplyr` syntax

## Components

- README.md markdown file outlining the repository
- `interact-with-databases` RMD file with the workshop materials
- `data/sqlite-sakila.db` file
  - original Sakila Sample database is originally developed by a member of MySQL AB documentation team for training and use in examples. You can learn more about it [here](https://dev.mysql.com/doc/sakila/en/)
  - `sqlite-sakila.db` file is a ported version from MySQL to other database systems, which is available as a part of the sakila-sample-database-ports project. The data was downloaded from [Kaggle](https://www.kaggle.com/datasets/atanaskanev/sqlite-sakila-sample-database?resource=download)

## Required Installs

- R and RStudio
- Packages: `tidyverse`, `DBI`, `RSQLite`

```
install.packages("tidyverse")
install.packages("DBI")
install.packages("RSQLite")
```

