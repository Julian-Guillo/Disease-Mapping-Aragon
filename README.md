# Disease-Mapping-Aragon
Informe en rmarkdown con datos espaciales de fallecimiento por enfermedad isquémica en Aragón, por municipio. Se ha ajustado un modelo jerárquico espacial bayesiano para la estimación del riesgo de fallecimiento por municipio.
El modelo ajustado es el modelo de [Besag,  York y Mollié](https://link.springer.com/article/10.1007/BF00116466), y se ha codificado tanto en [WinBUGS](https://en.wikipedia.org/wiki/WinBUGS)
como en [INLA](https://www.r-inla.org/). 
Además, el informe incluye un mapa interactivo creado con la librería [leaflet](https://rstudio.github.io/leaflet/).  

Puedes ver el informe renderizado [aquí](https://julian-guillo.github.io/Disease-Mapping-Aragon/).
