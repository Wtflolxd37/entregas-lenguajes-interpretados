- **Negrita**- Se coloca con dos *

- _cursiva_- Se coloca con un guion abajo _

- **_Negrita con cursiva_**- Se coloca con dos astericos y guion hacia abajo combinados

Los encabezados se colocan con un # y espacio, con una cierta cantidad se va disminuyendo el encabezado el maximo que puedes crear son 7#

# Encabezado 1

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

###### Encabezado 7

El enlace se coloca con un [Google]-(https://www.google.com/?zx=1756491563129&no_sw_cr=1) esto haciendo que la palabra en corchetes se vuelva azul y copie el link asi: [google](https://www.google.com/?zx=1756491563129&no_sw_cr=1)

Para la imagen es casi lo mismo pero tienes que agregar el signo de exclamacion(!): ![a](https://imagenes.20minutos.es/uploads/imagenes/2024/05/15/una-imagen-creada-por-la-herramienta-imagen-3-de-google-1.jpeg)

Las divisiones se hacen con --- en un espacio en blanco
---
y la tabla se hace de la misma manera pero con el signo | en la parte de abajo

| Mexico | China | Uruguay |
|-|-|-| 
| Brasil | Japon | Colombia |

El en listado se pone con el 1. y si sigues poniendo 1. te va salir el 2 eso en caso de que no haya ningun 1.
1. a
1. b
1. c

Las viñetas se ponen con el - y espacio
- 1
- 2
- 3

Para poner el formato de una lengua de programacion solo se pone ``` con el lenguaje de tu programacion
```js
function sumar(a, b) {
  if (typeof a !== "number" || typeof b !== "number") {
    console.error(`Los valores ingresados NO son números.`);
    return false;
  }
  ```

## Comandos Básicos de Terminal
- pwd = print working directory
- ls = Lista los directorios y archivos de directorio donde esta la Terminal
- ls -l = Lista detalles de los directorios y archivos
- ls -a = Lista de todo tipo de directorio y archivos(Incluye ocultos)
- ls - la = La combinacion de ambas flags
- clear = Limpia la pantalla de la Terminal
- cd nombre = cambiar de directorio
- cd ../ = sube al directorio padre
- cd ../../ = Subimos dos directorios padres
- cd ~ = Regresamos al directorio del usuario (/User/jonmira)
- mkdir = crea un directorio
- touch archivo.txt = crea un archivo del tipo que le indiquemos
- rm = eliminar archivos
- rm -r =eliminar directorios
- cp ruta-actual ruta-nueva = copia archivos
- mv ruta-actual ruta-nueva = mueve archivos

ctrl + j = abre la Terminal en el editor
alt + shif + flecha arriba o felcha abajo = Copia el texto de arriba o abajo
alt + shit + = Pone un comentario