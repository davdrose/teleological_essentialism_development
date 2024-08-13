# Teleology, shape and transformations

This repository contains the experiments, data, analyses, and figures for the paper "Teleology, shape and transformations," by David Rose, Jadess Lowery, Siying Zhang, and Ellen Markman.

The preprint can be found [here](https://UPDATE)

__Contents__:
- [Introduction](#Introduction)
- [Repository structure](#Repository-structure)

## Introduction

<img src="figures/storyboard.png" width="100%" align="center">

<br clear="left" />
<br clear="right" />

[Replace with abstract]



## Repository structure

```
├── code
│   ├── R
│   └── experiments
│       ├── exp1
│       ├── ...
├── data
│   ├── exp1
│   ├── exp2
│   ├── exp3
│   └── exp4
├── docs
└── figures
    ├── exp1
    ├── exp2
    ├── exp3
    ├── exp4

```

- `code/` contains all the code for the experiments, analyzing data and generating figures.
  - `experiments` contains materials and code for each experiment that was run. Pre-registrations for all experiments are linked below.
    	- `exp1` ([pre-registration](https://osf.io/2gebc)) was run asynchronously in Lookit.
	- `exp2` ([pre-registration](https://osf.io/uzhw8) was run synchronously over Zoom. 
	- `exp3 part1` ([pre-registration](https://osf.io/pb4wa)) and `exp3 part2' ([pre-registration](https://osf.io/8v5yk)) were run asynchronously in Lookit.
	- `exp4` ([pre-registration](https://osf.io/mrqdx)) was run asynchronously in Lookit.
- `R` contains the analysis scripts that were used to analyze data and generate figures
     (view a rendered file [here](https://davdrose.github.io/teleology_shape_transform/)).
- `data/` contains anonymized data from all experiments:
  - `exp1` contains `exp1.csv` which includes trial and demographic data. 
  - `exp2` contains `exp2.csv` which includes the trial and demographic data.
  - `exp3` contains `exp3_part1.csv` and `exp3_part2.csv' which includes the trial demographic data for each respective experiement.
  - `exp4` contains `exp4.csv` which includes the trial and demographic data.
- `docs/` contains all the experiment code 
- `figures/` contains all the figures from the paper (generated using the script in `code/R/`). 
