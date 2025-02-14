# distributional_shift
Data and Python source code for replicating analyses of "Measurement and comparison of distributional shift with applications to ecology, economics, and image analysis"

## Purpose

The concentration of a discrete or continuous distribution of frequencies or probabilities toward a lower bound is a conceptually simple property that historically lacks a global descriptive statistic. We recently termed this property ‘shift’ and defined it as the distance of a central tendency from an upper bound, expressed as a proportion of a finite range. The source code of this repository pertains to our [recent study](https://arxiv.org/abs/2401.11119) of the shift statistics that we develop.

## Files & Directories

<details><summary>Fig1_ShiftSkew.ipynb</summary>
This Jupyter notebook file is used to generate analyses of the relationship between shift and skewness (Figure 1 of our manuscript).
</details>

<details><summary>Fig2_DistMetics.ipynb</summary>
This Jupyter notebook file is used to generate comparative analyses between |Δ𝒮| and established distance metrics (Figure 2 of our manuscript).
</details>

<details><summary>Fig3_Fig4_Rarity.ipynb</summary>
This Jupyter notebook file is used to generate comparative analyses between 𝒮  and established measures of rarity (Figures 3 and 4 of our study). The analyses use combinatorical feasible sets of integer partitions.
</details>

<details><summary>Fig5_Poverty.ipynb</summary>
This Jupyter notebook file is used to generate comparative analyses between 𝒮 and established measures of poverty (Figure 5 of our study).
</details>

<details><summary>Fig6_ImageAnalysis.ipynb</summary>
This Jupyter notebook file is used to generate a relatively basic analysis of a synthetic video using our shift statistics (𝒮, Δ𝒮, |Δ𝒮|) and Wasserstein Distance (Figure 6 of our study).
</details>

<details><summary>license</summary>
This MIT license applies only to source code. It does not pertain to or exert any rights over, e.g., data, images, or video files.
</details>

<details><summary>data</summary>
This directory contains a single directory (time_lapse_video), which holds a single file (synthetic_video_no_noise_no_bars.mp4). This video file is used in the `Fig6_ImageAnalysis.ipynb` file.
</details>

<details><summary>Final_Figs</summary>
This directory contains additional directories that are used to store pdf files of figures produced by Jupyter notebooks.
</details>




