
# ETL_Project-PIB-Internacional

## 🧾 Descripción  
Este proyecto implementa un pipeline ETL sencillo pero funcional para procesar datos del PIB internacional, transformarlos y almacenarlos en una base de datos. Es ideal como prueba de concepto de flujo de datos, transformación y carga — útil para tareas de análisis económico, inteligencia de datos o proyectos educativos.

## 📁 Estructura del proyecto
```bash
├── Countries_by_GDP.csv # Datos originales: PIB por país
├── etl_project_gdp.py # Script principal del proceso ETL
├── World_Economies.db # Base de datos resultante con los datos transformados
├── etl_project_log.txt # Registro de logs del proceso ETL
```

## 🚀 Instalación y ejecución  

### 🛠 Prerrequisitos  
- Python 3.x  
- Librerías necesarias: pandas, sqlite3 (u otras si decides usar otro motor de BD)  

### 🔧 Pasos  
```bash
# Clonar el repositorio  
git clone https://github.com/FernandoBlanco10/ETL_Project-PIB-Internacional.git  
cd ETL_Project-PIB-Internacional  

# Instalar dependencias  
pip install pandas  

# Ejecutar el script ETL  
python etl_project_gdp.py  
Al ejecutar el script, se leerá el archivo Countries_by_GDP.csv, se transformarán los datos según la lógica definida y se guardarán en World_Economies.db. Un log del proceso quedará en etl_project_log.txt.
```

### ✅ ¿Qué hace este proyecto?
- Lee datos brutos del PIB por país desde un CSV.
- Limpia, transforma y normaliza los datos (tipos, nombres, valores faltantes, etc.).
- Inserta los datos procesados en una base de datos SQLite.
- Genera un log con detalles del proceso para seguimiento y debugging.

### 🎯 Casos de uso
- Base para análisis de datos económicos globales.
- Demostración de un pipeline ETL para proyectos de Data Engineering.
- Proyecto educativo para aprender transformación y carga de datos.

### 📝 Próximos pasos / posibles mejoras
- Agregar manejo de excepciones más robusto en el ETL.
- Añadir tests automatizados para asegurar calidad del pipeline.
- Permitir parametrización (por ejemplo: distintos orígenes de datos, distintos destinos de BD, formatos).
- Documentar datos de salida con esquema claro de la base de datos.
- Extender el pipeline para incluir más indicadores económicos.

### 👤 Autor & Contacto
Autor: Fernando Blanco (GitHub: @FernandoBlanco10)
