# DecisionTree-and-Random-Forest
Practicas de estos modelos, archivos y recordatorios utiles para predecir con este algoritmo.

![01](https://user-images.githubusercontent.com/94582879/161449025-3fa45eb3-bd47-483a-ab8c-26fea6a8c23e.jpg)

## Parametros a utilizar con Sklearn para arboles de decisión:

![01](https://user-images.githubusercontent.com/94582879/173691604-3eb15972-1123-48e4-806a-e8e92ccf7760.jpg)

Criterion: Se define la medida de selección que se utilizará para seleccionar el criterio de división que divide los datos de la mejor manera posible. Por defecto este parámetro viene configurado con “gini” que vendría siendo el índice de Gini, en caso en que se quiera configurar este parámetro como ganancia de información se deberá igualar este parámetro como “entropy”.

Splitter: Es la estrategia utilizada para la división en cada nodo, en esta caso se cuenta con dos opciones “best” que sería la mejor división, y “random” que elige de manera aleatoria la separación. Por defecto se encuentra seleccionada la opción “best” que por supuesto es la mejor opción.

Max_depth: Se refiere a la profundidad máxima del árbol. Si no se coloca ningún valor entonces el algoritmo selecciona de manera automática los nodos de manera que los expande hasta que todas las hojas estén puras o hasta que todas las hojas contengan menos datos. Si hacemos esto es muy probable que el algoritmo caiga en sobreajuste, por lo que se recomienda aqui variar el valor y ver el que mejor se adapte a nuestro analisis.



## Créditos y autor
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nestor_Diaz-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/contadornestordiaz/)
