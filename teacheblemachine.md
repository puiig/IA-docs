
# Proyecto: Clasificación de residuos

## Introducción al problema

Vamos a crear un modelo para clasificación de residuos en 5 contenedores: verde, azul, amarillo, orgánico y de residuos.


## Paso 1

Elección de clases y datos de entrenamiento.

Vamos a añadir cinco clases, una para cada tipo de residuos que hemos elegido:

* Contenedor amarillo
* Contenedor azul
* Contenedor verde
* Contenedor orgánico
* Contenedor gris

## Paso 2

Entrenamiento del modelo añadiendo diferentes imágenes.

* __Resultado de entrenamiento con imágenes propias:__

![](https://github.com/puiig/IA-docs/blob/main/Primer%20intento.png)

![](https://github.com/puiig/IA-docs/blob/main/Segundo%20intento%20IA.png)

![](https://github.com/puiig/IA-docs/blob/main/Cuarto%20intento.png)

## Paso 3 

__Evaluación del modelo con imágenes propias:__

El modelo falla al dar los resultados por confusión de colores generalmente.


## Paso 4

Evaluación del modelo con las imágenes ofrecidas por la carpeta test 2 de Aules.

## TEST 1

![](https://github.com/puiig/IA-docs/blob/main/Prueba%201.png)



## TEST 2

![](https://github.com/puiig/IA-docs/blob/main/Prueba%202.png)


## TEST 3

![](https://github.com/puiig/IA-docs/blob/main/Prueba%203.png)


## TEST 4

![](https://github.com/puiig/IA-docs/blob/main/Prueba%204.png)

__Evaluación del modelo con imágenes de Aules:__

Los resultados han sido positivos.


## Tabla de excel: Resultado de la IA con las imágenes de test 1 de Aules.



|   |                              ELEMENTO                              | CONTENEDOR SUGERIDO | PORCENTAJE | CONTENEDOR ADECUADO |
| - | ------------------------------------------------------------------ | ------------------- | ---------- | ------------------- |
| 1 |                            periodico.jpg                           |         Azul        |    100%    |         Azul        |
| 2 |                            restos2.jpeg                            |       Orgánico      |     85%    |       Orgánico      |
| 3 |           Apo 33 Reflejo-256x256.jpg (botella de vidrio)           |        Verde        |     85%    |        Verde        |
| 4 |                              pañal.jpg                             |        Gris         |     90%    |         Gris        |
| 5 |                         tarro_conserva.jpg                         |        Gris         |     47%    |        Verde        |

__Evaluación del modelo con imágenes de Aules:__ 

Los resultados han sido generalmente positivos, excepto por la última prueba, con el tarro de conserva, que lo ha clasificado incorrectamente por su forma.
