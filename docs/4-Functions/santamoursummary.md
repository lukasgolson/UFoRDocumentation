---
id: santamoursummary
title: santamoursummary - Summarizing Violations of Santamour's Rule
---

The `santamoursummary` function offers a way to track adherence to Santamour's Species Diversity Rule. The rule is a guideline for maintaining biodiversity and minimizing the vulnerability of a region to pests or diseases that may target specific species, genus, or families.

```R
santamoursummary(species, genus, family, region)
```

- `species`: Species column in community data
- `genus`: Genus column in community data
- `family`: Family column in community data
- `region`: Regional divisions of the community data

```R
Data(TreeTown_Data)
TreeTown_Data$Column1 <- species
TreeTown_Data$Column2 <- genus
TreeTown_Data$Column3 <- family
TreeTown_Data$Column4 <- region
santamour(species, genus, family, region, output = numeric)
```

### References