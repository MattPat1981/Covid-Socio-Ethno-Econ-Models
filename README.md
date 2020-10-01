# Covid-Socio-Ethno-Econ-Models
A KMeans Clustering algorithm and a Linear Regression that look at Covid-19 by County

### A look at how clustering algorithms like KMeans can help us better understand Covid-19's affects on different US counties

**Matt Paterson, hello@hireMattPaterson.com**<br>
**Machine Learning Engineer**<br>
**Cloud Brigade, Santa Cruz, CA**<br>


### Web API

https://public.tableau.com/views/Covid_Clustering_SocioEconomic_Racial_Data/Overview?:language=en&:display_count=y&publish=yes&:origin=viz_share_link

See an easy to use Tableau Dashboard here

### The Data Science Question

**Can we use Unsupervised Machine Learning models to learn new things about Covid-19 and how it is affecting different counties in different parts of the country?**

We set out to assemble as much data from each US county as possible as a way to see what each county might have in common and how that influences a county's propensity for and the severity of Covid-19. Here, we use the recorded number of confirmed cases as well as deaths in each county, and added to that economic data and ethnic population data from the Beaureau of Economic Analysis and pumped all of this data in to a KMeans clustering algorithm.

### Top-Level Results

The findings were interesting but really not anything new. To whit: Counties with higher African American populations are most likely to have higher deaths per capita as a result of Covid than counties with low African American populations. That was the single strongest feature of correlation in our data.

As you can see from the Tableau API, or from a run through the clustering modeling in the KMeans ipynb, the geographic areas that have been hardest hit by the pandemic include high-density city cores as well as very low-density rural areas. The one thing that all of these areas have in common is their non-white racial ratios, and specifically a high relative percentage of African American people versus the rest of the population.

This project was never meant to be political but only to look at the numbers and listen to what the tell us. So far, this is what we see. This study does not suggest the causation of this correlation, only the existence of it. Whether the reasons have to do with underlying health issues (or the causes therein), the number of adults living in a single household, or the ability to work from home versus reporting to work every day with other people, this particular study was only concerned with finding patterns in the data and not finding the causation.

