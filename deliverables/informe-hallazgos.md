<!--  -->
<h1 align='center'><b>INFORME SOBRE LOS HALLAZGOS DEL ANALISIS EXPLORATORIO DE DATOS</b></h1>

<br>

# Tabla de Contenido

1. <span style="font-size: 1.2em;">**[Contexto del Informe](#contexto-del-informe)**</span>

2. <span style="font-size: 1.2em;">**[Insights Encontrados](#resumen-de-insights-encontrados)**</span>

3. <span style="font-size: 1.2em;">**[Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)**</span>




<br>
<br>

<!-- # <div align="center">Contexto del Informe</div> -->
# Contexto del Informe 

El Observatorio de Movilidad y Seguridad Vial (OMSV), centro de estudios que depende de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires, nos encomendó la elaboración de un proyecto de análisis de datos para los siniestros viales en dicha ciudad.  

El objetivo de este proyecto es generar y brindar a la OMSV, informacion significativa sobre el problema en cuestion, junto con las recomendaciones pertinentes para cada caso, de tal forma que esta informacion sirva como una herramienta adicional de apoyo en la toma de decisiones, sobre las medidas a adoptar para reducir los indices de siniestralidad.  

Para alcanzar este objetivo se disponibilizó un dataset con datos sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021. Se trataron dichos datos aplicando diversos métodos, tanto para prepararlos para su analisis, como para el analisis en sí.

Producto de estos tratamientos se encontraron hallazgos significativos o insights, tales como tendencias y patrones relevantes en áreas clave. A partir de estos insights se extrajeron la conclusiones y recomendaciones pertinentes.  

<span style="float:right;">[arriba](#tabla-de-contenido)</span> 

<br>
<br>

<!-- # <div align="center">Resumen de Insights Encontrados</div> -->

# Resumen de Insights Encontrados

### A continuación se listan los insights encontrados a partir del análisis rrealizado:  

<br>

**Sobre el Nro de Victimas**  
* Mas del 97% de los siniestros causaron la muerte de solo una persona
* Observacion: se muestra una tendecia clara en el numero de muertes que se produjeron an cada siniestro  
<br/>
  
**Sobre los Tipos de Vehiculos Involucrados en SIniestos Viales**
* El tipo de vehiculo causante de mas siniestro fue el auto (32.8%) seguido de los de pasajeros (24.9%)
* El tipo de vehiculo que padecio de mas siniestro fue el moto (44.9%), seguido de los peatones (37.4%)
* Observacion: se muestra una tendecia clara sobre los vehiculos involucrados en siniestros  
 <br/>

**Sobre las Comunas de Buenos Aires**  
* Hay concentracion de siniestros en las comunas de las zonas del Centro-Sur y Este de la ciudad, con mayor preponderancia en esta ultima zona
* Se verifica que ciertas comunas acaparan la mayor cantidad de siniestros.
* De las 15 comunas, en cinco (1, 4, 9, 8 y 7) de ellas se contabilizan mas de la mitad de siniestros: 364
* En el 2016, fue en la Comuna 1 donde ocurrieron la mayor cantidad de siniestros: 22
* En 2017 y 2018 tambien en Comuna 1 se registraron mas siniestros: 20 en cada año  
<br/>

**Sobre los Tipos de Vias de Transito en que Ocurrieron Siniestros**
* En las comunas 8, 9, 11 y 12, la Gral Paz es la via con mas siniestros
* De todas las vias de la ciudad, en la Gral Paz ocurrieron la mayor cantidad de siniestros: 52 ocurrencias 
* La mayor cantidad de siniestros se produjeron en avenidas: 61%  
<br/>

**Sobre los Siniestros Organizados por Meses del Año**
* Noviembre y Diciembre registran mas siniestros que el resto de meses, pero las diferencias no son amplias
* Observacion: El mes del año no parece ser una variable que brinde algun factor a tomar en cuenta pues no se verifican tendencias claras.  
<br/>

**Sobre los Dias del Mes que Registraron Siniestros**
* En los meses de Febrero y Agosto ocurrieron mas siniestros el dia 17
* En los meses de Octubre y Noviembre ocurrieron mas siniestros el dia 25
* En los meses de Octubre y Setiembre ocurrieron mas siniestros el dia 14
* En los meses de Julio y Diciembre ocurrieron mas siniestros el dia 6
* El dia del mes no parece ser una variable que por si misma brinde algun factor a tomar en cuenta. Incluso visto desde multiples perspectivas con histogramas de frecuencias no se muestra un patron claro  
<br/>

**Sobre los Siniestros Organizados por Dias de la Semana**
* En los meses de Abril, Octubre y Diciembre ocurrieron mas siniestros el dia Domingo
* Observacion: el dia de la semana no parece ser una variable que por si misma brinde algun factor a tomar en cuenta. Segun el grafico de barras hay mucha similitud entre la cantidad de siniestros en todos los dias de la semana  
<br/>

**Sobre el Año en que Ocurrio el Siniesto**
* De los años registrados, en el 2016 ocurrieron la mayor cantidad de siniestros con 145, seguido por el año 2017 con 140 ocurrencias
* Si bien la cantidad de siniestros se ha ido reduciendo en los ultimos años, hubo un rebote en el año 2018 que impide afirmar una tendencia clara de reduccion de siniestros   
* Observacion: el año del siniestro no parece ser una variable que brinde algun factor a tomar en cuenta pues no se verifican tendencias claras.  
<br/>

**Sobre los Siniestros Organizados por Horas del Dia**
* Podriamos afirmar que de 5 a 9 hs ocurrieron mas siniestros, pero los siniestros ocurridos a las 8 hs invalidan la tendencia
* Podriamos afirmar que de 0 a 4 hs ocurrieron menos siniestros, pero los siniestros ocurridos a las 3 hs invalidan la tendencia
* Observacion: la hora del dia no parece ser una variable que por si misma muestre tendencias claras  

<span style="float:right;">[arriba](#tabla-de-contenido)</span> 

<br/>
<br/>

<!-- # <div align="center">Conclusiones y Recomendaciones</div> -->

# Conclusiones y Recomendaciones

### A continuacion se exponen algunas conclusiones a partir de los insights encontrados:

1. El resultado del analisis univariable demostro que se debe dar mayor atencion a las siguientes variables:
    * Nro de Victimas
    * Tipo de Calle
    * Comuna
    * Vehiculo de la Victima
    * Vehiculo del Acusado 

2. Sabiendo que en la gran mayoria de siniestros se registro una sola victima por ocurrencia y sabiendo que el tipo de vehiculo que padecio de mas siniestros fue la moto (44.9%) seguido por los peatones (37.4%) **se recomienda tomar medidas que se enfoquen en la seguridad vial de los motociclistas y peatones**.   
**Ademas se considera prioritario tomar medidas para reducir los siniestros producidos por automoviles y vehiculos de pasajeros** dado que causaron el 32.8% y el 24.9% de los siniestros respectivamente.

3. Sabiendo que las comunes mas proclives a los siniestros se concentran en las zonas Centro-Sur y Este de la ciudad **se recomienda priorizar la atencion de esas zonas, en especial a las comunas 1, 4, 9, 8 y 7**, dado que de las 16 comunas, en aquellas ocurrieron mas de la mitad de siniestros. 
De entre esas cinco comunas, **se sugiere dar aun mas relevancia a la Comuna 1** dado que alli se registraron la mayor cantidad de siniestros.

5. Dado que el 61% de los siniestros se produjeron en avenidas **se recomienda dar preferencia especial a este tipo de via a la hora de diseñar las medidas de seguridad vial**
En cuanto a las vias por donde circula el transito de la ciudad **se recomienda prestar atencion a la autopista Gral Paz** dado que alli se registraron la mayor cantidad de siniestros: 52

6. Dado que Noviembre y Diciembre registran mas siniestros que en el resto de los meses (aunque no por mucha diferencia) **se sugiere prestar atencion a esos meses**.
Asimismo, las fechas listadas a continuacion han registrado ciertos picos de siniestros, por lo que **se recomienda revisar si esos dias coincidan con dias feriados, fines de semana largos u otros acontecimientos interesantes de analizar**:
    * 17 Febrero y Agosto
    * 25 de Octubre y Noviembre
    * 14 de Octubre y Setiembre
    * 6 Julio y Diciembre  

<span style="float:right;">[arriba](#tabla-de-contenido)</span> 

