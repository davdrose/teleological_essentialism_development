# Teleological essentialism in development

This repository contains the experiments, data, analyses, and figures for the paper "Teleological essentialism in development," by David Rose, Jadess Lowery, Siying Zhang, and Ellen Markman.

The preprint can be found [here](https://davdrose.github.io/assets/pdf/teleological_essentialism_development.pdf)

__Contents__:
- [Introduction](#Introduction)
- [Repository structure](#Repository-structure)

## Introduction

<img src="figures/storyboard.png" width="100%" align="center">

<br clear="left" />
<br clear="right" />

Overcoming appearances in categorizing is an important intellectual achievement. But children can’t help but rely on them, as classic shape similarity (e.g., Landau at al, 1988) and perceptual transformation tasks (Keil, 1989) show. Scientific essences – placeholders for what gives something its identity that science fills out – might help (Gelman, 2003) but have a protracted development. We instead propose that children can more readily treat purposes as essences. Across three experiments, with 570 US based children, we find support for this. In contrast to being given only a label or inductively irrelevant properties, children categorize together dissimilar looking, familiar objects based on familiar purposes at the basic (Experiment 1) and superordinate level (Experiment 2)  Children also used an object’s purpose to judge its identity in the face of radical perceptual transformations (Experiment 3). That children can elaborate placeholders with purposes for biological kinds and artifacts suggests a reorientation of essentialism. 



## Repository structure

```
├── code
│   ├── R
│   └── experiments
│       ├── experiment1
│       ├── ...
├── data
│   ├── experiment1
│   ├── experiment2
│   └── experiment3
├── docs
└── figures
    ├── experiment1
    ├── experiment2
    ├── experiment3

```

- `code/` contains all the code for the experiments, analyzing data and generating figures.
  - `experiments` contains materials and code for each experiment that was run. Pre-registrations for all experiments are linked below.
    - `experiment1` ([pre-registration](https://osf.io/2gebc)) was run asynchronously in Lookit.
	  - `experiment2` ([pre-registration](https://osf.io/uzhw8)) was run synchronously over Zoom. 
    - `experiment3` includes a two-part norming study and the experiement  
      - two part norming study:
	      - `part1` ([pre-registration](https://osf.io/pb4wa)) and `part2` ([pre-registration](https://osf.io/8v5yk)) were run asynchronously in Lookit.
      - experiment:
        - `experiment` ([pre-registration](https://osf.io/mrqdx)) was run asynchronously in Lookit.
  - `R` contains the analysis scripts that were used to analyze data and generate figures
     (view a rendered file [here](https://davdrose.github.io/teleological_essentialism_development/)).
- `data/` contains anonymized data from all experiments:
  - `experiment1` contains `exp1.csv` which includes trial and demographic data. 
  - `experiment2` contains `exp2.csv` which includes the trial and demographic data.
  - `experiment3` contains `exp3_norm_part1.csv`, `exp3_norm_part2.csv`, adn `exp3.csv` which includes the trial demographic data for each respective experiement.
- `docs/` contains R code for viewing
- `figures/` contains all the figures from the paper (generated using the script in `code/R/`). 
