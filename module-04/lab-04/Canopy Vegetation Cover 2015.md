# Estimation of Forest Vegetation Cover in Kenya: 2015 

**Scenario**

Conservation International has announced a Conservation Fund over the next 4 years to promote the protection of Kenya's natural ecosistems, vegetation, and wildlife. The funding priorities will include improving the conservation of Kenyan's protected areas, forest management, and monitoring the canopy closure for each county by year. 

Conservation International has partnered with the Kenyan Government, and they will provide the data using Kenya's open data portal to analyze and visualize the 2015 forest vegetation cover by county (%), and the polygons data for the protected areas. 

**1. Why are we making this product?**

	1. To visualize the density of canopy closure in Kenya by county.
    2. To capture the distribution of protected areas in an interactive web map.
	3. To discern if there is any correlation between our data. 
    
**2. What do we want to get out of this product?**

    1. Use it as a conservation tool.
	2. Display important forested areas and their distribution.
    3. Identify higher and lower density of forested areas by county.
    4. Compare if there is any link between higher density forested areas and protected areas.
    5. Create a project database.
    
**3. What do our users want to get out of this product?**

    1. Identify where important natural areas are located.
    2. Visualize the percentage canopy closure for each county.
	3. Operate this product as conservation/planning tool.

**4. Content Requirements:**
	
	1. Data will be represented on a basemap creating a choropleth map.
    2. Data will be encoded as a polygon colored or shaded proportionally to the value represented for each county.
    3. Data for the protected areas will be added to the map with a basemap option, and as polygons.
	4. The area of each county, and its forest cover will be represented in hectares.  
	5. A legend will inform user of the % of canopy closure per county.
    6. An info legend will be available with the protected areas information.
	
**5. Functional Requirements:**

	1. Map will load data dynamically from a CSV and JSON file.
	2. Two data layers will be created (% of canopy closure and protected areas).
	3. Data layers will be drawn to map.
	4. Additional information will be attached to each county, and to each protected area polygon on a click or hover.
    5. Upon a click on a protected area polygon the map will automatically zoom in at least one level.
    

