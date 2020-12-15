# GUN VIOLENCE

*The Final Report with the Analysis and Findings can be found [here](https://nbviewer.jupyter.org/github/sanjanagupta16/data-512-final/blob/main/Final%20Report.ipynb?flush_cache=False).*

## Motivation
Over 37,500 American lives are lost on an average every year due to gun related violence. Between 1968 to 2011, about 1.4 million people have died from firearms in the United States. This number includes all deaths resulting from a firearm, including suicides, homicides and accidental discharges. The US gun homicide rate is 25 times than that of other high income countries. (!!) 

Given the alarming trend at which homicidal shootings have been increasing, it's important to take a hard look at this problem and, and ultimately make **data-driven** decisions. Unfortunately, research into firearms and gun control is full of difficulties due to limited data on gun ownership and use and aggregation of crime data.

The purpose of this project is to explore this issue and to see if there exists a correlation between gun related crimes and the firearm laws mandated by each state. This project also wishes to explore the different socio-economic and/or demographic factors that lead to higher number of such incidents.

## Data
#### Gun Violence Data

The primary dataset that will be used for analysis is the [Gun Violence Data](https://www.kaggle.com/jameslko/gun-violence-data) hosted on Kaggle. It is a comprehensive record of over 260K gun violence related incidents in the United States from 2013-2018. This data was web scraped from [Gun Violence Archive](https://www.gunviolencearchive.org/), a not-for-profit corporation that collects gun violence related incidents from over 7,500 law enforcement, media, government, and commercial sources daily.

Since the entire dataset could not be uploaded to GitHub due to size restrictions, a subset of the dataset can be found [here](https://github.com/sanjanagupta16/data-512-final/blob/main/data/gun-violence_sample.csv).

#### Census Data 

To normalize the number of incidents per state, The [US Census Population Data](https://www2.census.gov/programs-surveys/popest/datasets/2010-2017/state/asrh/scprc-est2017-18+pop-res.csv) will be used.

The datset can be found [here](https://github.com/sanjanagupta16/data-512-final/blob/main/data/census_population.csv).

#### Political Party Affiliation

Data was collected for each state's political party affiliation - Democratic or Republican. For this, results for the  US Presidential Elections was considered. Since elections are held every 4 years only, data for 2012 and 2016 was collected for each state, and extended for the remaining years. 

The data was collected from [MIT Election Data + Science Lab](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/42MVDX).

The dataset collected can be found [here](https://github.com/sanjanagupta16/data-512-final/blob/main/data/political_party_affiliation.csv).

#### Gun Laws

Since gun laws differ for each state (and sometimes across counties as well), and a single, rich source of data could not be found, data was curated for each state. This was done by looking up the state gun laws [here](https://www.gunstocarry.com/gun-laws-state/). 

The data curated can be found [here](https://github.com/sanjanagupta16/data-512-final/blob/main/data/gun_laws.csv).


## License
[MIT License](https://opensource.org/licenses/MIT) has been used for this project.
