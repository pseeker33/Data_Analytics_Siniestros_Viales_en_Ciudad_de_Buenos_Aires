
# <h1 align=center> **PROYECTO DE ANALISIS DE DATOS** </h1>

# <h1 align=center>**`Analítica de los Siniestros Viales en la Ciudad de Buenos Aires (2016-2021)`**</h1>

<p align="center">
    <img src="src/transito_CABA.jpg"  height=300>
</p>

# <h1 align=center>**`Hoover Pedro Zavala`**</h1>
# <h3 align=center>**`Data Engineering | Data Science | BI & Data Analytics`**</h3>
<hr> 
<br>

<br>

## Tabla de Contenido

1. **[Introducción](#1-introduccion)**
2. **[Objetivo y Alcance](#2-objetivo-y-alcance-del-proyecto)**
3. **[Estructura del Repositorio](#3-estructura-del-repositorio)**
4. **[Tech Stack](#4-stack-tecnologico-utilizado)**
5. **[Implementaciones Realizadas](#5-implementaciones-realizadas)**
6. **[Cierre](#6-gracias-por-su-atencion)**


#
<br>

## 1. Introducción 

De acuerdo con la OMS (2016), los accidentes de tránsito son la octava causa de muerte en el mundo.  
  
<img src="src/MUERTES OMS.png"  height=300>  <br>

Por esta preocupación la Asamblea General de las ONU proclamó a nivel mundial el periodo 2011 – 2020 como el “Decenio de Acción para la Seguridad Vial”.  
A partir de esta iniciativa se propusieron 12 medidas en base a diversas investigaciónes y de experiencias del pasado que demostraron ser efectivas al atacar de manera sistémica el problema de la siniestralidad vial
En tre esas medidas se destacan: 

1.  Definir la naturaleza y costo de las muertes en vias publicas.
2.  Adquirir el compromiso y soporte de los encargados de tomar las decisiones.
3.  Establecer una política de seguridad vial a nivel nacional.
4.  Definir roles institucionales y responsabilidades.
5.  Identificar los problemas de seguridad vial.
6.  Establecer objetivos de seguridad vial.
7.  Formular una estrategia o un plan de acción.
8.  Asignar responsabilidades de las medidas a implantar.
9.  Asegurar la financiación de las medidas.
10. Aplicar medidas de efectividad conocida y documentada.
11. Monitorear el desempeño de las medidas.
12. Estimular la investigación y el desarrollo de capacidades.

Tomando varias o todas la medidas antes mencionadas, corresponde a la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires delinear un plan sistemico que tome cuerpo en un Sistema de Gestión de la Seguridad Vial para la  ciudad.

<span style="float:right;">[arriba](#tabla-de-contenido)</span> 

<br>

## 2. Objetivo y Alcance del Proyecto

En cuanto al trabajo que nos concierne, el Observatorio de Movilidad y Seguridad Vial (OMSV),  centro de estudios que depende de dicha secretaria, nos encomendó la elaboración de un proyecto de análisis de datos para los siniestros viales en la Ciudad de Buenos Aires.  

Para ello, nos disponibilizan un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021.  

Entonces nuestro objetivo es el de, a partir de dicha fuente de datos, y aplicando técnicas de preparacion, análisis y visualización interactiva de datos, generar y brindar a la OMSV de informacion significativa junto con las recomendaciones para cada caso, para ser usada como `una herramienta adicional de apoyo en la toma de decisiones` de las autoridades locales encargadas de adoptar las medidas necesarias para disminuir la cantidad de víctimas fatales en siniestros viales.

<br>

## 3. **Estructura del Repositorio**

<br>
<p align="left">  
    <img src="./src/estructura_repo.png"  height=350>    
</p>

<br>

El repositorio contiene los siguientes elementos:  

**`Carpeta 'notebooks'.-`** contiene todas las implementaciones realizadas   
* **`'data_cleaning.ipynb'`**: implementación de la limpieza de los datos.
* **`'data_transformation.ipynb'`**: implementación de la implementacion de las modificaciones hechas en el dataframe.
* **`'EDA.ipynb'`**: implementación del analisis exploratorio de datos.

**`Carpeta 'data'`**: Contiene el dataset crudo mas los dataframes creados a apartir de las implementaciones ya mencionadas.

**`Archivo 'dashboard.pbix'`**: Contiene un archivo en formato öwer Bi del dashboard implementado.

**`Archivo 'ReadMe.md`**: El archivo actual.

**`'Carpeta src'`**: Carpeta fuente del archivo actual.

<br>

<span style="float:right;">[arriba](#tabla-de-contenido)</span> 

<br>


## 4. Stack Tecnologico Utilizado  
 
   ![Static Badge](https://img.shields.io/badge/PYTHON%203-%233776AB?logo=python&labelColor=%231F1F1F)  
   ![Static Badge](https://img.shields.io/badge/JUPYTER%20NOTEBOOK-%23F37626?style=plastic&logo=jupyter&labelColor=%235C5C5C)  
   ![Static Badge](https://img.shields.io/badge/PANDAS-%23F5F5F5?style=plastic&logo=pandas&labelColor=%235C5C5C)  
   ![Static Badge](https://img.shields.io/badge/NUMPY-%234DABCF?style=plastic&logo=numpy&logoColor=%234DABCF&labelColor=%235C5C5C)  
   ![Static Badge](https://img.shields.io/badge/POWER%20BI-%23F2C811?style=plastic&logo=powerbi&logoColor=%23F2C811&labelColor=%235C5C5C)


## 5. **Implementaciones Realizadas** 

### Data Cleaning

Se realizaron tareas de importacion de librerias, carga del dataset  
Se realizaron analisis sobre todas las variables significativas   
Se confecciono un informe escrito sobre los resultados obtenidos en la etapa de analisis  

<span style="float:right;">[arriba](#tabla-de-contenido)</span> 

<br>

### Data Transformation

Se realizaron tareas de importacion de librerias, carga del dataset  
Se realizaron analisis sobre todas las variables significativas   
Se confecciono un informe escrito sobre los resultados obtenidos en la etapa de analisis  

<span style="float:right;">[arriba](#tabla-de-contenido)</span> 

<br>

### Analisis Exploratorio de Datos

Se realizaron tareas de importacion de librerias, carga del dataset  

Se realizaron analisis sobre todas las variables significativas de los siguientes datasets:  
* `'internet_fijo_penetracion_por_provincia_100_hogares_trimestral.csv':`  

Se confecciono un informe escrito sobre los resultados obtenidos en la etapa de analisis  

A continuacion se muestra la organizacion general del EDA (archivo `'./src/eda.png'`)

<span style="float:right;">[arriba](#tabla-de-contenido)</span> 

<br>

### Indicadores Clave de Rendimiento

A continuación se presentan los 8 KPIs propuestos y sus métricas asociadas:

KPI 1: Aumentar las reseñas de usuarios nuevos en un 10% con respecto al año anterior  
KPI 2: Aumentar la cantidad de restaurantes nuevos reseñados en un 5% con respecto al año anterior  
KPI 3: Aumentar la cantidad de reseñas por restaurante en un 10% anual con respecto al año anterior  
KPI 5: Aumentar el promedio de calificaciones de los restaurantes en un 5% con respecto al año anterior  
KPI 6: Reducir en un 10% la cantidad de restaurantes de los que obtuvo reseñas negativas con respecto al año anterior  

<span style="float:right;">[arriba](#tabla-de-contenido)</span> 

<br>

## 6. Gracias por su atención
Te parecio interesante el proyecto? No olvides [regalarnos](https://github.com/pseeker33/Data_Analytics_Siniestros_Viales_en_Ciudad_de_Buenos_Aires/stargazers) una ⭐.  
Tienes una idea en mente o encontraste algun bug? Por favor abre un [issue](https://github.com/pseeker33/Data_Analytics_Siniestros_Viales_en_Ciudad_de_Buenos_Aires/issues) o inicia una [discusion](https://github.com/pseeker33/Data_Analytics_Siniestros_Viales_en_Ciudad_de_Buenos_Aires/discussions).  

**Usa mis redes para contactarme:**  
[![X (formerly Twitter) URL](https://img.shields.io/twitter/url?url=https%3A%2F%2Ftwitter.com%2Fpseeker222&label=%40pseeker222)](https://twitter.com/pseeker222)
[![Follow us on LinkedIn](https://img.shields.io/badge/LinkedIn-pseeker-blue?style=flat&logo=linkedin&logoColor=b0c0c0&labelColor=363D44)](https://www.linkedin.com/in/hoover-zavala-63a64825b/)  


<span style="float:right;">[arriba](#tabla-de-contenido)</span> 