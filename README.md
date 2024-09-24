[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/1bd51xRF)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16122650&assignment_repo_type=AssignmentRepo)
# Suma de Matrices

Este repositorio contiene un programa en C que permite sumar dos matrices. 
Los estudiantes deben proporcionar el código para terminar de leer la segunda matriz
Relizar la suma
y mostrará la matriz de suma.

## Archivos

- `main.c`: Código fuente del programa principal que suma matrices.
- `test_main.c`: Código fuente para las pruebas automatizadas del programa utilizando la biblioteca Check.
- `Makefile`: Archivo para facilitar la compilación del programa y las pruebas.

## Compilación

Para compilar el programa y las pruebas, asegúrate de tener instalado `gcc` y la biblioteca Check. Luego, abre una terminal en el directorio del proyecto y ejecuta:


Para instalar chec en MSYS2 utiliza el sigiuente comando 

```MSYS2
pacman -S mingw-w64-x86_64-check
```


Para generar el ejecutable ejecuta el siguiente comando

```bash
make
```

Esto generará dos ejecutables: main_program y test_program.

## Ejecución

Para ejecutar el programa principal:

```bash
./main_program
```

Esto te pedirá que ingreses las dimensiones de las matrices y los elementos que deseas sumar.

## Para ejecutar las pruebas:

```bash
./test_program
```

Las pruebas verifican que la suma de matrices se realice correctamente.

