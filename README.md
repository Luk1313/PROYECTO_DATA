# Proyecto de Análisis de Ventas

Este proyecto contiene un flujo automatizado para filtrar, procesar y analizar datos de ventas desde una base de datos inicial hasta generar un informe final con todos los análisis requeridos.

---

## Archivos Principales

1. **Base_control_2.xlsx**:
   - Es la base de datos inicial que contiene todas las ventas registradas.
   - Este archivo es importado por el script `filtro_inicial`.

2. **filtro_inicial.ipynb**:
   - Es el archivo principal que ejecuta todo el flujo de trabajo.
   - Funcionalidades:
     1. Importa los datos de `Base_control_2.xlsx`.
     2. Filtra las ventas realizadas entre el **1 de enero de 2023** y el **31 de diciembre de 2024**.
     3. Crea un archivo llamado `Ventas_filtradas.xlsx` con las ventas filtradas.
     4. Utiliza la base `Ventas_filtradas.xlsx` para realizar análisis y generar una base final con todos los resultados.

3. **Ventas_filtradas.xlsx**:
   - Contiene los datos filtrados de todas las ventas entre el **1 de enero de 2023** y el **31 de diciembre de 2024**.
   - Es generada automáticamente al ejecutar el archivo `filtro_inicial.ipynb`.

4. **Nuevo_Reporte.xlsx**:
   - Es el archivo final generado por `filtro_inicial.ipynb`.
   - Incluye todos los análisis requeridos, como resúmenes, cálculos y tablas específicas.

---

## Flujo de Trabajo

1. **Importación de Datos Iniciales**:
   - Los datos de `Base_control_2.xlsx` son cargados y procesados.

2. **Filtrado de Ventas**:
   - Se filtran las ventas realizadas entre el **1 de enero de 2023** y el **31 de diciembre de 2024**.
   - Los datos filtrados se guardan en `Ventas_filtradas.xlsx`.

3. **Análisis y Reporte Final**:
   - Los datos de `Ventas_filtradas.xlsx` son utilizados para generar el informe final.
   - Este informe incluye todos los análisis requeridos y se guarda en `Nuevo_Reporte.xlsx`.

---

## Cómo Ejecutar

1. Asegúrate de que todos los archivos estén en el mismo directorio:
   - `Base_control_2.xlsx`
   - `filtro_inicial.ipynb`

2. Abre y ejecuta el archivo `filtro_inicial.ipynb` en un entorno Jupyter Notebook o similar.

3. Una vez ejecutado:
   - Se generará `Ventas_filtradas.xlsx` con los datos filtrados.
   - Se generará `Nuevo_Reporte.xlsx` con los análisis finales.

---

## Notas

- Verifica que el archivo `Base_control_2.xlsx` tenga el formato y los datos correctos antes de ejecutar el flujo.
- Los períodos de filtrado (1 de enero de 2023 a 31 de diciembre de 2024) están definidos en el código y se pueden ajustar según sea necesario.
- Asegúrate de tener instalados los paquetes necesarios, como `pandas` y `openpyxl`.

