# Taller de Pipeline CI/CD - Ingeniería de Software II 🤖

Este proyecto implementa un flujo completo de **Integración Continua (CI)** y **Despliegue Continuo (CD)** para una aplicación web básica en Node.js, utilizando GitHub Actions y GitHub Pages.

## 📊 Estado del Proyecto
![CI Pipeline](https://github.com/santicrak2017/mi-proyecto/actions/workflows/ci.yml/badge.svg)
[![Deploy Status](https://img.shields.io/badge/Deployment-Live-green)](https://santicrak2017.github.io/mi-proyecto/)

## 🛠️ Tecnologías Utilizadas
* [cite_start]**Lenguaje:** Node.js (v18+) [cite: 13]
* [cite_start]**Framework:** Express.js [cite: 22]
* [cite_start]**Pruebas:** Jest y Supertest [cite: 23]
* [cite_start]**CI/CD:** GitHub Actions [cite: 1]
* [cite_start]**Hosting:** GitHub Pages [cite: 125]

## 🏗️ Estructura del Pipeline
El archivo ci.yml automatiza las siguientes etapas:
1. [cite_start]**Build:** Instalación de dependencias y verificación del entorno [cite: 107-113].
2. [cite_start]**Test:** Ejecución de pruebas unitarias y de integración, incluyendo el endpoint /version [cite: 114-118, 121].
3. [cite_start]**Deploy:** Generación automática de una página de estado y despliegue a la rama gh-pages [cite: 127-143].

## 🚀 Instalación Local
Para probar este proyecto en tu computadora:

1. Clona el repositorio:
git clone https://github.com/santicrak2017/mi-proyecto.git

2. Instala las dependencias:
[cite_start]npm install [cite: 21]

3. Corre las pruebas:
[cite_start]npm test [cite: 99]

4. Inicia la app:
[cite_start]npm start [cite: 98]

## 🔗 Enlace de Despliegue
Puedes ver el estado del último despliegue aquí:
https://santicrak2017.github.io/mi-proyecto/

---
[cite_start]**Equipo:**  [cite: 1]