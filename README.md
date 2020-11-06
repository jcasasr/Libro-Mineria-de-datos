# Minería de datos: Modelos y algoritmos
## Material adicional del libro **Minería de datos: Modelos y algoritmos**
### Por Jordi Gironès, Jordi Casas, Julià Minguillón y Ramon Caihuelas

<a href="http://www.editorialuoc.cat/mineria-de-datos"><img src="https://www.editorialuoc.cat/media/cache/a8/a1/a8a12045c1e742d4005870e8b91cdf3f.jpg" alt="Minería de datos: modelos y algoritmos" height="256px" align="right"></a>

**Este github contiene el código del libro [Minería de datos: algoritmos y modelos](http://www.editorialuoc.cat/mineria-de-datos), publicado por Editorial UOC**

En esta página encontraréis ejercicios prácticos en [Jupyter](http://jupyter.org/) que os permitirán trabajar más a fondo los contenidos aprendidos en el libro [Minería de datos: modelos y algoritmos](http://www.editorialuoc.cat/mineria-de-datos).

La mejor forma de trabajar estos ejercicios es seguir los capítulos del libro, descargarse los archivos de esta página y abrirlos desde un navegador web accediendo a tu instalación Jupyter.

## Introducción
Este libro es el resultado de 10 años de docencia en minería de datos dentro del [Máster Universitario en Ciencia de datos (Data Science)](https://estudios.uoc.edu/es/masters-universitarios/data-science/presentacion) y del [Máster de Inteligencia de Negocio](http://estudios.uoc.edu/es/masters-posgrados-especializaciones/master/informatica-multimedia-telecomunicacion/inteligencia-negocio-big-data/presentacion) de la UOC, a través de los cuales hemos reflexionado junto con nuestros alumnos, la mejor manera de aproximarse al mundo de los algoritmos más habituales en este campo de conocimiento.

[Jupyter](http://jupyter.org/) como herramienta de programación [R](https://www.r-project.org/), [Python](http://jupyter.org/) y [Julia](https://julialang.org/). Especializada en minería de datos, nos ha parecido una plataforma excelente para proponer prácticas en las que el estudiante pueda acompañar la comprensión del contenido del libro.

## Instalación de componentes
Recomendamos los siguientes enlaces para poder instalar los componentes de software necesarios para seguir los ejercicios propuestos:

- [Anaconda](https://www.anaconda.com/products/individual)
- [Lenguaje de programación R](https://www.r-project.org/)
- [Entorno de trabajo Jupyter](http://jupyter.org/install.html)
- [Kernel R para Jupyter](https://irkernel.github.io/installation/)

## Datos de ejemplo
Conjuntos de datos propios empleados en los ejemplos:

- [B2.332_Students.csv](data/B2.332_Students.csv)

## Capítulo 3. Preparación de los datos
En este ejemplo se trabajan funciones de R para explorar visualmente y mediante descriptores estadísticos el juego de datos.

Ejemplos en R:

- [Preparación de los datos](cap03/CH3EJ1-Preparacion-de-los-datos.ipynb)

## Capítulo 6. Extracción y selección de atributos
Este ejemplo muestra como extraer los valores singulares en un conjunto de datos y valorar su representatividad.

Ejemplos en R:

- [Extracción de características](cap06/CH6EJ1-Extraccion-de-caracteristicas.ipynb): En este ejemplo se buscan correlaciones entre las variables y se descubren variables con un mayor peso predictivo.
- [Análisis de componentes principales](cap06/CH6EJ2-Analisis-de-componentes-principales.ipynb): Este ejemplo muestra como extraer los componentes principales en un conjunto de datos y valorar su representatividad.
- [Descomposición en valores singulares](cap06/CH6EJ3-Descomposicion-en-valores-singulares.ipynb): Este ejemplo muestra realizar una descomposición en valores singulares.

## Capítulo 7. Agrupamiento jerárquico
Este ejemplo muestra del agrupamiento jerárquico y los dendogramas.

Ejemplos en Python:

- [Agrupamiento jeràrquico y dendogramas](cap07/CH7EJ1-Agrupamiento-jerarquico.ipynb): En este ejemplo se muestra la base del agrupamiento jerárquico y los dendogramas.

## Capítulo 11. Máquinas de soporte vectorial
En estos ejemplos se muestra cómo utilizar las máquinas de soporte vectorial (SVM) a partir ejemplos en Python y R (paquete de R 'e1071'). Se trabajan los distintos modelos de kernel: lineal, radial, polinomial y sigmoidal. También se comparan los resultados de trabajar con dos dimensiones o con todas.

Ejemplos en R:

- [Máquinas de soporte vectorial](cap11/CH11EJ1-Maquinas-de-soporte-vectorial-R.ipynb)

Ejemplos en Python:

- [Máquinas de soporte vectorial](cap11/CH11EJ2-Maquinas-de-soporte-vectorial-Py.ipynb)

## Capítulo 12. Redes neuronales
En estos ejemplos se muestra cómo utilizar las redes neuronales artificiales (NN) a partir ejemplos en Python y R (paquete de R 'neuralnet'). Se ven las distintas posibilidades de una red neuronal: capas, neuronas y criterio de parada.

Ejemplos en R:

- [Redes neuronales (R)](cap12/CH12EJ1-Redes-neuronales-R.ipynb)

Ejemplos en Python:

- [Redes neuronales con sklearn e IRIS](cap12/CH12EJ2-Redes-neuronales-sklearn_IRIS.ipynb): Ejemplo de clasificación mediante redes neuronales empleando sklearn y el conjunto de datos IRIS.
- [Redes neuronales con keras y Fashion-MNIST](cap12/CH12EJ3-Redes-neuronales-keras_FMNIST.ipynb): Creación de una red neuronal para clasificación del conjunto de datos FASHION-MNIST.

## Capítulo 13. Árboles de decisión
Los siguientes ejemplos crean un árbol de decisión con el algoritmo C5.0. Posteriormente se intenta mejorar la calidad con técnicas de boosting, VSD y PCA. También se muestra como evaluar la capacidad predictiva del modelo generado y ejemplos de árboles generados con poda o sin poda.

Ejemplos en R:

- [Creación de un árbol de decisión con el algoritmo C5.0 (R)](cap13/CH13EJ1-Creacion-de-un-arbol-de-decision-C50.ipynb)
- [Mejora del árbol con técnicas de boosting (R)](cap13/CH13EJ2-Mejora-de-arbol-con-tecnicas-de-boosting.ipynb)
- [Capacidad predictiva del modelo generado (R)](cap13/CH13EJ3-Capacidad-predictiva-del-modelo-generado.ipynb)
- [Podado del árbol (R)](cap13/CH13EJ4-Podado-del-arbol.ipynb)
- [Creación de arbol de decisión y mejora con SVD (R)](cap13/CH13EJ5-Creacion-de-arbol-de-decision-y-mejora-con-VSD.ipynb)
- [Creación de arbol de decisión y mejora con PCA (R)](cap13/CH13EJ6-Creacion-de-arbol-de-decision-y-mejora-con-PCA.ipynb)

Ejemplos en Python:

- [Creación de un árbol de decisión con el algoritmo CART (Python)](cap13/CH13EJ7-Creacion-de-un-arbol-de-decision-CART.ipynb)

## Capítulo 15. Combinación de clasificadores
En los siguientes ejemplos se mejora el resultado de un clasificador mediante las técnicas de Bagging, Boosting, Random Forest y Stacked.

Ejemplos en R:

- [Bagging](cap15/CH15EJ1-Bagging.ipynb)
- [Boosting](cap15/CH15EJ2-Boosting.ipynb)
- [Random Forest](cap15/CH15EJ3-Random-Forest.ipynb)
- [Stacked](cap15/CH15EJ4-Stacked.ipynb)
