# geometric-deep-learning
En este repositorio, se va a ilustrar el uso de dos librerías bastante conocidas en el aprendizaje profundo geométrico: `Graphein` y `PyTorch Geometric`.

- *Graphein.ipynb*: notebook que muestra la funcionalidad que proporciona `Graphein` para para construir representaciones de grafos y tratar con estructuras de proteínas, moléculas, ARN y redes de interacción proteína-proteína (PPI).
- *GrapheinPyTorch.ipynb*: notebook que expone:
   1. Funcionalidad de la librería `Graphein` para el tratamiento de datos sobre las estructuras de las proteínas.
   2. Funcionalidad de la librería `PyTorch Geometric` para entrenar y evaluar una red neuronal de grafo que toma como entrada un conjunto de datos sobre las estructuras de las proteínas, concretamente, *Protein Structural Change Data (PSCDB)*.

 Dichos notebooks se han ejecutado en Google Colab (Python 3.10.12) haciendo uso de una carpeta "data" que se encuentra subida a este repositorio.
 
 Al ejecutarlos, comprobar que la variable que apunta al directorio donde se encuentra la carpeta data (`path`) se encuentra actualizada.
