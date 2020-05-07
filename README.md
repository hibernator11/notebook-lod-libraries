[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hibernator11/notebook-lod-libraries/master)

[![DOI](https://zenodo.org/badge/254954138.svg)](https://zenodo.org/badge/latestdoi/254954138)


# notebook-lod-libraries
Jupyter notebooks to reuse the Linked Open Data provided by digital libraries.

## Biblioteca Virtual Miguel de Cervantes (BVMC)
This [notebook](bvmc-create-composite.ipynb) retrieves the covers from the Linked Open Data repository of the BVMC, data.cervantesvirtual.com. The covers of the books have been selected based on the authors [Miguel de Cervantes](http://data.cervantesvirtual.com/person/40), [Lope de Vega](http://data.cervantesvirtual.com/person/72) y [Calderón de la Barca](http://data.cervantesvirtual.com/person/79)). It is possible to change the authors by changing the identifiers (data.cervantesvirtual.com/person/id) that can be retrieved at data.cervantesvirtual.com.

Then, the notebook creates a composite image with all the covers that is accessible at [easyzoom](https://www.easyzoom.com/imageaccess/acab10e5187b45d8ad802d8d302a4901). 

The example has been limited to retrieve only 100 covers from the repository. However, it is possible to modify the SPARQL to retrieve, for instance, 2500 covers, as in the composite image provided.

## BNB Linked Data Platform
The [BNB Linked Data Platform](https://bnb.data.bl.uk/) provides access to the [British National Bibliography (BNB)](http://www.bl.uk/bibliographic/natbib.html) published as linked open data and made available through SPARQL services. 

This [notebook](bnb-lod-extraction-map.ipynb) explains how to query the repository and obtain places of publication (fields blt:publication and blt:projectedPublication ) to show an interactive map. Thanks that the works are linked to [GeoNames](https://www.geonames.org/), the records can be linked to external repositories. This notebook obtains information from [Wikidata](https://www.wikidata.org), showing the benefits of Linked Open Data.


## Bibliothèque nationale de France (BnF)
The Bibliothèque nationale de France published [data.bnf.fr](https://data.bnf.fr/) its resources by aggregating information scattered among its various catalogues and the Gallica digital library on dedicated HTML pages. Data.bnf.fr is an open data project based on semantic web standards and tools.

This [notebook](bnf-graph-example.ipynb) shows how to exploit the editions of *les fleurs du mal de baudelaire* using different techniques. It also provides a CSV file as a dataset extracted from the SPARQL endpoint. This example shows how to analyse the information using the network graphs, identifying the most relevant characteristics of the information retrieved.

## References & notes
This [notebook](create-composite-bvmc.ipynb) has been inspired by the the [GLAM Workbench](https://glam-workbench.github.io/), in particular the [notebook to create a composite image from Trove newspaper](https://nbviewer.jupyter.org/github/GLAM-Workbench/trove-newspapers/blob/master/Composite-thumbnails.ipynb).
