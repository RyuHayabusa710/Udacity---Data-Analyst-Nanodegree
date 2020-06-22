# Pokémon investigation
## by Hoai-Nam Nguyen


## Dataset

> After looking on Kaggle for an interesting dataset I've stumbled across this dataset and found it pretty interesting, because Pokémon reminds me of my younger years.
After looking at the dataset during the exploration phase I noticed that I didn't have to do real cleaning steps and just sometimes had to rearrange data, so I could plot them properly (temporarily dropping columns, pivoting for the Heatmap etc.).
This is the link I got the dataset from: https://www.kaggle.com/abcsds/pokemon


## Summary of Findings

> Univariate: The variables didn't have any unusual distribution at all. The single attributes almost always had a clear normal distribution (right-skewed). The "Total" had a bivariate distribution, but this can be explained because the "Total" is just the sum of the single attributes.

> Bivariate: Some features have a positive relationship with each other, as I mentioned above. Additionally there seems to be no trend across the different Generations or at least no visible trend regarding attributes or Pokémon types. I was surprised that legendary Pokémon had higher attributes than normal Pokémon! Although I've only played the first two games in my childhood I was always under the impression that the legendary birds were not as strong. The last analysis confirms this, as in the top 20 Pokémon ranked by Total "strength" there are only 4 non-legendary Pokémon.

> Multivariate: Some primary Pokémon types have not been introduced until later or have some Generations with no occurence of them at all (like Flying, Fairies, Dragons etc. - see above). Overall the strongest Pokémon type seems to be the Dragon type, having the highest overall average Total across the Generations. Additionally we could see in the Heatmap that some of the combinations (primary + secondary type) occur more often than others, like Normal and Flying being the most common combination, while the Flying type alone is rarely a primary type combined with another type. I was surprised about some Pokémon types not being represented in some Generations at all. Also the above mentioned combinations surprised me, that Pokémon are very rarely Flying as a primary type.


## Key Insights for Presentation

> Insight 1: Legendary Pokémon are on average stronger than normal Pokémon, out of the top 20 Pokémon (ranked by Total score) only 4 Pokémon where NOT legendary!

> Insight 2: Flying Pokémon are very rarely the primary Pokémon type and are most often just a secondary type! They weren't introduced as a primary type until Generation 5.


## Resources used

> Stackoverflow

> Documentation for pandas, Seaborn and Matplotlib

> Kaggle

> Google