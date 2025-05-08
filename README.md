# Introduccion a Docker
Este proyecto est  preparado para ejecutarse utilizando [Docker](https://www.docker.com/), una plataforma para desarrollar, enviar y ejecutar aplicaciones dentro de contenedores. Si nunca has usado Docker, este README te guiar  por los conceptos b sicos.
## ¿Que es Docker?
Docker es una herramienta que permite empaquetar una aplicaci¢n y todas sus dependencias en un contenedor, asegurando que se ejecute de la misma manera en cualquier entorno. Es ideal para garantizar consistencia en desarrollo, pruebas y producci¢n.
## Requisitos
- Tener instalado [Docker Desktop](https://www.docker.com/products/docker-desktop)
- Opcional: [Docker Compose](https://docs.docker.com/compose/) si trabajas con m£ltiples contenedores
## Comandos Basicos
### 1. Construir una imagen
```bash
docker build -t nombre-de-la-imagen .
### 2. Ejecutar un contenedor
```bash
docker run -p 8000:8000 nombre-imagen
