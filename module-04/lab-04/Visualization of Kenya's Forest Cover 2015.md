# Visualization of Kenya Forest Cover 2015

According to the U.N. FAO, 6.1% or about 3,467,000 ha of Kenya is forested, according to FAO. Of this 18.9% ( 654,000 ) is classified as primary forest, the most biodiverse and carbon-dense form of forest. Kenya had 197,000 ha of planted forest.
Between 1990 and 2010, Kenya lost an average of 12,050 ha or 0.32% per year. In total, between 1990 and 2010, Kenya lost 6.5% of its forest cover, or around 241,000 ha. (http://rainforests.mongabay.com/deforestation/2000/Kenya.htm).

Kenya's forests contain 476 million metric tons of carbon in living forest biomass. Biodiversity and Protected Areas: Kenya has some 1847 known species of amphibians, birds, mammals and reptiles according to figures from the World Conservation Monitoring Centre. Of these, 4.0% are endemic, meaning they exist in no other country, and 3.8% are threatened. Kenya is home to at least 6506 species of vascular plants, of which 4.1% are endemic. 6.0% of Kenya is protected under IUCN categories I-V. (http://rainforests.mongabay.com/deforestation/2000/Kenya.htm).

Most Kenyan forests are under pressure. That is because of deforestation, forest fragmentation, forest degradation, over-exploitation of species and the introduction of exotic species. One of the ecological communities that have been most extensively exploited is lowland forest, the first forests to be cleared for agriculture. Because the land best suited to the growth of forests is also good agricultural land, the remaining forests in Kenya are highly fragmented. Many species are inhibited from crossing forest gaps and therefore many isolated populations will not be “rescued” or supplemented by individuals dispersing from forest fragments. Therefore, these species face additional risks of extinction. (http://www.helsinki.fi/science/taita/reports/Peltorinne_Forest_types.pdf)

Deforestation and forest degradation can adversely affect many ecological processes impacting on e.g. soil-water relationship, but the over-exploitation of ecological resources for survival is a complex matter. To counter such process, account must be taken of the characteristics of the biophysical environment, patterns of resource use and consumption, socio-cultural conditions and the socio-economic roots of poverty. A shift from commercial re-afforestation programmes to community involvement in forest resources development would have long-term benefits that are sustainable. (http://www.helsinki.fi/science/taita/reports/Peltorinne_Forest_types.pdf)

Social and farm forestry practices have emerged as possible sustainable solutions to environmental degradation, because these approaches favour equity, ownership and desired community participation. (http://www.helsinki.fi/science/taita/reports/Peltorinne_Forest_types.pdf)


**1. Why are you making this product?**

	* I want to visualize the forest cover for each county in Kenya.
	* See which counties have more forest cover in relationship to their area and which counties don't.

**2. What do we want to get out of this product?**

    * Use it as a conservation tool.
	* Create awareness within the population in Kenya of the importance of forests.
    
**3. What do our users want to get out of this product?**

    * Knowledge of estimate forest cover for each county in Kenya.
	* Conservation tool.

**Content Requirements:**
	
	1. Data will be represented as a percentage by county and using a proportional symbol.
	2. Data will be encoded as one circle for each county.
	3. Area of county and area of forest cover of that county will be available for the user.
	4. Data will be displayed on a basemap for locating counties in wider geography.
	5. A legend will inform user of the relative magnitude of the circles?
	
**Functional Requirements:**

	1. Map will load data dynamically from csv file.
	2. One data layer will be created from the data file.
	3. Data layer will be drawn to map.
	4. Additional information will be attached to each county to user on a click or hover.

**Initial Structure:**

    1. Data will be encoded in a JSON or GeoJson format.
    2. These data will consist of a single feature for each geographic county.
    3. Each feature will also contain the data attribute.
    4. CSV data didn't contain data of geographic coordinates for each county; these information was            copied from a different dataset.
