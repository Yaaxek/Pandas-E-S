# Proyecto: Manipulación de Datos con Pandas

Este proyecto resume los conocimientos adquiridos en el curso sobre cómo trabajar con diversos formatos de archivo utilizando la biblioteca Pandas en Python.

## Temas Cubiertos:

### 1. Archivos CSV
- **Lectura**: Aprendimos a cargar archivos CSV utilizando `pd.read_csv()`, con la capacidad de especificar el separador de columnas (`sep`) cuando este difiere de la coma por defecto.
- **Escritura**: Se demostró cómo exportar DataFrames o selecciones de datos a archivos CSV mediante `df.to_csv()`.

### 2. Archivos Excel
- **Lectura**: Se cubrió la lectura de archivos Excel (`.xlsx`, `.xls`, etc.) desde fuentes locales y Google Sheets, utilizando `pd.read_excel()`. También se aprendió a seleccionar hojas específicas mediante el parámetro `sheet_name`.
- **Escritura**: Se mostró cómo guardar DataFrames en formato Excel usando `df.to_excel()`.

### 3. Archivos JSON
- **Lectura**: Aprendimos a importar datos de archivos JSON con `pd.read_json()`.
- **Normalización**: Se exploró la normalización de estructuras JSON anidadas utilizando `pd.json_normalize()` para aplanar datos complejos en un formato tabular.
- **Escritura**: Se explicó cómo exportar DataFrames a archivos JSON utilizando `df.to_json()`.

### 4. Archivos HTML
- **Lectura**: Se aprendió a extraer tablas de páginas HTML con `pd.read_html()` y cómo seleccionar la tabla deseada de la lista resultante.
- **Escritura**: Se mostró cómo guardar un DataFrame como una tabla HTML utilizando `df.to_html()`.

### 5. Archivos XML
- **Lectura**: Se cubrió la lectura de archivos XML con `pd.read_xml()` y la comprensión de su estructura para la extracción de información relevante.
- **Escritura**: Se demostró cómo exportar DataFrames a archivos XML utilizando `df.to_xml()`.

### 6. Bases de Datos SQL
- **Conexión**: Se configuró una base de datos local SQLite en Google Colab utilizando SQLAlchemy y `create_engine()`.
- **Carga de Datos**: Aprendimos a importar datos desde un DataFrame de Pandas a una tabla SQL usando `df.to_sql()`.
- **Consultas SQL**: Se realizaron operaciones básicas de base de datos como seleccionar (`SELECT`), borrar (`DELETE`) y actualizar (`UPDATE`) datos utilizando `pd.read_sql()` y `engine.connect().execute(text(query))`.
