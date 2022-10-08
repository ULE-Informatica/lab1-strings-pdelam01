# MUIC - DPS - Laboratorio 1

## ejemplo1.c

Follow the instructions explained in the beginning of file ejemplo1.c for compiling with gcc and g++ (you can try also clang). 

## ejemplo2.c. Program Instrumentation

Find the memory errors presented in file ejemplo2 using gcc instrumentation option **AddressSanitizer (ASan)**.
Explain in this file each error.

---
## Ejercicio 1
La primera parte de la practica se estructura de la siguiente forma:
- **ejemplo1.c**: ejercicio base, donde se muestran en las líneas correspondientes las reglas y/o recomendaciones que han sido rotas
- **ejemplo1_std99.c**: en este archivo se indican qué errores y advertencias se han obtenido corriendo los comandos:
```sh
gcc ejemplo1.c -o ej1_std99 -Wall -pedantic -std=c99 (el programa compila sin warnings ni errores para esta versión)
g++ ejemplo1.c -o ej1_stdpp99 -Wall -pedantic -std=c++98
```
- **ejemplo1_std11.c**: de igual manera que en el caso anterior, se muestran los errores y advertencias se han obtenido corriendo los comandos:
```sh
gcc ejemplo1.c -o ej1_std11 -Wall -pedantic -std=c11
g++ ejemplo1.c -o ej1_stdpp11 -Wall -pedantic -std=c++11 
```
---
## Ejercicio 2
Errores detectados en ejemplo2.c:
