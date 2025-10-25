# Clasificación de Opiniones - PLN
Dentro del código se implementaron los archivos de entrenamiento y prueba,
luego se analizaron sus datos para determinar si contenían valores vacíos
(null), pero no se encontró ninguno. Luego de esto se generó un archivo de
envío con las columnas seleccionadas: declaracion, palabras_clave, tweet,
respuesta_mayoria_5_etiquetas y respuesta_mayoria_3_etiquetas.

## Modelado
Al modelo le tomó un tiempo el poder entrenarse por completo, debido a la
enorme cantidad de datos existentes, incluso, el modelo no tomó el total
de los datos en el archivo, tan solo tomó una parte. Esto debido a un
límite que contiene el modelo *LogisticRegression*.

# Resultados
<img width="1005" height="51" alt="image" src="https://github.com/user-attachments/assets/321cd560-4ef9-4da9-b051-c9506302cdc7" />
