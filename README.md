## Citations

Data is obtained from [OpenAlex](https://openalex.org) and then visualised using [3d-force-graph](https://github.com/vasturiano/3d-force-graph), inspired by [uoa-eresearch](https://github.com/uoa-eresearch/citations/).

To visualisate the network a scholar has via papers, authorships, co-authors, institutes, fields and topics.

## Examples from the [Centre of Excellence in Music, Mind, Body and Brain (CoEMMBB)](https://www.jyu.fi/en/research/centres-of-excellence/mmbb):

- [Petri Toiviainen](http://tuomaseerola.github.io/citations/index.html?data=https://openalex.org/a5028633802)

- [Suvi Saarikallio](http://tuomaseerola.github.io/citations/index.html?data=https://openalex.org/a5007264746)

- [Tuomas Eerola](http://tuomaseerola.github.io/citations/index.html?data=https://openalex.org/a5039535349)

- [Martin Hartmann](http://tuomaseerola.github.io/citations/index.html?data=https://openalex.org/A5101493951)


There is a possibility to control the camera as well, so to
[zoom in to Petri Toiviainen's papers](http://tuomaseerola.github.io/citations/index.html?data=https://openalex.org/a5028633802&cam0=0,0,300&cam1=50,20,120&camms=4000&camdelay=1000), where `&cam0=0,0,300&cam1=50,20,120&camms=4000&camdelay=1000` define
 start (cam0) and end position (cam1) of the camera movement defined by duration in ms `camms=4000` and delay `&camdelay=1000`.


## To Do

- Safe API key embedding

- Polishing the interface

- Geography of collaborations (visualisation across the 3D and 2D map) by a unit. Requires hardcoded location data, can only be done by continents via OpenAlex.

