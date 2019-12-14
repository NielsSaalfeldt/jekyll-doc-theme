---
title: Welcome
permalink: /docs/home/
redirect_from: /docs/index.html
---

## Getting started

Once you have cloned the repo [group6project](https://github.com/Ferdi28/group6project), open the corresponding R project in your files.
From there let us guide you by following the steps below.
1. Download this package to start or rather build and install it.
2. Run the app either manually or with the function run_indeed().
3. The map will appear and you will observe the number of job listing in Switzerland.
4. Play around with it by filtering the category you seek to find a job in!
5. Zoom on the region/city you desire to work in and, by clicking on the icon you will observe job title and the indeed link to the corresponding job
6. CLICK & APPLY!


## Package functions

#### indeed_scraping()
Creates a data frame with indeed jobs based on the categories selected.
ATTENTION : Run to update the dataframe containing the information about the jobs listed at Indeed.
Include more or less categories depending on computing power of your computer (Four categories takes about 45 minutes).

#### map_ready_df()
Creates a data frame with indeed jobs and their corresponding latitude longitude based on the city.
Please make sure you use the following code in order to have the data for the appropriate job category:
final_indeed_data <- readRDS(file = here :: here("final_indeed_data.rds")) where the Data Frame comes from
the (prepared Data) folder.

#### indeed_map()
Creates an interactive map of the indeed data frame created with map_ready_df function.
It displays the job offers' location, its type and its external link to the indeed website.

#### run_Indeed()
Runs the shiny app to display Indeed Jobs on a map


