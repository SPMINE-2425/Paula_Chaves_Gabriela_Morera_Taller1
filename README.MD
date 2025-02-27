# Proyecto de Ciencia de Datos - Seminario de Programación

![Python](https://img.shields.io/badge/Python-3.10-blue)  
![pandas](https://img.shields.io/badge/pandas-2.2.3-orange)  
![tqdm](https://img.shields.io/badge/tqdm-4.67.0-lightgrey)  

**Autores:** Paula Chaves y Gabriela Morera  
**Materia:** Seminario de Programación  
**Universidad:** Externado de Colombia  
**Departamento:** Cundinamarca  

## Descripción
Este proyecto tiene como objetivo la descarga, exploración y análisis de datos para el Departamento de Cundinamarca. A través del uso de Python y herramientas de ciencia de datos, buscamos obtener insights valiosos a partir de los datos extraídos mediante una API.

## Estructura del Proyecto

El proyecto está organizado en las siguientes carpetas:

- **código/**: Contiene los cuadernos Jupyter con el desarrollo del proyecto.
  - `descarga_datos.ipynb`: Cuaderno encargado de obtener los datos desde la API y almacenarlos en la carpeta de datos.
  - `exploracion_datos.ipynb`: Cuaderno para la exploración inicial y análisis de los datos.
- **datos/**: Carpeta donde se almacenan los datos descargados desde la API.
- **documentacion/**: Contiene el informe y los comentarios sobre los resultados obtenidos en la exploración de los datos.

## Tecnologías Utilizadas
- Python
- Pandas
- Seaborn
- Matplotlib
- tqdm
- Conda para la gestión de ambientes
- Poetry para la gestión de dependencias

## Instalación y Configuración

### 1. Clonar el repositorio
```bash
 git clone <https://github.com/SPMINE-2425/Paula_Chaves_Gabriela_Morera_Taller1>
 cd <NOMBRE_DEL_PROYECTO>
```

### 2. Crear y activar el ambiente con Conda
```bash
 conda create --name mi_ambiente python=3.11
 conda activate mi_ambiente
```

### 3. Instalar dependencias con Poetry
```bash
 pip install poetry
 poetry install
```

## Uso del Proyecto

Para ejecutar el cuaderno de descarga de datos:
```bash
 jupyter notebook codigo/descarga_datos.ipynb
```

Para ejecutar el cuaderno de exploración de datos:
```bash
 jupyter notebook codigo/exploracion_datos.ipynb
```

## Contacto
https://github.com/SPMINE-2425/Paula_Chaves_Gabriela_Morera_Taller1