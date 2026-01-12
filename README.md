# Peering into the twilight: a systematic review on visual -based investigation of worldwide mesophotic ecosystems  

Data and scripts used for the manuscirpt *Campanini et al., submitted, Peering into the twilight: a systematic review on visual -based investigation of worldwide mesophotic ecosystems*

Pre-print available at:

Authors: Campanini, Claudia; Marrocco, teo; Roveta, Camilla; Pulido Mantas, Torcuato; Coppari, Martina; Gregorin, Chiara; Di Camillo, Cristina Gioia; Cerrano, Carlo

## Abstract
Mesophotic ecosystems host high biodiversity and support a vast variety of habitats. Owing to climate change, there is a growing interest in the study of mesophotic assemblages as a possible pocket of biodiversity for species. However, due to logistic constraints, these habitats have been historically less investigated and mostly neglected in conservation planning. Thus, it is difficult to gain a global overview of the state of the art, especially with regards to sampling methodology. Here, we conducted a systematic literature review, extracting data from 994 publications on mesophotic research at a global level, focusing on visual-based methodologies, to identify gaps, emerging trends, and to supply useful information to improve sampling methodologies of mesophotic ecosystems and their reporting. Overall, the review highlighted an evidently uneven spatial distribution and a bias towards some taxonomic groups, i.e., corals and algae. From a methodological perspective, it showed that most studies at community level were performed with no standardized protocols. Even if crucial for the understanding of the functioning of these ecosystems, baseline data and long-term monitoring projects are virtually lacking. Despite these challenges, this review clearly shows a surge in interest and research effort driven by technological development. Considering the previously underestimated vulnerability of mesophotic ecosystems to anthropogenic pressures and the current climate change scenario, there is a pushing need to study mesophotic ecosystems through a standardized framework to adequately inform conservation and restoration measures.

## Repository structure

- [Deduplication](/deduplication): autoamtic deduplication with manual check was performed using the R package RefDeduR.
  - [raw data]() consisting in bibliography files exported from SCOPUS, Web of Science and mesophotic.org
  - [deduplication script](deduplication/Mesophotic_methods_LR_screening_from_excel)  
  - [deduplicated data](/deduplication/Clean_data): list of deduplicated records that were subjected to title-abstract screening
    
- [Data analysis of extracted data](/Extracted_data_analysis)
  - [Input data](/Extracted_data_analysis/Input_data): data extracted after full-text screening of included records (for explanation of each parameter collected see [metadata](/metadata.xlsx) and MEOW, an Excel file with the Marine Ecoregion of the World described by [Spalding et al., 2007](https://doi.org/10.1641/B570707)
  - Analyses of input data were run at a [global](/Extracted_data_analysis/global) level as well as for studies carried out in [temperate](/Extracted_data_analysis/temperate) and in [tropical](/Extracted_data_analysis/tropical) latitudinal regions. In each dedicated subfolder, there is a script file written in R markdown, the corresponding report in html, a subfolder with transformed data and one for visualizations.

- [Removed_records_clean.csv](/Removed_records_clean.csv): List of records excluded from the review with specified removal criteria. Each removal criterion is exaplained in see [metadata](/metadata.xlsx). 

## Licence
Scripts author: Claudia Campanini. No data can be used without the permission of the authors. Enquiries to claudiacampanini@hotmail.it
