# PROYECTO DE INVESTIGACION
**ROLANDO MOISES PERCA GONZALES**
# PLANTEAMIENTO DE LA INVESTIGACION
## PROBLEMA

Se plantea desarrollar modelos estocasticos para generar predicciones de series temporales de radiacion solar y de velocidad de viento (de un anio) para el estudio del ptencial renovable de estas dos energias en la ciudad de Arequipa.</br>
Estos modelos se fundamentan en el analisis estadisticos dinamicos, basados en modleos estocasticos, los cuales son utilizados para simular y predecir series de datos de radiacion solar y velocidades de viento mientras retienen las caracteristicas medias d elos datos observados (radiacion solar  velocidad de viento promedio, varianza, coeficiente de autocorrelacion, densidad de probabilidad, etc) los cuales son usados para construir los modelos.</br>

## TITULO

## *PREDICCIONES DEL POTENCIAL RENOVABLE EN ENERGIA SOLAR Y EOLICA EN AREQUIPA*

## HIPOTESIS

Realizar un estudio del pontencial de energias renovables en Arquipa, especialmente solar y eolico, fundamentando su importancia como fuentes economicas de uso limpio y como una medida alternativa de utilizacion en nuestro medio.</br>

Bajo esta motivacion se realiza un estudio de prediccion de estos potenciales a partir de 10 anios de datos de promedios horarios de radiacion solar y de velocidades de viento, los cuales seeran utilizados para construir modelos teoricos, empleara modelos autoregresivos (AR(2)) y autoregresivos de medias moviles (ARIMA) para simular datos de radiacion solar directa y la velocidad de viento en periodos como minimo de un anio. Posteriormente se realizara comparaciones entre series de datos generados temporalmente y datos reales, para comprobar el comportamiento de prediccion de la radiacion solar y del viento en Arequipa.</br>

## I. PLANTEAMIENTO

## 1. FORMULACION Y DELIMITACION DEL PROBLEMA

La modelacoin consiste en justar los datos de radiacion solar y velocidad de viento (promedios horarios), los cuales han sido al principio transformados para hacer que sus distribuciones sean aproximadamente Gausianas y normalizadas para asegurar la estacionalidad (una de las fases de aplicacion de la metodologia Box-Jenkins) al proceso ARMA (p,q) y otros como AR(q) de varios ordenes:

- Identificacion de la estructura del modelo: Decidir que transformacion aplicar a las series para convertir los procesos subyacentes en estacionarios y determinar las estructuras de los procesos estacionarios resultantes.
- Estimacion de los parametros del medio para los procesos estacionarios.
- Diagnosis de los modelos: comprobar si se satisface la hipotesis de que los residuos obtenidos al ajustar los modelos son realizaciones de procesos de ruido blanco.</br>

El problema utilizara:

- Metodo Box-Jenkis para ajustar las series temporales al modelo ARIMA o AR.
- Determinacion de las series temporales mediante los modelos ARIMA(p,q) o AR(p).

## 2. PLANTEAMIENTO DE OBJETIVOS

### **Objetivos Generales**

- A partir de un analisis estadistico dinamico basado en un modelo estocasitico simular y predecir distribuciones de radiaciones solar y velocidades de viento para tiempos posteriores a los analizados.

### **Objetivos Especificos**

- Realizar un estudio motivador sobre el uso racional de la energias poniendo enfasis en las energias renovables (solar y eolica).
- Recopilar bibliografia referente a modelos de prediccion temporal de tratamiento de series temporales de radiacion solar y de velocidad de viento.
- Analizar y comprender el uso de analisis de series temporales y de radiacion solar y de velocidad de veinto en el estudio predictivo de estas distribuiciones.

## 3. CONTENIDO TEMATICO

### Indice
### Introduccion
### Resumen

### Capitulo 1

Estudios preliminares</br>
1.1 Introduccion</br>
1.2 Antecedentes del problema</br>
1.3 Importancia del uso de energias renovables (solar y eolica)</br>
1.4 Caracteristicas de la radiacion solar en la ciudad de Arequipa</br>
1.5 Modelo fisico de la distribucion de radiacion solar (Ley de Beer)</br>
1.6 Caracteristicas de viento en la ciudad de Arequipa y topografia local</br>
1.7 Modelo fisico estadistico de la distribucion de velocidad de viento (Distribucion de Weibull)

### Capitulo 2

Descripcion del Modelo Temporal Implementado</br>
2.1 Introduccion</br>
2.2 Procesos estacionarios</br>
2.3.1 Funcion de autocorrelacion</br>
2.3.2 Autocorrelacion simple de orden k</br>
2.3.3 Autocorrelacion parcial d eorden k</br>
2.3.4 Proceos de ruido blanco</br>
2.3.5 Proceso autorregresivo AR(p)</br>
2.3.6 Proceso autorregresivo de medias moviles (ARMA(p,q))</br>
2.3.7 Procesos autorregresivos integrados d emedias moviles (ARIMA(p,d,q))</br>
2.3 Analisis de una serie temporal medainte la metodologia Box-Jenkins</br>
2.4 Ajuste de los modelos AR(p) y ARIMA(p,q)

### Capitulo 3

3.1 Introducion</br>
3.2 Construccion de una variable estacionaria para obtener una distribucion gaussiana de radiacion solar.</br>
3.3 Aplicacion de la metodologia Box-Jenkins a la distribucion gausiana de radiacion solar.</br>
3.4 Aplicacion del modelo para generar un anio referencial de radiacion solar en Arquipa.

### Capitulo 4

4.1 Introduccion</br>
4.2 Construccion de una variable estacinaria para obtener una distribucion gausiana de velocidades de viento.</br>
4.3 Aplicacion de la tecnologia Box-Jenkins a la distribucion gausiana de velocidades de viento.</br>
4.4 Aplicacion de modelo para generar un anio referencial de velocidades de viento en Arequipa.

### Conclusiones y Sugerencias

### Referencias Bibliograficas

## 4. FUNDAMENTACION DE LA IMPORTANCIA DEL ESTUDIO

La demanda de energia electrica en nuestro medio es satisfecha mayormente utilizando fuentes limitadas de produccion y de residuos contaminantes, en el prensente se intenta utilizar otras fuentes alternativas como sol la solar, eolica, biomasa, etc. En particular el uso delas energias solar y eolica mediante el empleo de dispositivos que utilicen como fuentes estos dos recursos, como pueden ser: calentadores, concentradores, refrigeradores, extractores eolicos, aerogeneradores de baja potencia para el cconsumo humano, etc, para esto se precisa como primer paso determinar el potencial renovable tanto solar como eolica del cual se dispone, siendo este obtenido solo si se conce el comportamiento temporal de las distribuciones tanto solar como eolica.</br>
En el presente trabajo se propone justamente determinar y predecir tales distribuciones a partir de la diponibilidad y estuido de series temporales y promedios hoarios de radiacion y velocidades de viento.

## 5. PRECISION DE LA METODOLOGIA DE INVESTIGACION

Este estudio inductivo (de las partes al todo), en su primera fase donde intenta a partir de datos de radiacino soalr y de velocidad de viento de 10 anios armar un modelo que determine las propiedades generales de tales datos y deductivos en su segunda parte (del todo a las partes) cuando a partir de las distribuciones predecidas se intente determinar datos d elas dos variables temporalmente. Este sera realizado mediante la siguiente metodologia:</br>

- Revision bibliografica.</br>
- Recoleccion y seleccion de datos.</br>
- Tratamiento de datos para obtencion de distribuciones temporales de radiaciones solar y velocidad de viento.</br>
- Redaccion del informe final.</br>
- Revision y elaboracion del informe final.</br>

## 6. DEFINICIO DEL CRONOGRAMA A EJECUTAR LA INVETIGACION

La investigacion se realizara en el transcurso de 18 meses a partir de la fecha</br>
Revision bibliografica  6 meses</br>
Recoleccion y seleccion de datos 4 meses</br>
Tratamiento de datos 7 meses</br>
Redaccion del informe</br>
Revision y elaboracion del informe final</br>

## 7. DETERMINAR EL CAMPO O CONTEXTO EN EL QUE SE VA EJECUTAR

Este estudio se realizara en los campos de:</br>

- Estudio de recuross energeticos renovables</br>
- Analisis estocastico</br>
- Programacion y simulacion</br>

## 8. DEFINICION DE LOS RECURSOS

### HUMANOS

- Responsables del proyecto</br>
- Asesor</br>

### MATERIALES

- Bibliografia</br>
- Computadora</br>
- Programa para analisis numerico</br>
- Programa SPSS</br>
- Hoja de Calculo Origen/Excel</br>
- Impresora</br>
- Datos de radiacion solar y velocidad de viento (10 anios)</br>
- Papel</br>
- Toner de tinta para impresora</br>

## 9. PRESUPUESTO

Bibliografia 300</br>
Internet 100</br>
Papel 40</br>
Toner 270</br>
**Total 710**</br>

## II ORGANIZACION DE LA INVESTIGACION

## 1. ADMINISTRACION DE LA INVESTIGACION

## 2. DEFINICION DEL EQUIPO Y DELIMITACION DE FUNCIONES Y RESPONSABILIDADES

Asesor (proporcioin de trabajo y exigencias a complir)</br>
Responsable (Cumplimiento con las proposiciones y exposiciones de avance)</br>
Ambiente de reuniones (Lugar para reuniones periodicas y exposiciones de vances)</br>
Ambiente de trabajo (Lugar equipado de implementos de investigacion)</br>

### 3. AMBIENTACION FISICA NECESARIA

*Ambiente de reuniones:* Oficina del asesor: Departamento de Ingenieria</br>
*Ambiente de trabajo:* Local propio; Departamento Academico de Fisica

### 4. PERSONAL DE APOYO

Profesores especializados del DAF en el tema de tesis.

### 5. BIBLIOGRAFIA

1. M. Ferran Arnaz, "SPSS para Windows, programacion y analisis estadistico", Ed. McGraw-Hill, 1997</br>
2. D. R. Inglis, "Wind Power and other Energy Options", University Michigan Press, 1978