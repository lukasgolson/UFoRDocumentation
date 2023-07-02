---
id: sprich
title: sprich - Species Richness Calculation
---

Species richness is a crucial concept in biodiversity studies and conservation. It refers to the number of different species represented in a particular community. High species richness indicates greater biodiversity, which is often linked to the stability and health of an ecosystem.

```R
sprich(x, region, se)
```

- `x`: Community data (matrix-like object or a vector)
- `region`: Regional divisions of the community data
- `se`: Estimate standard errors

```R
Data(TreeTown_Data)
TreeTown_Data$Column1 <- x
TreeTown_Data$Column2 <- region
sprich(x, region, se)
```

### References