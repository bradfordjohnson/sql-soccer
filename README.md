# `SQL` Soccer
*Exploring a 7 table soccer database; features data from 5 professional leagues during 2014-2020*

## Objectives
- Import tables into local `postgreSQL` database
- Create and execute queries to extract insights
- Use `R` to create insightful visuals

## Queries
### Query 1
- Get stats for top 100 goal scorers during their games over 2014-2020
<img src="sql/01-sql.png" width ="90%">

### Query 2
- Get stats for all players with "Tour" as within their last or middle name
<img src="sql/02-sql.png" width ="90%">

### Query 3
- Get season stats for each team in the EPL, exclude match outcome
<img src="sql/03-sql.png" width ="90%">

### Query 4
- Get the play and shot data for each shot taken in the EPL
<img src="sql/04-sql.png" width ="90%">

### Query 5
- Get the shot data for every shot taken with league name
<img src="sql/05-sql.png" width ="90%">

## Citations
### Data Source
- [Kaggle](https://www.kaggle.com/datasets/technika148/football-database?select=leagues.csv)
### `R` Packages
|             |                                                                                                                                                                                                                                                                                                                                                                 |
|-------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `DBI`       | R Special Interest Group on Databases (R-SIG-DB), Wickham H, Müller K (2022). DBI: R Database Interface. https://dbi.r-dbi.org, https://github.com/r-dbi/DBI.                                                                                                                                                                                                   |
| `ggsoccer`  | Torvaney B (2023). ggsoccer: Plot Soccer Event Data. https://torvaney.github.io/ggsoccer/, https://github.com/Torvaney/ggsoccer.                                                                                                                                                                                                                                |
| `janitor`   | Firke S (2023). janitor: Simple Tools for Examining and Cleaning Dirty Data. https://github.com/sfirke/janitor, https://sfirke.github.io/janitor/.                                                                                                                                                                                                              |
| `tidyverse` | Wickham H, Averick M, Bryan J, Chang W, McGowan LD, François R, Grolemund G, Hayes A, Henry L, Hester J, Kuhn M, Pedersen TL, Miller E, Bache SM, Müller K, Ooms J, Robinson D, Seidel DP, Spinu V, Takahashi K, Vaughan D, Wilke C, Woo K, Yutani H (2019). “Welcome to the tidyverse.” Journal of Open Source Software, 4(43), 1686. doi:10.21105/joss.01686. |
| `RPostgres` | Wickham H, Ooms J, Müller K (2023). RPostgres: Rcpp Interface to PostgreSQL. https://rpostgres.r-dbi.org, https://github.com/r-dbi/RPostgres.                                                                                                                                                                                                                   |
| `sportyR`   | Drucker R (2022). sportyR: Plot Scaled 'ggplot' Representations of Sports Playing Surfaces. R package version 2.1.0, https://github.com/sportsdataverse/sportyR.                                                                                                                                                                                                |
