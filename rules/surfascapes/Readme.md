# Surfacescapes 
Authors: Steven Kaminski & Meghan Kalinowski

![surfacescapes_cover](rules/surfascapes/examples/Surfacescapes_Markdown_Cover.PNG)

![A semi-decentralized system of reorganizing “streets” to accomodate community needs and Climate Change.](rules/surfascapes)

> A surface network that focuses on human powered mobility, community activation and productive systems. Its architecture symbiotically links to existing site infrastructure and aims to respect the preexising golf course topography; maximizing environmental gains while promoting new activations within the public realm.

## Participative Design
![surfacescape_participative}(rules/surfascapes/examples/Surfacescapes_Markdown_ParticipativeDesign.PNG)

> The rules of the surfacescape code were designed to allow for flexible use depending on what the community needs. Using the codes in the CityEngine model community stakeholders can see how different public use, ecological and mobility options would affect the mobility and engagement in the public realm of the surfacescape. 

## Code
The primary function of the code is to segment the street function in CityEngine to create new "surfacescapes" which we envision having a totally different use and function from what is knows traditionally as a street. We designed two rules for these surfacescapes. One is a simplified version using primarily color for high level understanding the other is a more detailed and granular code with objects, trees, street splitting, extrusions and patterns demonstrating the surfacescape design. The **inputs** are the street objects in CityEngine and attributes A, B, C, D, E, F. The **output** segments the street object into sections depending on its width and A, B, C, D, E, F attribute and populates the street with colors, lanes, objects, extrusions and setbacks depending on the typology tied to the attribute and width. 

### Surface Types

We coded five main surface types and several offshoot sub-types of those primary surfaces. The main types were denoted as A, B, C, D, E and F within the code and sub-types were labeled as A1, A2 etc.

![surfacescapes_typologies](rules/surfascapes/examples/Surfacescapes_Markdown_Typologies.PNG)

>**Type A** had similar functionality to a service road. It was wide enough for emergency vehicles like fire trucks, and was designed to be sturdy for heavy use, but porous with as light a structural touch as possible.

>**Type B** was used for edge conditions in the site where there were no parks, commercial or residential buildings but there did need to be strong mobility infrastructure. This was primarily for public transit and bike use to circumvent the neighborhood but access the ferry station to Manhattan.

>**Type C** made up the largest portion of the mobility infrastructure. Its primary purpose was for human powered mobility options as well as large portions of the area devoted to programmable space where the Balanced Spaces and Economics teams could inhabit their projects. In addition to these primary uses, it was wide enough for emergency vehicles and trucks to access if necessary. 

>**Type D** had a mixture biking mobility infrastructure and walking infrastructure space.

>**Type E** was a mix of exclusively programmable and pedestrian space.

>**Type F** was a new kind of "street" a surfacescape not designed primarily for human use, but for the natural world. It could have many functions. A place for animals and bugs, an area for water to drain to/through and be absorbeds, replenishing aquifers, an interstitial space between the coast and development to allow natural fluctuations in water levels to work with the earth instead of against it.
