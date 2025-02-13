# Clasificacion-de-patrones-parkinsonianos-desde-una-representacion-multimodal
Clasificacion de patrones parkinsonianos desde una representacion multimodal que incluye puntos de referencia de marcha y rostro
![banner](banner.png)


## Objetivo
Desarrollar una estrategia de aprendizaje profundo para clasificar patrones asociados al Parkinson utilizando puntos de referencia *Landmarks* de la marcha y la expresión facial.

## Dataset

El dataset está compuesto por dos clases de pacientes: Control (10 pacientes) y Parkinson (19 pacientes), lo que suma un total de 29 pacientes. Cada paciente en el dataset realiza las siguientes acciones:

- Pronuncia 3 veces las vocales (A, E, I, O, U).
- Marcha 5 veces de lado a lado, la camara captura el video desde un plano sagital.
 
## Descripción del proyecto
El Parkinson es una enfermedad neurodegenerativa que se caracteriza principalmente
por la deficiencia de dopamina que se expresa por múltiples afecciones motoras como
la bradicinesia (lentitud de los movimientos durante la marcha y la expresión facial),
inestabilidad postural y rigidez entre otros. En la rutina clínica, el diagnóstico se basa
principalmente en la observación y en la experticia del especialista, reportándose errores
en el diagnóstico superiores al 25 %. Actualmente, estrategias computacionales han
permitido soportar la caracterización aislada de patrones como la marcha, expresión
facial, el temblor, la voz entre otras. Sin embargo, la consideración de una modalidad
aislada puede sesgar el diagnóstico y perder complementaridad en el an ́alisis de una
enfermedad entendida como multifactorial.

En este trabajo se explorará y desarrollar una aproximación computacional que permita involucrar posturas durante la locomoción y expresiones faciales durante ejercicios de pronunciación para clasificar patrones Parkinsonianos, que conlleven a un soporte diagnóstico de la enfermedad. Para ello, tanto en marcha como en las expresiones faciales, se tomará como referencia una representación simplificada de puntos de de referencia (*landmarks*). Este conjunto de puntos, en cada modalidad, permite identificar las correlaciones entre los movimientos e identificar posibles asociaciones motoras que expresan la enfermedad del Parkinson. La arquitectura desarrollada será validada con un conjunto de videos, registrados en el grupo de investigación BivL2ab. Este conjunto
de datos reporta una población de pacientes control y pacientes con la enfermedad de Parkinson.

## Modelo
Random Forest y Bilinear maping covariance learning.

## Presentacion del Proyecto
[Presentacion](presentacion.pdf)

## Autores del proyecto
Faiber Stiven Angarita Mendoza

## Codirector del proyecto
John Edinson Archilla Valderrama

## Director del proyecto
Fabio Martinez Carrillo
