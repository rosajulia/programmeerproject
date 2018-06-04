# Programmeerproject
Julia Jelgerhuis - 10725482 <br />
A visualization connecting brain regions to their neurobiological properties and connections.

### Problem statement
For neuroscientists, not many clear overviews exist for visualizing brain areas and linking them to neurobiological properties. In the field of neuroscience, it is particularly important to keep in consideration that brain regions “talk” to each other. In my visualization, I strive to bridge the gap between neurobiological properties and connections of different subcortical brain areas. </br>

### Solution
Visualization of subcortical brain areas and linking them to their neurobiological properties and connections. </br>
For the sketch, see sketch.jpg in the doc folder. </br>
Main features:
* A 3D image of the brain with an overlay of subcortical brain areas (**MVP**). People will be able to choose between 3 different views of the brain via a dropdown menu.
* When a region is clicked, three visualization will be shown: 
  1. A network visualization of that area with its most important connections (**MVP**); 
  2. A piechart of the distribution of 5 neurotransmitters in that area (in pgmol / g wet tissue) (MVP) or a piechart showing in which  resting-state networks these brain areas are involved (choice via buttons); 
  3. A webscraping element showing the Wikipedia page of the clicked area (**optional**). 

### Prerequisites
Data sources:
* Image of brain: retrieve via library Nipy.
* AAL atlas: atlas containing 92 different brain regions: http://www.gin.cnrs.fr/en/tools/aal-aal2/ 
* Article about brain networks and their corresponding brain regions --> convert results to csv file.       http://www.pnas.org/content/103/37/13848.short 
* Article about neurotransmitters per brain region --> convert results to csv file.  https://www.sciencedirect.com/science/article/pii/000689939191582L?via%3Dihub 

External components:
* Library Nipy: http://nipy.org/nipy/index.html 
  * A library for analysis of structural and functional neuroimaging data.
* Matplotlib: for making graphs in python.
* D3-tip: a tip for displaying information when hovering over a graph.

Related visualizations:
* Brainnetome atlas: http://atlas.brainnetome.org/bnatlas.html 
  * This atlas gives a clear view of all the areas in the brain. I have worked with the atlas and I hope to implement my brain atlas the same way, but with using Python instead of Matlab. 
  
Difficulties: </br>
It will be most difficult to implement the brain areas in the brain by using Nipy. I will try to overcome this by reading the how to of this program in the next couple days. Furthermore, I would love to find more data to compare with brain areas, such as neuronal density, volume, or spike rates, so I will also try to find more data. 


