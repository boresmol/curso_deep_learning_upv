# Curso Deep Learning UPV
Repositorio para el curso de "Deep Learning aplicado a señales e imágenes".

En este repositorio se añade todo el código realizado en el curso de "Deep Learning aplicado a señales e imágenes" en la Universitat Politècnica de València. En este curso se tratan los siguientes temas:

    - Fundamentos de las redes neuronales
    - Aprendizaje y evaluación en redes neuronales
    - Introducción a TensorFlow y Keras
    - Fundamentos de las redes neuronales convolucionales
    - Desarrollo de CNN usando Keras
    - Arquitecturas CNN existentes y transferencia del conocimiento
    - Aprendizaje profundo aplicado a texto y secuencias temporales
    - Explicación de los proyectos propuestos y detalles teóricos
    - Hardware/software necesario para Deep Learning

El repositorio contiene un notebook por cada una de las 7 sesiones del curso. A continuación se hace un breve resumen del contenido de cada uno de los notebooks:

-**P1_Fordward_y_Backpropagation__Evaluando_el_perceptron_con_funciones_logicas_solucionado.ipynb**: En esta primera práctica        se desarrollan los algoritmos fundamentales del aprendizaje profundo: fordward y backpropagation 'from scratch', es decir, usando únicamente *Numpy*.

-**P2_Redes_Neuronales_empleando_TensorFlow_Clasificando_digitos_manuscritos_results _1_.ipynb**: Se trabajan los mismos aspectos que en la anterior práctica pero esta vez usando la librería *Tensorflow*.

-**P3_Redes_Neuronales_empleando_Keras_Estudio_de_hiperparámetros_mediante_Keras_Tuner.ipynb**: En primer lugar, se replican las prácticas 1 y 2 pero esta vez usando una biblioteca de más alto nivel, *Keras*. También se crea una red neuronal profunda con el objetivo de clasificar el famoso dataset *MNIST*, ajustando los hiperparámetros de la red por "prueba y error". Por último, se hace uso de la herramienta *Keras Tunner* con el fin de automatizar el ajuste óptimo de hiperparámetros.

-**P4_CNNs_con_Keras_para_la_clasificación_de_imágenes (1).ipynb**: Se utiliza el dataset *CIFAR 10* para realizar tareas de clasificación con este. En primer lugar, se realiza un preprocesamiento de las imágenes del datset para luego clasificar estas mediante *Redes neuronales Convolucionales*

-**P5_Transferencia_del_conocimiento_data_augmentation_y_visualizacion_interna_de_una_CNN**: Trabajar con arquitecturas CNN previamente propuestas en la literatura para la clasificación de imágenes y para el entrenamiento de nuevos modelos a partir de los ya existentes haciendo uso de técnicas las técnicas de *transferencia del conocimiento* y *fine-tunnning*. Además, se hará uso de técnicas de *Data Augmentation* como medida para mitigar el *overfitting* y se visualizarán tanto las activaciones a la salida de ciertas capas de la red como los pesos de los filtros de la mismas.

-**P6_Word_embeddings,_text_classsification___generation.ipynb**:En esta práctica se introducen ciertos aspectos del *NLP*: se discute sobre las ventajas y desventajas de las diferentes representaciones de las palabras y sobre distintos métodos de clasificación. Además, se propone una *Red Generativa de texto* basada en *LSTM*.

-**micro_proyecto_pokedex**: Se realiza un microproyecto como prueba de evaluación del curso. En este se propone un clasificador que dada una imagen distinga entre 5 tipos distintos de pokemons. Se realiza todo el *pipeline* necesario para una tarea de este tipo: visualización, preprocesamiento, *Data Augmentation* , creación de una CNN y evaluación de la red.
