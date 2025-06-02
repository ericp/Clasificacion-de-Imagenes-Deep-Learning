# Clasificacion-de-Imagenes-Deep-Learning
Proyecto de clasificación de imágenes con redes neuronales convolucionales

Durante esta práctica he desarrollado múltiples modelos de clasificación de imágenes multiclase aplicando técnicas modernas de Deep Learning. El objetivo es evaluar diferentes enfoques y comprobar su impacto en la precisión sobre un conjunto de datos real proporcionado por Intel, compuesto por más de 17.000 imágenes de paisajes y escenas urbanas.

El flujo de trabajo incluye:
* Un modelo base de red neuronal convolucional (CNN).
* Un modelo extendido con capas adicionales y ajuste de hiperparámetros mediante keras_tuner.
* Un modelo de Transfer Learning con VGG16, seguido de fine-tuning para afinar las capas profundas del modelo preentrenado.
* Un modelo basado en técnicas de aumento de datos (ImageDataGenerator) para mejorar la generalización.

  
He utilizado buenas prácticas como la validación cruzada con validation_split, early stopping, y el uso de flow_from_directory para evitar sobrecargar la memoria. 
Todos los modelos han sido evaluados sobre un conjunto de test independiente (seg_test), alcanzando una precisión máxima del 85% con el modelo de aumento de datos.
Este ejercicio no solo me ha servido para consolidar algunos de los conceptos aprendidos durante mi master en IA, sino que también ha producido un flujo de trabajo completo, reproducible y escalable, como parte de mi portfolio profesional como futuro ingeniero de IA.
