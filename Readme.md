# Ensayo DataCube

Alumno:

* Jean Carlo Cornejo Cornejo

## Tabla de Contenidos

* [Introducción](#introducción)
* [DataCube](#DataCube)
* [Comparación](#comparación)

## Introducción

Es necesario denotar los objetos que se tomaran en cuenta para realizar nuestro datacube.

<img title="" src="https://raw.githubusercontent.com/Jeannix/EnsayoDataCube/main/Resources/data.png" alt="link" data-align="center">

De esta imagen podremos obtener dimensiones como lspatial1, lspatial2 y el device.

Cada uno de estos comprendiendo los siguientes posibles datos:

* lspatial1 = ((0,0);(0,1);(1,0);(1,1)).

* lspatial2 = ((00,00);(00,01);(00,10);(00,11);(01,00);(01,01);(01,10);(01,11);
                     (10,00);(10,01);(10,10);(10,11);(11,00);(11,01);(11,10);(11,11)).

* Device = (Android, Iphone).

Todo esto se puede comprender como datos de latitud y longitud y los puntos de color implicarían las dos opciones de Android o Iphone.

Tambien podemos extraer los siguientes objetos tomando en cuenta nuestros datos presentados en la imagen.

<img src="https://github.com/Jeannix/EnsayoDataCube/blob/main/Resources/dataset.png?raw=true" title="" alt="link" data-align="center">

A continuación tomariamos en cuenta una "permutación" de todos nuestros posibles datos, para así generar nuestro DataCube.

## DataCube

Como fue mencionado en [Introducción](#introducción) se realizara una "permutación" de estos datos y a su vez se añadirá un nuevo dato por cada grupo de opciones, conteniendo ambos devices. Como resultado obtendremos la siguiente tabla:

<img src="https://raw.githubusercontent.com/Jeannix/EnsayoDataCube/main/Resources/0%2C0.png" title="" alt="link" data-align="center"><img src="https://raw.githubusercontent.com/Jeannix/EnsayoDataCube/main/Resources/0%2C1.png" title="" alt="link" data-align="center"><img src="https://raw.githubusercontent.com/Jeannix/EnsayoDataCube/main/Resources/1%2C0.png" title="" alt="link" data-align="center"><img src="https://raw.githubusercontent.com/Jeannix/EnsayoDataCube/main/Resources/1%2C1.png" title="" alt="link" data-align="center"><img src="https://raw.githubusercontent.com/Jeannix/EnsayoDataCube/main/Resources/lspatial2.png" title="" alt="link" data-align="center">

## Comparación
