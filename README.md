#  Reloj Digital en C

Este proyecto es un simple **reloj digital** desarrollado en el lenguaje de programación **C**. Muestra la hora actual en formato `HH:MM:SS` y se actualiza cada segundo en la consola.

---

##  Descripción

El programa obtiene la hora del sistema usando la librería estándar de tiempo de C (`<time.h>`) y la actualiza continuamente mediante un bucle que se ejecuta cada segundo.

---

##  Tecnologías utilizadas

- Lenguaje C
- Librerías estándar:
  - `<stdio.h>`: para impresión por pantalla
  - `<time.h>`: para manejo de tiempo y fechas
  - `<stdbool.h>`: para usar tipo booleano
  - `<unistd.h>`: para la función `sleep()`

---

## Cómo compilar y ejecutar

1. Guarda el código en un archivo, por ejemplo: `reloj.c`
2. Abre una terminal y compila el archivo con `gcc`:

   ```bash
   gcc reloj.c -o reloj
