# Actividad Integradora 1. Predicción casos COVID

_Generar un modelo de regresión lineal para proyectar casos nuevos de COVID en el tiempo_

## Requerimientos ⚙️

El código está hecho en un Jupyter Notebook con Python 3. Se pueden instalar las dependencias usando el archivo de repositorio requirements.txt

> pip install -r requirements.txt

* requests
* beautifulsoup4
* pandas
* numpy
* matplotlib

## ¿Cómo funciona? 📄

### 1. Recolección de datos 📦

La página [world o meter](https://www.worldometers.info/coronavirus/) muestra datos de casos de covid durante el tiempo. Dentro del HTML renderizado existe una gráfica de casos de COVID en el tiempo, de aquí se extraen los datos usando la biblioteca **beautifulsoup4**

### 2. Procesamiento de datos 🔧

Al usar el origen de datos de las gráficas, los datos ya vienen preprocesados, de manera que no hay que hacer limpieza de datos, sólo organizarlos para usarlos en estructuras de **pandas**

### 3. Selección de modelos 📈

Para este proyecto se sabe por adelantado que se usará un modelo de regresión lineal 

### 4. Entrenamiento de modelos 🛠️

Usando **sklearn**, se elige el modelo **LinearRegression**, se separa el dataset 80/20 y se genera el ajuste del modelo

### 5 - 7. Evaluación de modelo, afinación de parámetros y predicciones 🚀

Con el modelo generado, se muestra en el notebook una gráfica con los datos reales y los datos de la predicción del modelo. No se busca hacer un ajuste más por el momento con una regresión lineal, pero tal vez un modelo más complejo sirva para mejorar la predicción.

## Autores ✒️

_Equipo 2_

* **Eugenio González**
* **Iñaki Janeiro**
* **Aglahir Jiménez**
* **Fernando Isunza**
* **Juan Juárez**