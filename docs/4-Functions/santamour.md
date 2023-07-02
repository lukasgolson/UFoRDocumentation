---
id: santamour
title: santamour - Applying Santamour's Species Diversity Rule
---

Santamour's Species Diversity Rule, or the 10-20-30 rule, is a guideline suggesting no more than 10% of any one species, 20% of any one genus, and 30% of any one family should occupy a region. This rule is a preventive measure against the risks associated with over-reliance on a few species.

```R
santamour(species, genus, family, region, output)
```

- `species`: Species column in community data
- `genus`: Genus column in community data
- `family`: Family column in community data
- `region`: Regional divisions of the community data
- `output`: `numeric` (count) or `text` (species)

```R
Data(TreeTown_Data)
TreeTown_Data$Column1 <- species
TreeTown_Data$Column2 <- genus
TreeTown_Data$Column3 <- family
TreeTown_Data$Column4 <- region
santamour(species, genus, family, region, output = numeric)
```

### References