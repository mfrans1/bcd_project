# Benzie Conservation District Volunteer Data-Science Project

Invasive species pose a serious threat to freshwater ecosystems, yet the state of Michigan currently lacks the infrastructure to effectively assess and manage their spread. As part of the Benzie Conservation District’s long-term initiative to develop an aquatic invasive species (AIS) risk assessment for recreational boating and angling pathways in Benzie, Manistee, Grand Traverse, and Leelanau Counties, this project focused on cleaning and analyzing three years of in-situ boater movement data. A network analysis was then performed to identify high-risk transmission pathways between lakes, with interactive Folium maps used to visualize these relationships and inform spatial risk. The resulting insights contribute to ongoing efforts to model AIS spread and have been incorporated into grant proposals for congressional funding to support boat-washing stations and further research.

## Data Used and Data Preprocessing
The raw dataset, compiled from handwritten records collected at regional boat launches, was standardized using fuzzy matching with cosine similarity to align trip entries with the State of Michigan’s official GIS lake registry, resulting in an 89% successful match rate. This was used to generate cleaned_boater.csv

cleaned_boater.csv is the only datafile required to run mapping.ipynb

## Mapping
mapping.ipynb are a collection of interactive folium maps that visualize the boater/angler pathways found through this project. 
