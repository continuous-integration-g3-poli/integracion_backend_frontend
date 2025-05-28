# Integración Backend y Frontend

Este proyecto tiene como objetivo integrar un frontend y un backend previamente creados y publicados como imágenes en Docker Hub.
Utiliza `docker-compose` para levantar ambos servicios de manera sencilla.

## 🚀 Requisitos

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## 🐳 Clonación de Imágenes

Primero, asegúrate de tener las imágenes necesarias desde Docker Hub:

```bash
docker pull drios8331/fronted:latest
docker pull drios8331/backend:latest
```

## 📁 Clonar este Repositorio

Clona el repositorio que contiene los archivos de integración:

```bash
git clone https://github.com/drios8331/integracion_backend_frontend.git
cd integracion_backend_frontend
```

## ⚙️ Levantar los Servicios

Desde la raíz del proyecto ejecuta el siguiente comando:

```bash
docker-compose up -d --build
```

Este comando descargará y levantará los servicios definidos en el archivo `docker-compose.yml`.

## 🌐 Acceder a la Aplicación

Una vez estén corriendo los servicios, puedes acceder a la aplicación en tu navegador en la siguiente URL:

👉 http://localhost:9000/

## 🧼 Detener los Servicios

Si deseas detener y eliminar los contenedores, puedes usar:

```bash
docker-compose down
```

---

**Autor:** [@drios8331](https://github.com/drios8331)  
**Repositorio:** [integracion_backend_frontend](https://github.com/drios8331/integracion_backend_frontend)
