# Programación Avanzada -  TP - Rearte J.

## Dataset
Este dataset, obtenido de Kaggle, contiene información detallada sobre sismos ocurridos en todo el mundo. Incluye la ubicación geográfica, magnitud, profundidad y el organismo que detectó cada sismo. Los registros abarcan el período de 1965 a 2016, lo que permite analizar patrones históricos y tendencias sísmicas a lo largo del tiempo.

[Earthquake Database - Kaggle](https://www.kaggle.com/datasets/usgs/earthquake-database)

## Instalación Postgresql en Windows

🪟 Instalación en Windows
1️⃣ Descargar el instalador oficial

👉 https://www.postgresql.org/download/windows/

Ahí vas a encontrar un enlace al instalador de EDB (EnterpriseDB).

2️⃣ Ejecutar el instalador

Abrí el archivo descargado (postgresql-x.x.x-windows.exe).

Elegí los componentes por defecto (PostgreSQL Server, pgAdmin, Stack Builder).

Elegí la carpeta de instalación.

Ingresá una contraseña para el usuario postgres (administrador principal).

Seleccioná el puerto (por defecto es 5432).

Finalizá la instalación.

3️⃣ Verificar instalación

Abrí el SQL Shell (psql) o pgAdmin 4, y conectate:}

Server: localhost
Database: postgres
Username: postgres
Password: <la que definiste>

## Dashboard
Este dashboard, creado en Power BI Desktop, permite visualizar y comparar la cantidad de sismos y su magnitud entre distintas décadas, años y meses, ofreciendo un análisis temporal detallado de la actividad sísmica.

Si deseas abrir el archivo .pbix y que los datos se actualicen, debes cambiar la conexión a tu propio servidor PostgreSQL, incluyendo host, puerto, usuario y contraseña.
Puedes cambiar la conexión en Power BI Desktop desde Transformar datos → Origen → Configuración de fuente de datos.
