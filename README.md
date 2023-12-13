# <Kim_mittal_Wei_ClassProject>

<General notes: add as much information as is relevant for your repository. Some overarching guidelines are provided, but feel free to expand on these guidelines.>
<More resources found here: https://www.dataone.org/all-best-practices>
<Delete the text inside the brackets when formatting your file.>

## Summary
This repository is created for ENVIRON 872L's class project. Palm oil production is one of the main drivers of deforestation in Southeast Asia. However, to what extent does it contribute to deforestation? In this repository, we try to answer that question and also explored the relationship between palm oil production and CO2 emission as climate change is also a pressing issue.
Our goal is to explore our research question: How has the cultivation of oil palm contributed to deforetation and carbon emissions in Indonesia and Malaysia from 1990 and 2020? To do so, linear regression and time series analysis models are used.
To do this, we are using three datasets: Oil Palm Production - FAO, Forest Cover - FAO, and Carbon Dioxide Emissions - Climate Watch. 
This repository contains raw data that we obtained from the repective sources in the Raw data folder, processed data in the Processed folder, and relevant R project in the main menu.




## Investigators
<Vanishka Mittal: MEM, vanishka.mittal@duke.edu, Ayoung Kim: MEM, ayoung.kim@duke.edu, Queenie Wei: MEM, queenie.wei@duke.edu>


## Keywords

<Oil Palm Plantations, Carbon Dioxide Emission, Forest Cover, Planted Forest, Natural Forest, Deforestation, Malaysia, Indonesia>

## Database Information

<describe the origin of all data in the repository, including data collected from outside sources and new data generated by the investigator(s). If data was accessed from an outside database, the date(s) of data access should also be included.>

Palm oil production: Our world in data https://ourworldindata.org/palm-oil
CO2 emissions by sector: Climate Watch https://ourworldindata.org/emissions-by-sector
Forest area: Food and Agriculture Organization of the United Nations https://ourworldindata.org/forest-area

## Folder structure, file formats, and naming conventions 

<describe the folders contained in the repository, including what type of files they contain>
This repository includes two folders and a home page. The home page contains the relevant R project files, Raw folder contains raw data, and Processed folder contains processed data.
All of the files in the two folders are in csv formats. They are named using descriptive language.


## Metadata

<For each data file in the repository, describe the data contained in each column. Include the column name, a description of the information, the class of data, and any units associated with the data. Create a list or table for each data file.> 
Raw data: 
forest-area-primary-planted.csv: 
Columns: Entity, Year, Planted.Forest...00006716....Area...005110....hectares, Naturally regenerating forest.00006717.Area.005110.. hectares.
Entity: Country
Planted.Forest...00006716....Area...005110....hectares: Planted forest in hectares
Naturally regenerating forest.00006717.Area.005110.. hectares.: Naturally regenerating forests in hectares

ghg-emissions-by-sector_indonesia.csv and ghg-emissions-by-sector_malaysia.csv: (Food and Agriculture 2020)
columns: Entity, Year,  Greenhouse. gas emissions.from.land.use .change.and.forestry
Entity: Country
Greenhouse. gas emissions.from.land.use .change.and.forestry: GHG emissions from land-use change and forestry in tons

palm-oil-production.csv: (Our World in Data)
Columns: Entity, Year, Palm.oil...00000257....Production...005510....tonnes
Entity: Country
Palm.oil...00000257....Production...005510....tonnes: Palm oil production in tonnes




## Scripts and code

Git.ignore: exclude files in the working directory from the Git history. Ensures that files that are not tracked by Git remains untracked.

## Quality assurance/quality control

This project uses very preliminary TSA and can be improved using more sophisticated analytical methods such as machine learning. Also, GIS data was not used due to the limited capacity of the members. Future research should be conducted use spatial data to better analyize where the deforestation and CO2 emission occurs and if that aligns with oil palm production patterns.
