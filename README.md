# BST 270: Individual Project
This repository contains my attempt to reproduces figures from FiveThirtyEight's [How Americans View Biden's Response To The Coronavirus Crisis](https://projects.fivethirtyeight.com/coronavirus-polls/).

## Environment

This project utilizes Python programming language. For packages used to build this project, create a conda environment using the provided `environmnet.yml` file:

```bash
conda env create -f environment.yml
```

## Code

A complete code for reproduction is available at `./code/covid-response.ipynb`. 

## Data

The data set used for the reproduction analysis is available at `./data/covid_approval_toplines.csv`. It contains the calculated daily averages for the approval polls.

Column | Description
---------|-------------
`subject`| This column marks whose handling of covid-19 the approval poll is about, the value can be `Trump` or `Biden`
`modeldate` | Date of this summary info.
`party`| Party of respondents
`approve_estimate` | The percentage of people who approves.
`disapprove_estimate` | The percentage of people who approves.
`timestamp` | The time point for the summary work.