# Master's project
This Github repository contains the data, code, html pages and visualizations that together makes up my master's thesis at Columbia Journalism School. The project examines the decades long decline in aquatic biodiversity in the southeastern United States, what caused this decline and what is being done to reverse it. 

The result is the article
[Crisis in the Currents: Alabama’s Tug-of-War for the Future of Freshwater Biodiversity](https://laurabejder.com/masters-project/)

## In the repository

The file `index.html` contains the html code for the full webpage linked above.

#### Notebooks
- `dam-analysis.ipynb`: This notebook contains an analysis of the size, ownership and age of the dams in the Southeast.
- `species-analysis.ipynb`: This notebook contains the majority of the projects data analysis including grouping by states, species and endangerment.
- `state-level-analysis.ipynb`: This notebook allows you to run analysis on the data from the state organizations.

#### The `data` directory
All the data files that are needed to replicate the analysis in the notebooks. The data comes from [Natureserve](https://explorer.natureserve.org/), the [US Fish and Wildlife Services](https://www.fws.gov/species/search) and the [National Inventory of Dams](https://nid.sec.usace.army.mil/#/). It also includes data directly from the state organizations in Alabama, Georgia and Tennessee that monitor species' endangerment.

#### The `images` directory
Images that appear or are related to the article.

#### The `maps` directory
The QGIS files for the map of endangered species in the southeast.

#### The `shapefiles` directory
The shapefiles for the geographical distribution of all federally listed endangered and threatened aquatic species that occur primarily in the southeastern region. All the files are downloaded from the [US Fish and Wildlife Services website](https://www.fws.gov/species/search). 

#### The `visuals` directory



## Methodology
In this section I explain the methodological choices I have made throughout the project and their limitations and consequences. 

This project deals with freshwater species here defined as the species that by Natureserve was put in the four categories `freshwater fishes`, `freshwater mussels`, `freshwater snails`, and `crayfishes`. This means the exclusion of other potential freshwater species (salamanders, snails, shrimps etc.) that weren't put in a clear freshwater category. I decided to limit my research to freshwater species alone because the species and ecosystems are significantly different from saltwater and terrestrial species and because of the unique challenges facing this particular kind of ecosystem. 

- What is the southeast
- states
- Differences between states (endimism, remaining nature)

- Using the highest S rank (contrary to G rank or normal s rank)

- Things we still don't know
- Still listing species
- how updated is the data
