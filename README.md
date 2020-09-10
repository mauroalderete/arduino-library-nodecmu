# nodeCMU

Libreria con constantes y definiciones para las placas nodeCMU

- Lolin3

## Instalación

Utilizando la consola de tu preferencia, dirigete a la ruta de las librerias de arduino de tu instalacion. Por ejemplo:

``` bash
cd P:\Arduino\libraries
```

Una vez dentro del directorio solo basta con clonar el proyecto de la libreria en la versión que gustes.

``` bash
git clone git@gitlab.com:arduinolibraries/nodecmu.git .
```

Esto creara el directorio nodemcu de la libreria junto con los archivos de documentación y los ejemplos.

## Seleccion de versión

Por defecto, luego de instalar desde el repositorio, la versión seleccionada es la ultima vigente en master. Si quiere puede seleccionar otra version en cualquier momento utilizando los comandos git checkout y haciendo referencia a la versión que desee.

``` bash
git checkout tag/<versión>
```

Puede ver un listado de las versiones disponibles por medio del siguiente comando

``` bash
git fetch --tags
```

## Actualización

Para actualizar a la ultima versión solo es necesario ejecutar un simple pull

``` bash
git pull
```

Luego podra seleccionar la ultima versión siguiendo los pasos de Selección de versión

## Uso

El uso es sencillo, basta con incluir la libreria Lolin3.h

``` c++
#include <Lolin3.h>
```

## Links

[Cambios de version](CHANGELOG.md)

[Repositorio](git@gitlab.com:arduinolibraries/nodecmu.git)