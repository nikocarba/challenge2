# Challenge

Este repositorio resuelve un challenge relacionado con el análisis de datos de un dataset de eventos de telecomunicaciones.

## Requisitos

- Docker
- Docker Compose

## Descripción del Proyecto

La Jupyter Notebook en este proyecto realiza las siguientes tareas:

1. **Cálculo del Monto Total de Facturación**: 
   La notebook calcula el monto total de facturación utilizando el conjunto de datos proporcionado.
   
2. **Generación de un Nuevo Dataset**:
   Se crea un nuevo conjunto de datos con los 100 IDs que tienen el mayor monto de facturación.
   
3. **Generación de un Histograma**:
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
docker-compose up
```


### Paso 4: Acceder a Jupyter Notebook
Una vez que el contenedor esté corriendo, abre tu navegador y dirígete a:

Para iniciar el entorno, ejecuta el siguiente comando:
```bash
http://localhost:8888/?token=myjupytertoken
```

### Paso 5: Ejecutar el Notebook
Dentro de Jupyter, abre el archivo notebook.ipynb. Para ejecutar las celdas, simplemente haz clic en "Run" o usa el atajo Shift + Enter para avanzar de celda en celda.
