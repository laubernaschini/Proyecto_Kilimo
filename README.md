## **Ejercicio Kilimo**

*Problema planteado:* Desarrolle un pipeline completo para predecir el rendimiento de cultivos de maíz usando datos históricos de campo, clima y manejo agronómico.
El objetivo es crear una solución que permita a los agricultores tomar decisiones informadas sobre sus cultivos.


1. **Data Engineering**

   1.1. Pipeline de Datos: (notebook Pipeline_datos)

   Se cargó el dataset principal

   Se realizó una exploración, limpieza y curación de datos:
   
      - Eliminación de columnas irrelevantes
      - Filtrado de datos
      - Identificación de datos faltantes, nulos y atípicos
      - Exploración visual de variables categóricas y numéricas 
      - Análisis estadísticos simples de variables cuantitativas relevantes
      - Correlación entre variables predictoras cuantitativas 
      
   1.2. Feature Engineering: (notebook Feature_Engineering)     
      
   Se incorporaron al dataset 3 variables 
   
      - Fertilizantes ("N_kg/ha"), obtenida a partir de la base de datos de FAOSTAT
      - Carga de pesticidas "pesticide_load", variable categórica creada a partir de la variable "pesticides_tonnes"
      - Continente "continent", variable categórica que engloba los países de la columna "Area"
      
   1.3. Transformación de variables: (notebook Feature_Engineering)
   
   Estandarización, codificación y reducción de la dimensionalidad de los datos
  
      - Estandarización de variables numéricas
      - Codificación de variables categóricas 
      - Reducción de dimensionalidad de los datos (variables de componentes principales)
      
      
      
2. **ML Engineering:**

   2.1 Modelos: (notebook Feature_Engineering) 
   
   Modelos regresivos, validación, selección de hiperparámetros
   
      - Regresión lineal  
      - Random Forest 
      - Selección de hiperparámetros del mejor modelo


      
      
      
      
      
      

      
      
      

