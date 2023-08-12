# Entregable: Definición de la línea base y alcance del proyecto
Instructor: Carlos Mejia
Student: Gabriela Sánchez

La línea base (modelo de referencia) debe ser un modelo simple que actúe como una comparación y sea fácil de explicar. Además, la línea base debe basarse en el conjunto de datos para crear el modelo real.

En este entregable se identifica la naturaleza del dataset que ha sido asignado, y se responden las siguientes preguntas:

1. ¿Qué problema aborda?
2. ¿Qué soluciones (notebooks) ya tiene desarrollados?
3. ¿Cuál de todas las soluciones contiene lo mínimo necesario para
poder entrenar y guardar un modelo?

El problema que aborda es de prevención de ataques:

![Alt text](stroke.png)

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

El data se llama: "healthcare-dataset-stroke-data"

Existen múltiples soluciones desarrolladas, dentro de las cuales revisé particularmente las dos siguientes:

- stroke-prediction-effect-of-data-leakage-smote.ipynb
- beginner-friendly-end-to-end-ml-project-enjoy.ipynb

La que tomé como base es la última "beginner-friendly-end-to-end-ml-project-enjoy.ipynb".

El alcance del modelo es:
- Tomar el dataset con los inputs para entrenar un modelo que pueda predecir la probabilidad de tener un ataque considerando algunas caracterírsticas de los pacientes/personas.