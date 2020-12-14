# DATA 512 Au 20: Human-Centered Data Science

### Project Proposal
This project aims to explore gun violence related crimes in the United States and to investigate if there are any significant socio-economic and/or demographic factors that lead to these crimes.

### Data
#### Gun Violence Data

The primary dataset that will be used for analysis is the [Gun Violence Data](https://www.kaggle.com/jameslko/gun-violence-data) hosted on Kaggle. It is a comprehensive record of over 260K gun violence related incidents in the United States from 2013-2018. This data was web scraped from [Gun Violence Archive](https://www.gunviolencearchive.org/), a not-for-profit corporation that collects gun violence related incidents from over 7,500 law enforcement, media, government, and commercial sources daily.

It contains 239, 677 rows of data with 29 columns/features. The dataset consists of:
* Date of incident
* The location (City, State, Address, Latitude, Longitude, Congressional District, State House District, State Senate District)
* Casualties (Killed, Injured)
* Logistics (Guns stolen, Number of guns involved, Gun type)
* Demographic information about the persons involved (Age, Gender, Type)

The Gun Violence Data is publicly available and as [stated](https://www.gunviolencearchive.org/about), it can be used for research, advocacy or writing. 

This dataset contains a lot of missing data from 2013 and only contains data until March 2018. There have been a considerable number of incidents since then that are not included in the dataset.

Since the entire dataset could not be uploaded to GitHub due to size restrictions, a subset of the dataset can be found [here](https://github.com/sanjanagupta16/data-512-final/blob/main/data/gun-violence_sample.csv).

#### Census Data 

To normalize the number of incidents per state, The [US Census Population Data](https://www2.census.gov/programs-surveys/popest/datasets/2010-2017/state/asrh/scprc-est2017-18+pop-res.csv) will be used.

The datset can be found [here](https://github.com/sanjanagupta16/data-512-final/blob/main/data/census_population.csv).

#### Political Party Affiliation

Data was collected for each state's political party affiliation - Democratic or Republican. For this, results for the  US Presidential Elections was considered. Since elections are held every 4 years only, data for 2012 and 2016 was collected for each state, and extended for the remaining years. 

The data was collected from [MIT Election Data + Science Lab](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/42MVDX).

The dataset collected can be found [here](https://github.com/sanjanagupta16/data-512-final/blob/main/data/political_party_affiliation.csv).

#### Gun Laws

Since gun laws differ for each state (and sometimes across counties as well), and a single, rich source of data could not be found, data was curated for each state. This was done by looking up the state gun laws [here](https://www.gunstocarry.com/gun-laws-state/). Each state was also assigned a star rating from 1 to 5, with 5 being awarded to states with the friendliest gun laws. 

For the purpose of this project, gun laws applicable only to handguns was considered. 

The data curated can be found [here](https://github.com/sanjanagupta16/data-512-final/blob/main/data/gun_laws.csv).


### License
[MIT License](https://opensource.org/licenses/MIT) has been used for this project.
