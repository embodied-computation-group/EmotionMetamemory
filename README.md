# Emotional valence and arousal influence metacognition for memory

Nicolas Legrand, Sebastian Scott Engen, Camile Correa, Nanna Kildahl Mathiasen, Niia Nikolova, Francesca Fardo, Micah Allen

This repository contains data, scripts and Jupyter notebook needed to reproduce analyses from the preprint version of the paper.

# Abstract

>Emotional and physiological arousal biases both perception and decision making. In the domain of memory, the valence and arousal of memorized stimuli can modulate both the acuity and content of episodic recall. However, no experiment has investigated whether arousal and valence also influence metacognition for memory (i.e. the processes of self-monitoring memories). In this pre-registered study we measured the sensitivity, bias, and efficiency of meta-memory for arousing versus unarousing words with either positive or negative valence, and measured cardiac activity during decision making as an index of physiological arousal. We found that negative valence globally decreased both memory performance and metacognition.  Emotional valence had no effect on the instantaneous heart rate, but we found strong modulation of heart rate variability across experimental blocks. Exploratory analyses on the trial level also revealed that the instantaneous heart rate encoded confidence, and this was modulated by emotional valence. These data indicate that both memory and metacognition are biased by emotional valence, while arousal has only marginal influence, and show that this effect is partially mediated by cardiac activity.


# Data

Raw behavioral and physiological data are provided in the `Data/Raw` folder.

# Code

## Notebooks

Figures and statistical models can be reproduced via Jupyters Notebooks and Rmarkdow scripts.

* `1 - Behavioral.ipynb` will preprocess the behavioral data, plot and run stat models.
* `2 - EvokedPulseRate.ipynb` will extract and clean instantaneous pulse rate, save reports, plot and test results for Figure 3.
* `3 - Regressions.ipynb` will run the regression analysis for Figure 5.
* `4 - PulseRateVariability.ipynb` will extract HRV, plot and run stat model for Figure 4.

## Scripts

### Metacognition

* `sdt.py` Signal Detection Theory utilities.

* `metad.R` R script runing hierarchical estimation of meta-d' based on the method proposed by Fleming (2017). Adapted from: https://github.com/metacoglab/HMeta-d

# Figures

## Figure 1:
![Figure 1: ](Figures/Figure1.png)
>

## Figure 2:
![Figure 2: ](Figures/Figure2.png)
>

## Figure 3:
![Figure 3: ](Figures/Figure3.png)
>
