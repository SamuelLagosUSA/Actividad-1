# Comparación de Factorial Recursivo y Iterativo

Este proyecto tiene como objetivo comparar el rendimiento y el uso de memoria de dos implementaciones del calculo del factorial de un numero entero positivo:

- Version Recursiva
- Version Iterativa

Se realizaron pruebas en Python y en C, a fin de analizar la diferencia en tiempo de ejecucion y en uso de memoria entre ambos enfoques.

## Archivos del Proyecto

- **factorial_comparacion.py**  
  Programa en Python que calcula el factorial de una lista de valores mediante iteracion y recursion.  
  Mide el tiempo de ejecucion y el uso de memoria, generando ademas graficas comparativas.

- **factorial_comparacion.c**  
  Programa en C que realiza el mismo analisis de rendimiento y uso de memoria, pero sin graficas.  
  Los resultados se muestran en la terminal.

## Requisitos

### C
- Compilador GCC o equivalente
- Sistema compatible con la libreria `<sys/resource.h>` para la medicion de memoria

### Python

- Python 3.6 o superior.
- Librerías:
  - memory_profiler
  - matplotlib

Se recomienda instalar todas con:

```bash
pip install -r requirements.txt
