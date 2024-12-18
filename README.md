# Challenge

Este repositorio resuelve un challenge relacionado con el análisis de datos de un dataset de eventos de telecomunicaciones.

## Requisitos

- Docker
- Docker Compose

## Descripción del Proyecto
Se proporciona un .yml con el docker compose que levanta una Jupyter Notebook con Spark y las instrucciones para utilizarlo.

La Jupyter Notebook en este proyecto realiza las siguientes tareas:

1. **Analisis exploratorio de datos**: 
   La notebook realizar un EDA de los datasets para entender la data con la que se esta trabajando.
   
1. **Cálculo del Monto Total de Facturación**: 
   La notebook calcula el monto total de facturación utilizando el conjunto de datos proporcionado.
   
3. **Generación de un Nuevo Dataset**:
   Se crea un nuevo conjunto de datos con los 100 IDs que tienen el mayor monto de facturación.
   
4. **Generación de un Histograma**:
   Se genera un histograma que muestra la cantidad de llamadas realizadas por hora.

## Instrucciones de Uso

### Paso 1: Instalar Docker

Instalar [Docker ](https://www.docker.com/) desde la pagina oficial.

### Paso 2: Clonar el Repositorio

Luego, clona este repositorio en tu máquina local:

```bash
git clone https://github.com/nikocarba/challenge2.git
cd challenge2
```

### Paso 3: Inicializar el Entorno con Docker Compose
Este proyecto utiliza Docker Compose para configurar un contenedor que ejecuta Jupyter Notebook.

Para iniciar el entorno, ejecuta el siguiente comando:
```bash
docker-compose up -d
```

### Paso 4: Acceder a Jupyter Notebook
Una vez que el contenedor esté corriendo, abre tu navegador y dirígete a:
```bash
http://localhost:8888/?token=myjupytertoken
```

### Paso 5: Ejecutar el Notebook
Dentro de Jupyter, abre el archivo notebook.ipynb. Para ejecutar las celdas, simplemente haz clic en "Run" o usa el atajo Shift + Enter para avanzar de celda en celda.

### Paso 6: Terminar el enterno
Para terminar el entorno, ejecuta el siguiente comando:
```bash
docker-compose down
```


## RESOLUCIONES

### Punto 1
Monto total de facturacion: 1696022.5
### Punto 2
El parquet se encuentra en la ruta data/output del repositorio
### Punto 3
![image](https://github.com/user-attachments/assets/43599078-d279-4dba-949e-485fc2b9e2dd)

