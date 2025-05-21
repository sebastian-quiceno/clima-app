# clima-app
Docker que tiene una pequeña aplicacion web que muestra el clima de las ciudades del mundo

# Clima App - Servicio Web con Flask y Docker

Este proyecto es un servicio web construido con Python y Flask que permite consultar el clima de cualquier ciudad utilizando la API de OpenWeatherMap. El proyecto está desplegado dentro de un contenedor Docker, listo para producción local.

## 🚀 Requisitos

- Docker
- Cuenta gratuita en https://openweathermap.org para obtener una API Key

## 🔧 Instalación y ejecución

1. Clone el repositorio (si ya esta en la carpeta, omita este paso).
2. Asegurese de que el archivo `main.py` contiene la API Key dada por OpenWeatherMap.
3. Construya la imagen Docker:

## 🔥 Ejecucion
1. En la terminal digite: sudo docker run -p 5000:5000 clima-app
2. Posteriormete el docker le va a mostrar la direccion para ver el servicio, copiela y peguela en su navegador

# clima-app-Script
Para correr el programa automaticamente, vaya a la consola, ingrese en la ruta .../clima_app_Script/clima_app y digite el siguiente comando sudo ./run.sh
