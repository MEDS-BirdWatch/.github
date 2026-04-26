<h1 align="center">

BirdWatch

</h1>

<h2 align="center">

Mind the GAP: Avian responses to conservation investments in California

</h2>

![birdwatch_proposal_photo](https://github.com/user-attachments/assets/2529c257-a5e3-42b1-85d1-3107a7994b34)

This is a capstone project for the [Master of Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) at [Bren School of Environmental Science and Management](https://bren.ucsb.edu), University of California, Santa Barbara”

<h2 align="center">

[Deliverables](link) | [Deliverables]() 

</h2>

## Description
In 2020, California implemented an executive order to advance biodiversity conservation as an administration priority, committing to the goal of conserving 30% of lands and coastal waters by 2030 (30x30), fitting into a larger framework that outlines that effective area-based conservation measures are a proven method for safeguarding habitats while preserving ecosystem services. 

A major challenge in approaching this goal is the lack of high resolution biodiversity data able to track responses to conservation approaches at large scales. Traditional conservation efforts have typically focused on establishing protected areas that are actively managed with conservation as a primary objective. While California could meet its 30 x 30 goal by acquiring new land for the existing protected area network, it might be more cost effective to use state resources for conservation stewardship in extant protected areas that are not currently managed for conservation (GAP status 3 & 4, USGS 2024), or by investing in ecosystem stewardship outside of protected areas. Understanding how biodiversity has performed historically across these three conservation approaches will provide much needed guidance to the 30 x 30 partnership for how to prioritize investment in resources to achieve its goals. 

This project uses avian observations from within areas defined by the United States Geological Service GAP project to inform resource investment decisions within the state. Point Blue Conservation Science hosts millions of avian observations on their platform Avian Knowledge Network (AKN) which can be used to fill the gap in high quality data, enabling analysis of where biodiversity and conservation efforts intersect. We will integrate AKN data with USGS GAP status designations to quantify the relationship between conservation status and biodiversity. This analysis will be synthesized into a technical memo detailing the results. This memo, along with a github repository and possible story map, will aid Point Blue in achieving their 5 year plan, as well as influence their recommendations to the state in regards to the implementation of the 30 x 30 goals. 

## Repository Structure
**[.github](https://github.com/MEDS-BirdWatch/.github)**: This repository contains the prohect overview information including repository directory.

**[Avian_GAP_Analysis](https://github.com/MEDS-BirdWatch/Avian_GAP_Analysis)**: This repository houses all final workflow components for spatial and statistical analyses. Inside the repository are functions, quarto documents with each step in analysis, and final outputs. The README contains information about analytical decision making to guide users on reproducing analyses. 

**[BirdWatch_shiny](https://github.com/MEDS-BirdWatch/BirdWatch_shiny)**: This repository houses all the components to deploy a shiny dashboard to highlight trends and missing information in our data. Final data used in analyses are available as parquet files within the repository, and the server, ui, and global scripts are designed to be reused and modifiable by Point Blue Scientists and conservation users. 

## Contributors
Team members: Nathalie Bonnet, Isabella Segarra, Peter Vitale

Client: Dr. Sam Veloz with Point Blue Conservation Science

Faculty Advisor: Dr. Naomi Tague

## Acknowledgements
*Capstone Advisor*
 Dr. Carmen Galaz García, Bren School of Environmental Science & Management

*Special Thanks*
Dr. Max Czapanskiy, Bren School of Environmental Science & Management

## References

### Datasets

**[Avian Knowledge Network (AKN)](https://avianknowledge.net/)**: Avian Knowledge Network provides Level 5 (publicly accessible, non sensitive) data to users who create an account on the site. Data from AreaSearch and PointCount Survey types at this level were used in analysis. 

**[Protected Areas Database (PAD-US) Data](https://www.usgs.gov/programs/gap-analysis-project/science/pad-us-data-download)**: U.S. Geological Survey (USGS) Gap Analysis Project (GAP), 2024, Protected Areas Database of the United States (PAD-US) 4.1: U.S. Geological Survey data release, https://doi.org/10.5066/P96WBCHS. These data were used to classify land management status in the analyses.

**[CAL FIRE WHR13 Types](https://gis.data.cnra.ca.gov/maps/CALFIRE-Forestry::california-vegetation-whr13-types) and [CALFIRE FRAP [ds1327]](https://www.arcgis.com/home/item.html?id=58f81510e4c14b1da3c64823302f5101)**: CAL FIRE Vegetation data classified as of 2024 was used in analyses to represent habitat types across California. These data combine CAL FIRE WHR13 data and other WHR classes.

**[Partners in Flight Avian Conservation Assessment Database Scores Regional](https://pif.birdconservancy.org/avian-conservation-assessment-database-scores/)**: Partners in Flight data was used to provide conservation assessment data and rankings for all North American bird species of conservation of concern for California BCR Regions. These data were used with indicator species outcomes from AKN data to create a list of focal species to assess population trends. 

**[United States Census Bureau 2025 TIGER/Line® Shapefiles: Counties (and equivalent)](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2025&layergroup=Counties+%28and+equivalent%29)**: Used to create public facing data visualization of avian observations per California County. 


### R and R Studio
**Packages and versions**


### Key Literature

