# Proyecto de Algoritmos de Ordenamiento y Medición de Desempeño

Este proyecto implementa diversos algoritmos clásicos de ordenamiento en C++, con el objetivo de comparar sus rendimientos en términos de tiempo de ejecución. Los resultados se guardan en archivos CSV para facilitar su análisis.

## Algoritmos Implementados
Los algoritmos de ordenamiento incluidos son:
- **Inserción** (`metodoInsercion`)
- **Burbuja** (`metodoBurbuja`)
- **Selección** (`metodoSeleccion`)
- **Shell Sort** (`metodoShell`)
- **Merge Sort** (`metodoMergeWrapper`)
- **Quick Sort** (`metodoRapidoWrapper`)
- **Heap Sort** (`metodoMonticulo`)

## Descripción del Programa
El programa genera arreglos de números enteros aleatorios y mide el tiempo de ejecución de cada algoritmo utilizando la librería `<chrono>`. Los resultados se almacenan en archivos CSV, con un archivo específico para cada algoritmo, permitiendo comparar su desempeño.

### Flujo del Programa:
1. **Generación de Datos**:
   - Arreglos de 100 números aleatorios entre 1 y 1000.
   - Se ejecutan 1000 pruebas por cada algoritmo.

2. **Medición de Tiempos**:
   - Cada algoritmo ordena un arreglo y su tiempo de ejecución se mide en nanosegundos.
   - Los datos generados se almacenan en archivos CSV.

3. **Resultados en CSV**:
   - Los nombres de los archivos son:
     - `insercion.csv`
     - `burbuja.csv`
     - `seleccion.csv`
     - `shell.csv`
     - `merge.csv`
     - `rapido.csv`
     - `monticulo.csv`

## Cómo Compilar y Ejecutar
### Compilación:
Ejecuta el siguiente comando en la terminal para compilar el programa:
```bash
g++ -o ordenamiento main.cpp -std=c++17
