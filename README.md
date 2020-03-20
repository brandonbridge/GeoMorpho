# GeoMorpho

This repository contains the data and jupyter notebooks used in the geometric morphometric analysis performed in the dissertation of Katherine Baca, Department of Anthropology, University of Montana, titled, "Three-dimensional Geometric Morphometric Sex Determination and Modeled Fragmentary Analysis of the Human Pubic Bone."

For this research we used a Linear Discriminant Analysis (LDA), a supervised machine learning algorithm, to accurately classify human pubic bones as either male or female. Each bone was digitized with eight landmarks, and a procrustes analysis was done in MorphoJ to standardize the samples.

The directory titled "Linear Discriminant Analysis" contains the data and code for the LDA run on the full sample. The directory titled "Fragmentary Analysis" contains the data and code for the fragments.

For the fragmentary analysis, we ran the same algorithm separately on each possible combination of three or more landmarks. The landmark combinations were computed in Combinatorics.ipynb.

All code was written by Brandon Bridge. 
