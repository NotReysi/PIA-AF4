# Actividad Fundamental No. 4 - Gestión y Normalización de Datos con Python
>En este repositorio se muestra el proceso que pasamos para realizar la Actividad Fundamental 4 para la materia Programación para Inteligencia Artificial.

Se seleccionó una base de datos pública para esta tarea, con el objetivo de normalizarla y hacer que sea apta para un entrenamiento de Machine Learning. En este caso, encontramos una base de datos que contenía información sobre la renta de airbnb y se necesió cambiar algunos caracteres y eliminar las columnas que no servían para lograr nuestro objetivo
=======
# Actividad Fundamental N.º 6 – Implementación de un Modelo Supervisado en Python

>En este repositorio se muestra el proceso que pasamos para realizar la Actividad Fundamental 6 para la materia Programación para Inteligencia Artificial.

Para esta tarea se seleccionó un dataset público, con el objetivo de limpiarla y normalizarla para que sea apta para un entrenamiento de Machine Learning. En este caso, tenemos un dataset que contiene información médica de pacientes. Generamos un modelo que logra predecir el coste médico de la persona.
>>>>>>> af6/main

## Requisitos e Instalación 🚀
Para este trabajo se utilizó Python 3 y las siguientes librerías:
- ```pandas```
- ```numpy```
- ```scikit-learn```
<<<<<<< HEAD

## Pasos para Clonar
En la terminal de git agregar los siguientes comandos:

**Bash**
```
git clone https://github.com/NotReysi/PIA-AF4
cd PIA-AF4
Crear y Activar el Entorno Virtual (Recomendado con Conda)
```
Luego entrar a Anaconda y crear un nuevo entorno que contenga las 3 librerias anteriormente mencionadas
Finalmente abrir vs code desde Anaconda.

## Uso y Ejecución del Sistema💻
El sistema se ejecuta mediante el script principal, main.py, ejecutando la siguiente cadena de procesos de forma modular:
- **gestion.py:** Carga los datos, realiza la limpieza inicial, corrige formatos (elimina $, reemplaza , por .), y elimina filas con valores nulos.

- **normalizacion.py:** Aplica One-Hot Encoding (Dummies) a las variables categóricas (city, area) y escala todos los datos numéricos a un rango de [0, 1] usando MinMaxScaler.

- **train.py:** Divide el dataset normalizado en conjuntos de Entrenamiento (80%), Validación (10%) y Prueba (10%) para simular la preparación de un modelo predictivo.

- **gestion.py:** Exporta el DataFrame final, normalizado y completo, a un nuevo archivo.

Archivo de Salida
Al finalizar la ejecución, se generará el archivo:
**airbnb_normalizado.csv**
=======
- ```matplotlib```
- ```seaborn```
>>>>>>> af6/main

## Autores 👥
- Orlando Alvarado Vargas
- Diego Alonso Carrillo Castillo
