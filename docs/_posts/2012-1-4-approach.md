---
layout: default
title: "Approach"
published: false
data:
  x: 1
  y: 0

---

1. The top 100 baby names for each region were identified by determining which names correlate to which of the five regions of immigration.
  * Top names were determined by treating names as predictors for immigration from a region and computing R<sup>2</sup> scores for each name for each region.

2. For each region, we constructed matrices in which rows represent the US states (including D.C.) and columns represent the 100 names for that region.
  * The value of each cell in the matrix is the overall count of that name in that state.

3. To reduce the dimensions of these matrices, we used principal components analysis (PCA).
  * The top two PCA components were used to visualize the similarity of names between states over time on a per decade basis.
  * We also identified the most representative immigrant names for each state by normalizing the name frequencies across states.


