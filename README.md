# TFM-MUIA-2024
- Trabajo de Fin de Máster
- Máster Universitario en Inteligencia Artificial (MUIA)
- Título: Reconocimiento de Emociones a Partir de Voz mediante Shallow ANN
- Fecha: Julio- 2024
- Autor(a): Javier Meitín Moreno
- Tutor(a): Javier De Lope Asiaín

## Estructura del repositorio
- Memoria TFM.pdf
- TFM_Modelo_Shallow_ANN_Final.ipynb: Programa con el modelo propuesto.
- TFM_Métodos_de_prueba.ipynb: Programa auxiliar empleado para realizar experimentos y pruebas de optimización de hiperparámetros.

## Resumen
En este trabajo se propone el diseño y desarrollo de una red neuronal de una sola
capa oculta capaz de reconocer emociones a partir de la voz. El clasificador es entre
nado y evaluado con espectogramas mel de dimensiones 90x98 generados a partir de
los archivos de audio de la base de datos pública RAVDESS. Dicho conjunto esta for
mado por 8 emociones (neutralidad, calma, felicidad, tristeza, enojo, miedo, disgusto
y sorpresa). La red neuronal es capaz de clasificarlos con un 68,81% de precisión
sin la necesidad utilizar otros algoritmos complementarios como aumento de datos.
Además, se ha comprobado que seleccionando los 4000 pixels más importantes con
Gradient Boosting, la precisión del modelo puede mejorar al 71,09%. Estos resul
tados, aunque no superiores a los de otros trabajos anteriores similares, permiten
medir y ratificar el alcance y potencial de este tipo de redes neuronales en el ámbito
del aprendizaje automático.

## Abstract
In this work, the design and development of a single hidden layer neural network
capable of recognizing emotions from speech is proposed. The classifier is trained
and evaluated using Mel spectrograms of dimensions 90x98 generated from audio fi
les from the public RAVDESS database. This dataset consists of 8 emotions (neutral,
calm, happy, sad, angry, fearful, disgusted, and surprised). The neural network is
able to classify them with a precision of 68,81% without the need to use other com
plementary algorithms such as data augmentation. Additionally, it has been found
that by selecting the 4000 most important pixels with Gradient Boosting, the model’s
precision can improve up to 71,09%. These results, although not higher than those
of some similar previous works, allow for measure and confirmation of the scope and
potential of this type of neural network in the field of machine learning.
