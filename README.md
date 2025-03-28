# Trabajo Final - CODERHOUSE

- Alumno: Agustin Alsop

## Actividad 1

Deberás entregar un dataset del estilo texto (libro, paper, documento, colección de tweets, etc) donde se desarrollen de mínima dos de las tareas más usuales de preprocesamiento de NLP: steeming, tokenización, remoción de stopwords, lematización, etc.

### Resolución

El corpus seleccionado es un PDF de un diccionario de lunfardo argentino. El objetivo es leer este archivo y aplicar procesamiento de texto a las definiciones de las palabras, transformándolas en vectores. Con esta representación vectorial, se desarrollará una pequeña aplicación en la que el usuario ingresa una definición y el sistema devuelve la palabra que mejor se ajuste, basándose en la similitud entre la definición proporcionada y las definiciones almacenadas en el diccionario.

## Actividad 2

- Considerando lo visto dentro de las clases de redes neuronales seleccionar un dataset de trabajo (puede ser nuevo o de los preparados para learning estilo MNIST).

- Cargar el dataset usando la función adecuada.

- Hacer una análisis exploratorio e identificar al menos tres insights sobre el mismo.

- Entrenar una red neuronal sencilla al menos dos capas (puede ser convolucional o recurrente).

- Plantear conclusiones.

### Extra

Como se opto desarrollar mas esta actividad se agrega lo siguiente

Para trabajo final si se opta por Deep Learning debe adicionarse alguna de las siguientes tareas:

- Adicionar al menos dos capas a la red para mejorar su rendimiento.

- Comparar los resultados contra el modelo sencillo. Dimensionar mejoras.

### Resolución

Para la realización de este trabajo se utilizó el set de datos de cifar10, la idea es entrenar una red neuronal que pueda diferenciar entre las distintas clases que se encuentran en el data set
