# 🏫 Colegio San Marcos - REST API

Una API REST robusta y dockerizada diseñada para la gestión académica y administrativa del Colegio San Marcos. Este proyecto implementa una arquitectura backend moderna orientada a la escalabilidad, el aislamiento de entornos y la automatización de despliegues.

## 🛠️ Tecnologías Utilizadas

* **Backend:** Node.js, Express.js
* **Base de Datos:** PostgreSQL
* **ORM:** Prisma
* **Autenticación:** JWT y API Keys
* **Infraestructura:** Docker y Docker Compose

## ⚙️ Requisitos Previos

El objetivo principal de esta arquitectura es ejecutar la API y la base de datos en contenedores aislados. Para trabajar de forma local, el único requisito es:
* Tener **Docker Desktop** instalado y ejecutándose en la computadora local.

No es necesario instalar Node.js ni PostgreSQL localmente.

## 🚀 Instalación y Despliegue Local

1. Clonar el repositorio y acceder a la carpeta del proyecto:
   ```bash
   git clone [https://github.com/TU-USUARIO/colegio_san_marcos.git](https://github.com/TU-USUARIO/colegio_san_marcos.git)
   cd colegio_san_marcos

   ## ☁️ Entorno de Producción y DevOps

Como parte de los lineamientos de arquitectura, este proyecto no solo se ejecuta en entornos locales, sino que cuenta con un ciclo de vida de desarrollo de software (SDLC) automatizado y monitoreado.

* **🚀 API Desplegada:** [Ver lista de alumnos](https://api-colegio-san-marcos.onrender.com/api/alumnos)
* **⚙️ Pipeline CI/CD:** Configurado para automatizar la integración y el despliegue continuo cada vez que se actualiza la rama principal. 
  * [Ver Evidencia de GitHub Actions](https://github.com/Franrecinos1991/Modulo_8/actions/workflows/main.yml)
* **📈 Monitoreo de Salud:** Vigilancia automatizada (Uptime) de los endpoints principales para garantizar la disponibilidad del servicio. 
  * [Ver Evidencia de Monitoreo](https://api-colegio-san-marcos.onrender.com/api/alumnos)
* **💾 Plan de Backups:** Estrategia de copias de seguridad de la base de datos PostgreSQL para garantizar la persistencia e integridad de la información académica.
   * [Ver estrategia de Backup](https://docs.google.com/document/d/10sgUoTdncIhKPTxfR_5d-49eFoCYVIFm6YNGiSnGzig/edit?usp=sharing) 
  
