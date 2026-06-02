<h1 align="center">

BirdWatch

</h1>

<h2 align="center">

Mind the GAP: Avian responses to conservation investments in California

</h2>

![birdwatch_proposal_photo](https://github.com/user-attachments/assets/2529c257-a5e3-42b1-85d1-3107a7994b34)

This is a capstone project for the [Master of Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) at [Bren School of Environmental Science and Management](https://bren.ucsb.edu), University of California, Santa Barbara

<h2 align="center">

[Project Description](https://bren.ucsb.edu/projects/mind-gap-avian-responses-conservation-investments-california)  

</h2>

## Description
In 2020, California implemented an executive order to advance biodiversity conservation as an administration priority, committing to the goal of conserving 30% of lands and coastal waters by 2030 (30x30), fitting into a larger framework that outlines that effective area-based conservation measures are a proven method for safeguarding habitats while preserving ecosystem services. 

A major challenge in approaching this goal is the lack of high resolution biodiversity data able to track responses to conservation approaches at large scales. Traditional conservation efforts have typically focused on establishing protected areas that are actively managed with conservation as a primary objective. While California could meet its 30 x 30 goal by acquiring new land for the existing protected area network, it might be more cost effective to use state resources for conservation stewardship in extant protected areas that are not currently managed for conservation (GAP status 3 & 4, USGS 2024), or by investing in ecosystem stewardship outside of protected areas. Understanding how biodiversity has performed historically across these three conservation approaches will provide much needed guidance to the 30 x 30 partnership for how to prioritize investment in resources to achieve its goals. 

This project uses avian observations from within areas defined by the United States Geological Service GAP project to inform resource investment decisions within the state. Point Blue Conservation Science hosts millions of avian observations on their platform Avian Knowledge Network (AKN) which can be used to fill the gap in high quality data, enabling analysis of where biodiversity and conservation efforts intersect. We will integrate AKN data with USGS GAP status designations to quantify the relationship between conservation status and biodiversity. This analysis will be synthesized into a technical memo detailing the results. This memo, along with a github repository and possible story map, will aid Point Blue in achieving their 5 year plan, as well as influence their recommendations to the state in regards to the implementation of the 30 x 30 goals. 

## Repository Structure
**[.github](https://github.com/MEDS-BirdWatch/.github)**: This repository contains the project overview information including repository directory.

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


### Key Literature

California Natural Resources Agency (CRNA). 2022. Final Pathways to 30x30 Strategy. https://resources.ca.gov/-/media/CNRA-Website/Files/Initiatives/30-by-30/Final_Pathwaysto30x30_042022_508.pdf 

California Natural Resources Agency (CRNA). 2025. Pathways to 30 x 30 California Progress Report 2024.  https://resources.ca.gov/-/media/CNRA-Website/Files/2025-30x30-Pathways-Progress-Report.pdf

Gonzalez, A., Chase, J. M., & O'Connor, M. I. (2023). A framework for the detection and attribution of biodiversity change. Philosophical Transactions of the Royal Society B: Biological Sciences, 378(1881), 20220182. https://doi.org/10.1098/rstb.2022.0182

Harrison, S., Franklin, J., Hernandez, R. R., Ikegami, M., Safford, H. D., & Thorne, J. H. (2024). Climate change and California's terrestrial biodiversity. Proceedings of the National Academy of Sciences, 121(32), e2310074121. https://doi.org/10.1073/pnas.2310074121

Moussy, C., Burfield, I. J., Stephenson, P. J., et al. (2022). A quantitative global review of species population monitoring. Conservation Biology, 36, e13721. https://doi.org/10.1002/cobi.13721

Urban, M. C., Alberti, M., De Meester, L., et al. (2024). Interactions between climate change and urbanization will shape the future of biodiversity. Nature Climate Change, 14, 436–447. https://doi.org/10.1038/s41558-024-01996-2

U.S. Geological Survey. (2024). Gap Analysis Project (GAP). https://www.usgs.gov/programs/gap-analysis-project 
Zhou, J., Yang, Fl., Zhong, Zj. et al. Surrogacy of bird species in systematic conservation planning and conservation assessments in Yunnan Province, China. J. Mt. Sci. 19, 2861–2873 (2022). https://doi.org/10.1007/s11629-021-7251-z
