# distributional_shift
Data and Python source code for replicating analyses of "Measurement and comparison of distributional shift with applications to ecology, economics, and image analysis"

## Purpose

The statistical concept of shift is often used to describe changes or directional differences in statistical moments (e.g., mean, variance) or entire distributions. In a [recent study](https://arxiv.org/abs/2401.11119), We propose that shift can also be used to describe individual frequency distributions. We define distributional shift (DS) as the concentration of frequencies towards the lowest discrete class, e.g., the left-most bin of a histrogram. We derive a measure of DS as a normalized sum of exponentiated cumulative frequencies. We also define relative distributional shift (RDS) as the difference in DS between distributions, yielding a measure that quantifies the direction and magnitude of difference between frequency distributions.

The data and source code of this repository pertain to our [recent study](https://arxiv.org/abs/2401.11119) wherein we: 1) Use empirical datasets to demonstrate DS as a measure of species rarity, economic poverty, and resource scarcity, 2) use multiple data generating processes to show that RDS is closely related to other comparative measures, and 3) Apply RDS to video image analysis by demonstrating its performance against established measures in the detection of light events, changes in complex patterns, detection of patterns within visual noise, and shifts in the color spectrum.

## Files & Directories

<details><summary>main_analyses_sans_images.ipynb</summary>
This Jupyter notebook file is used to generate all analyses and figures 1 through 5 of our study. It does not contain source code pertaining to image analysis.
</details>

<details><summary>main_image_analysis.ipynb</summary>
This Jupyter notebook file is used to generate image analyses pertaining to figure 6 of our recent study.
</details>

<details><summary>supplemental_measure_comparisons.ipynb</summary>
This Jupyter notebook file is used to generate supplemental analyses of comparisons of RDS to measures of distance, divergence, intersection, and probabilistic scoring, i.e., Supplemental figures 1 - 6 of our recent study.
</details>

<details><summary>supplemental_image_analysis.ipynb</summary>
This Jupyter notebook file is used to generate all supplemental image analyses of our recent study.
</details>

<details><summary>license</summary>
This MIT license applies only to source code. It does not pertain to or exert any rights over, e.g., data, images, or video files.
</details>

<details><summary>Supplement</summary>
This directory contains a single pdf file, Supplement_for_Preprint.pdf. This file accompanies the preprint of our [recent study](https://arxiv.org/abs/2401.11119)
</details>

<details><summary>data</summary>
This directory contains additional directories that are used by Jupyter notebooks to conduct analyses.
</details>

<details><summary>Final_Figs</summary>
This directory contains additional directories that are used to store pdf files of figures produced by Jupyter notebooks.
</details>




