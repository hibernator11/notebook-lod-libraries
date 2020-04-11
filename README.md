[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hibernator11/notebook-composite-image/master)

# notebook-composite-image
Jupyter notebook to create a composite image using covers of books from digital libraries.

## Biblioteca Virtual Miguel de Cervantes (BVMC)
This notebook retrieves the covers from the LOD repository of the BVMC. The authors selected in this example are [Miguel de Cervantes](http://data.cervantesvirtual.com/person/40), [Lope de Vega](http://data.cervantesvirtual.com/person/72) y [Calderón de la Barca](http://data.cervantesvirtual.com/person/79)). It is possible to change the authors by changing the identifiers (data.cervantesvirtual.com/person/id) that can be retrieved at data.cervantesvirtual.com.

Then, the notebook creates a composite image with all the covers that is accessible at [easyzoom](https://www.easyzoom.com/imageaccess/acab10e5187b45d8ad802d8d302a4901). 

The example has been limited to retrieve only 100 covers from the repository. However, it is possible to modify the SPARQL to retrieve, for instance, 2500 covers, as in the composite image provided.

## References
This example has been inspired by the the [GLAM Workbench](https://glam-workbench.github.io/), in particular the [notebook to create a composite image from Trove newspaper](https://nbviewer.jupyter.org/github/GLAM-Workbench/trove-newspapers/blob/master/Composite-thumbnails.ipynb).
