# TFG
Este repositorio contiene el código utilizado para la realización del proyecto de final de grado accesible aquí: (link)
La función del software es cargar y evaluar diferentes embeddings. Además en (.py de diccionarios) hay código para un tratamiento simple de diccionarios que pueden ser utilizados en rotaciones de embeddings para replicar las pruebas mostradas en la memoria.

#Cómo utilizarlo
Para ejecutar este código necesitaras tener instalada una versión de Python superior a 3.0 y los paquetes utilizados, visibles en los import. Los archivos tienen que abrirse con Jupyter Notebook. Además, tendrás que tener los embedding que quieras probar en un formato de texto (no .bin). 
En (archivo principal) se encuentra todo el código referente a la evaluación de embeddings de sentidos. Antes de empezar a evaluar hay que cargar los embedding. Para ello hay que ralizar una llamada a la función load_embedding() con la ruta al archivo del embedding por cada embedding que se desee cargar. Una vez cargados los embedding, se pueden empezar a comparar.
