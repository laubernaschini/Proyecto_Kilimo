## **Ejercicio Kilimo**

*Problema planteado:* Desarrolle un pipeline completo para predecir el rendimiento de cultivos de maíz usando datos históricos de campo, clima y manejo agronómico.
El objetivo es crear una solución que permita a los agricultores tomar decisiones informadas sobre sus cultivos.


1. **Data Engineering**

   1.1. Pipeline de Datos: (notebook Pipeline_datos)

   - Se cargó el dataset principal

   - Se realizó una exploración, lipieza y curación de datos:
   
       1) Eliminación de columnas irrelevantes
       2) Filtrado de datos, 
       3) Identificación de datos faltantes, nulos y atípicos
       4) Exploración visual de variables categóricas y numéricas 
       5) Análisis estadísticos simples de variables cuantitativas relevantes
       6) Correlación entre variables predictoras cuantitativas 
      
   1.2. Feature Engineering: (notebook Feature_Engineering)     
      
   - Feature Engineering: se incorporaron al dataset 3 variables 
   
       1) Fertilizantes ("N_kg/ha"), obtenida a partir de la base de datos de FAOSTAT
       2) Carga de pesticidas "pesticide_load", variable categórica creada a partir de la variable "pesticides_tonnes"
       3) Continente "continent", variable categórica que engloba los países de la columna "Area"
      
   1.3. Transformación de variables: (notebook Feature_Engineering)
   
   - Estandarización, codificación y reducción de la dimensionalidad de los datos
  
       1) Estandarización de variables numéricas
       2) Codificación de variables categóricas 
       3) Reducción de dimensionalidad de los datos (variables de componentes principales)
      
      
      
2. **ML Engineering:**

   2.1 Modelos: (notebook Feature_Engineering) 
   
   - Modelos regresivos, validación, selección de hiperparámetros
   
       1) Regresión lineal  
       2) Random Forest 
       3) Selección de hiperparámetros del mejor modelo


      
      
      
      
      
      

      
      
      

