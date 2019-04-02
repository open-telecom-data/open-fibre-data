Network Deployment Table
========================

| Field | Description / Examples | Rationale |
| --- | --- | --- |
|*GIS Info*|||		
|Route|a polyline or collection of polylines in GIS (probably GEOJSON)| format	visual data of network extent|
|ISO Country Code|	2 letter country code|	to enable country-level analysis of networks|
|Network Length	number| of kilometres (derived from GIS Info)|	essential for cost analysis|
|*Tech Info*		|||
|Type of deployment|Aerial or Underground|	essential for cost analysis and for revealing opportunities|
|Number of fibres|	e.g 12/24/48/96|	these two fields tell us the capacity of the cable as well as indicate a lifespan|
|Fibre Type| (ITU Standard)	e.g. G.652, G.652.D G.653 etc	||
|*Operational Info*		|||
|Year of inauguration|	Year the network went live|	useful for historical analysis of network development|
|Operator|	Who manages the network - Link to organisation table|	does the operator manage one network or several?|
|Current Status|	is the network operational|	self-explanatory|
|Construction Organisation|	Company name, link to Organisation Table	who built the network, sometimes linked to financing||
|*Ownership & Finance Info*		||
|Financing source|	Company name, link to Organisation Table	|who is investing in terrestrial fibre|
|Financing amount|	USD| 	how much of the network was financed|
|Financing terms|	loan, soft loan, grant, trade agreement	||
|Total Cost|USD 	what did the network cost to build||
|Ownership Structure|PPP, Private, Public, Cooperative|	how is the ownership structured|
|Owners |	Company name, link to Organisation Table [array]	||
|Terms of Access|	Open Access, Closed Club, etc	||
|Network Name|	if any	||
|Phase Name|	if any	||
|Network Website	|does the network have a website url||	self-explanatory
