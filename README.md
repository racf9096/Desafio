# Desafio

Archivos con solución a desafio técnico de Seguros.

En este se encuentra un notebook, con un código que genera un modelo de clasificación usando arboles de decisión. Además se realizan cálculos de Riesgos para determinar el precio base del seguro por cliente. Para ver el detalle de lo solicitado ver archivo "desafio_tecnico.pdf".
En cuanto a código, se inicio con la lectura del archivo "data_desafio_seguros", el cual se transformo sus datos a numéricos, y categóricos en caso de diversos valores en un atributo.
Posteriormente, se prepararon los datos, haciendo un split de 70% de datos de entrenamiento y 30% de prueba.
Una vez generado el modelo de clasificación, se evaluo con los datos de prueba mostrando métricas, matriz de confusión y curva ROC. Luego se guardó el modelo en un archivo ".dot", con el cual se puede generar el arbol de decisión como png (Este se encuentra en archivo "Decision_tree_desafio.png").
Finalmente se crearon las funciones que permiten calcular los valores solicitados en el desafio.
