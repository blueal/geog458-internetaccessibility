# Internet Access in King County
[blueal.github.io/geog458-internetaccessibility](https://blueal.github.io/geog458-internetaccessibility/)

## Group Members
* Alex Friedberg (blueal)
* Nichapa Lertviwatkul (nlertv)
* Holden Bailey (Synometry)
* Vincent Le (vinceleuw)
* Ali Basbeth (LostGovernment)

## Project Proposal and Significance

We, group AA2, will be researching and analyzing internet accessibility for our final project. Access to the internet is foundational for participating in modern America, yet it is not equal in all parts of the country. This can be seen most easily in many rural towns that are disregarded by the various internet service providers (ISPs) such as Comcast, Century Link, etc. We plan to produce a resource that highlights significant patterns in the distribution of internet access to draw attention to the issue and educate the public. Additionally, locales with sub-par internet access represent potential customers for ISPs. 

We have decided to narrow down our studies in King County. We are trying to make a distinction between the rural and the urban areas' internet access.  

![Map1](.img/provider.png)

## Target Audience

Our target audience is therefore two-fold. The media we create will serve communities typically ignored by major broadband companies. It will also act as an investment guide to the very same companies that brought about this situation in the first place.  

## Primary Functions

To accomplish these goals, we will make an interactive web map by the end of the quarter. It will afford the sort of interaction one typically finds with these kinds of maps: panning, zooming, selection of geographic units (state, census tract, etc.), among others. This map will depict the geographic distribution of internet access. Because “internet access” is a rather high-level variable – a purely quantitative or qualitative representation would not perfectly encapsulate it – we will be settling for a stand-in variable, “fastest available internet speed”, which we feel is the best available for the scope of this assignment. We want to display this through generic digital geographies with a monochrome base map from MapBox. We will be zooming in and centering on Washington State with Mercator projection. For the thematic layer, we plan to use choropleth maps with the data from querying https://opendata.fcc.gov/resource/hicn-aujz.csvLinks to an external site.. Most of our data is vector data with data attributes such as, max advertized service speed, blockid, and count. 
![Map](.img/downloadspeed.png)

To contextualize our data, we plan on having an adjacent, introductory webpage. This webpage will feature some of the highlights of our research into the topic of internet accessibility, namely excerpts from a Vice article located hereLinks to an external site. and snapshots from the FCC’s own map of broadband data. 

## Data Source

We will source our data directly from the Federal Communications Commission (FCC), which is available at https://broadbandmap.fcc.gov/#/data-download. (Links to an external site.) This dataset contains comprehensive, block-level information about internet access. The only obstacle to its use is having to query the FCC’s API, and the coding of many of the variable names, such as “u_2” and “hoconum”. 

## Broader Impacts

We do expect our project to have a negative impact on service providers. This is because service providers are selective in where they offer different speeds, and it is in their best interest to keep this disparity hidden from their customer base. Customers may be upset to find their provider offers 1000+Gbps in the town over, whereas they can only get a max of 35Mbps. 

## Applied Libraries 
- mapbox
- github 

## Acknowledgements 
For this project, we would like to express our special thanks of gratitude to Professor Bo and Steven Bao for giving us guideance and help throughout the project.