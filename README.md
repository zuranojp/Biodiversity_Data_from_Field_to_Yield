# Master class: Biodiversity_Data_from_Field_to_Yield

Date & time: Tuesday, October 2 – Saturday, October 6, 2018 (5 full days)

Location: Universidade Federal do Rio Grande do Norte, Laboratório de Modelagem do departamento e Ecologia/DECOL, First floor, Natal, Brazil

Teachers: Alexandre Antonelli & Alexander Zizka, University of Gothenburg, Gothenburg Global Biodiversity Centre, and 
German Centre for Integrative Biodiversity Research  

http://antonelli-lab.net   http://ggbc.gu.se    https://www.idiv.de/ 

# Detailed schedule and locations
Day 1 (Oct, 2nd): 8:00 - 18:00  (local: UFRN/ Laboratório de Modelagem do departamento e Ecologia/DECOL - 1° andar)

Day 2 (Oct, 3rd): 5 am              (local: [Canyon dos Apertados](https://pt.wikipedia.org/wiki/Canyon_dos_Apertados). Meeting point: gas station Petrobrás "Posto 1002" - Av Roberto Freire, 2971 - Capim Macio)

Day 3 (Oct, 4th): 7 am              (local: [Parque das Dunas](http://www.parquedasdunas.rn.gov.br/). Meeting point: DECOL)

Day 4 (Oct, 5th): 8 - 18             (local: UFRN/  Laboratório de Modelagem do DECOL)

Day 5 (oct, 6th):  8 - 18             (local: UFRN/  Laboratório de Modelagem do DECOL)

# Before the course
Please:

* For the two days of field work, it is recommended to bring sunblock, hats, long-sleeved shirt, proper shoes and also some snacks (fruits, cereal bars, etc).  The lunch on the 3rd day (Canyon dos Apertados) will be paid for, but all other meals should be paid by the participants.

* Please bring your own computer and smart phone (iPhone/Android) if possible

* Read the course [literature](https://github.com/azizka/Biodiversity_Data_from_Field_to_Yield#literature)

* Download the [knowme.earth app](https://knowme.earth/) to your phone

* Install [R](https://cran.r-project.org/bin/) and [Rstudio](https://www.rstudio.com/products/rstudio/download/#download) on your computer

* Open R studio and install the necessary dependencies by copying the code below into the R console and running it. 

Please do not hesitate to [contact us](mailto:zizka.alexander@gmail.com) if you have any questions.


# Installation
Please run the following code (just copy it into the R console) before the course to make sure all dependencies are installed and we can start smoothly.

```
install.packages(c("countrycode", "ConR", "devtools", "ggmap", "mapproj", "maps",
                   "rgbif", "raster", "rnaturalearth", "sp", "tidyverse",
                   "viridis"))

library(devtools)

install_github(repo = "azizka/speciesgeocodeR")
install_github(repo = "azizka/sampbias")
install_github(repo = "azizka/CoordinateCleaner")
```


# Objectives
1.	Exemplify the various uses of biodiversity data for exploratory and question-driven research in ecology, evolution and biogeography 

2.	Familiarize participants with new bioinformatic tools for handling and processing ‘big data’, including dealing with data errors and biases 

3.	Provide the participants with a workflow to use large scale species occurrence data for biodiversity analyses (including point localities and range maps)

4.	Provide an overview of how to use R for analysing large datasets of species occurrences (including data mining, visualization, exploration, cleaning and applications)


# Background
The public availability of large-scale species distribution data has increased drastically over the last ten years. In particular, the digitalization of collections from museums and herbaria, the input from human and machine observations, and the aggregation of information in public databases such as the Global Biodiversity Information Facility (GBIF) have contributed significantly to this development. This is leading to a ‘big data’ revolution in biogeography, which holds an enormous but still poorly explored potential for understanding large scale patterns and drivers of biodiversity. 


# Project Assignment
During the course you will pick a taxonomic group of your interest and then independently collect occurrence data and answer biogeographic questions on this group with guidance from the teachers.


# Software exercises and Project questions
After collecting occurrence records in the field we will spend day four of the course getting to know different software to process the data and answer the research questions of your projects. There are seven exercises, each one representing a step to gather and process geographic occurrence information to tackle questions of your research project. 

Most of the exercises are in R, although exercise 1) and 6) can also be done using a web browser. Each exercise comes as a set of questions with some suggestions on how to solve them. If necessary, example answers are available to guide the students. Exercises 1) and 2) are compulsory, beyond that you can chose which exercises to follow based on the questions of your project.


# Examination
Grades are pass/fail. Successful participants should participate in all course days and present a project on the last day. A certification will be issued for all participants.


# Literature
1. Meyer *et al.* (2016) Multidimensional biases, gaps and uncertainties in global plant occurrence information. *Ecology Letters* 19:992-1006.

2. Schmidt *et al.* (2017) Diversity, distribution and preliminary conservation status of the flora of Burkina Faso. Magnolia Press.

3. Antonelli *et al.* (2018) Amazonia is the primary source of Neotropical biodiversity. PNAS 6pp

4. One of the following suggestions (depending on your own interests):

* Edler *et al.* (2017) Infomap Bioregions: Interactive mapping of biogeographical regions from species distributions. *Systematic Biology* 66(2):197–204

* Antonelli (2017) Comparative biogeography, big data, and common myths. In: *Tropical Plant Collections: Legacies from the Past? Essential Tools for the future. Scientia Danica. Series B, Biologica. vol. 6*

* Silvestro *et al.*(2016) Fossil biogeography: a new model to infer dispersal, extinction and sampling from palaeontological data. *Philosophical Transactions of the Royal Society B* 371:20150225

* Price *et al.* (2019) Big data little help in megafauna mysteries. Nature 558(7):23-25
