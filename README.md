
# Proyecto de Análisis y Procesamiento de Datos SQL con Python

Este proyecto se centra en establecer una conexión a bases de datos SQL utilizando Python, realizar consultas, transformar datos y realizar análisis exploratorio. Además, exporta datos a formato Parquet y genera visualizaciones y resúmenes estadísticos clave.


## Indice


 1. [Requisitos](#requisitos)
 2. [Instalación](#instalación)
 3. [Cómo Usar](#cómo-usar)
    - [Conexión a la Base de Datos](#conexión-a-la-base-de-datos)
    - [Exportación de Tablas a Parquet](#exportación-de-tablas-a-parquet)
    - [Análisis de Datos](#análisis-de-datos)
 4. [Estructura del Proyecto](#estructura-del-proyecto)
 5. [Autor](#autor)

## Requisitos

Antes de ejecutar este proyecto, asegúrate de contar con lo siguiente:

- **Python**: Versión 3.8 o superior.
- **Librerías necesarias**:
  - `pyodbc`
  - `pandas`
  - `dotenv`
  - `matplotlib`
- Acceso a una base de datos SQL.

---

## Instalación

1 Clona este repositorio:
   
    git clone https://github.com/tu_usuario/tu_repositorio.git
    cd tu_repositorio 


## Como usar

Configura las credenciales de la base de datos en un archivo .env:

    DB_SERVER=<tu_servidor>
    DB_NAME=<tu_base_de_datos>
    DB_USER=<tu_usuario>
    DB_PASSWORD=<tu_contraseña> bash

### Conexión a la Base de Datos

Utiliza la función connect_to_database() para establecer conexión con la base de datos. Esta función lee las credenciales desde el archivo .env.
Exportación de Tablas a Parquet

Ejecuta la función process_all_tables() para exportar todas las tablas de la base de datos al formato Parquet. Los archivos exportados se guardan en una carpeta designada.
Análisis de Datos

El script incluye herramientas para análisis de datos, como:

    Estadísticas descriptivas.
    Verificación de valores nulos.
    Conteo de frecuencias para columnas categóricas.

### Visualizaciones

Genera gráficos descriptivos con matplotlib, como:

    Top 5 países con más clientes.
    Tracks más vendidos.
    Meses con mayores ventas.
## Estructura proyecto
📦 tu_repositorio
    
    ┣ 📜 main.py          # Código principal del proyecto.

    ┣ 📜 .env             # Archivo con variables de entorno (se genera automáticamente).
    
    ┣ 📜 requirements.txt # Dependencias necesarias para ejecutar el proyecto.
    
    ┣ 📜 README.md        # Documentación del proyecto.

## Contacto

    Creador: Sebastián Nuñez Mejia
    cel : 3144610417
    Correo: snmsebastian@gmail.com
