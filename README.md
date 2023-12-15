# Pokemon_Image_Classifier

La idea principal del transfer learning es tomar prestados datos etiquetados o conocimientos extraídos de algunos dominios relacionados para ayudar a un algoritmo de aprendizaje automático a lograr un mayor rendimiento en el dominio de interés. Por ello, he empleado la red neuronal convolucional de 53 capas de profundidad, MobileNet-v2, desarrollada por Google. Esta red ha sido entrenada con más de un millón de imágenes procedentes de la base de datos de ImageNet. La red preentrenada puede clasificar imágenes en 1000 categorías de objetos (por ejemplo, teclado, ratón, lápiz y muchos animales). Como resultado, ha aprendido representaciones ricas en características para una amplia gama de imágenes, que me han sido de gran utilidad a la hora de llevar a cabo mi proyecto. Dicho proyecto ha consistido en la creación de un modelo capaz de clasificar imágenes, distinguiendo qué inicial de primera generación de Pokémon aparece en ellas. Sin embargo, no todo ha acabado con la generación del modelo, ya que, una vez almacenado, lo he desplegado en forma de aplicación web gracias a la librería Flask, especializada en el marco del desarrollo web.

**Instalar todos los paquetes desde un archivo requirements.txt usando pip y Python:**<br>
```pip install -r requirements.txt```




