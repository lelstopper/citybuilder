# citybuilder
## Documentation
Working on a mid to long term project for procedural generation of cities


This will be broken down into many sub-structures and will (probably) be rewritten many tines
I will be using python for starters.

** Breakdown of Core Generation**
1. Map/Terrain Gen
	- Can be done by generic noise algorithm and step sizes

2. Specific Features
	- Rivers
	- highways (probably)
	
3. Areas/Zones
	- Residential
	- CBD
	- Commercial
	- Office Space
	- Industrial
	- Pasture/Farms (Large land area primarily to support the city)

4. Generation of Road Networks
	- ???
	
5. Generation of Buildings
	- Particle Systems for the bulding meshes
	
**features that can be added**
1. Pathfinding implemented on a large scale ie. in units of 10-20 to prevent it from being computationally too expensive. This can also be implemented in an increased focus in public transport
2. Public Transport generative methods	
	
*algorithms used for generation of roads*
 - Ideally we want the roads to replicate modern day roads sprawl. There are two approaches to this
	1. We coud use the grid network of american cities like manhattan
	2. we could replicate space saving generation like trees using L-systems
	
	