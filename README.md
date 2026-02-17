# Taller de Pipeline CI/CD - Ingeniería de Software II 🤖

Este proyecto implementa un flujo completo de Integración Continua (CI) y Despliegue Continuo (CD) para una aplicación web básica en Node.js, utilizando GitHub Actions y GitHub Pages.

## 📊 Estado del Proyecto
![CI Pipeline](https://github.com/santicrak2017/mi-proyecto/actions/workflows/ci.yml/badge.svg)
[![Deploy Status](https://img.shields.io/badge/Deployment-Live-green)](https://santicrak2017.github.io/mi-proyecto/)

## 🛠️ Tecnologías Utilizadas
* Lenguaje: Node.js (v18+)
* Framework: Express.js
* Pruebas: Jest y Supertest
* CI/CD: GitHub Actions
* Hosting: GitHub Pages

## 🏗️ Estructura del Pipeline
El archivo ci.yml automatiza las siguientes etapas:
1. Build: Instalación de dependencias y verificación del entorno.
2. Test: Ejecución de pruebas unitarias y de integración, validando el endpoint /version.
3. Deploy: Generación de página de estado y despliegue automático a la rama gh-pages.

## 🚀 Instalación Local
Para probar este proyecto en tu computadora, ejecuta estos comandos en tu terminal:

1. Clona el repositorio:
git clone https://github.com/santicrak2017/mi-proyecto.git

2. Instala las dependencias:
npm install

3. Corre las pruebas:
npm test

4. Inicia la app:
npm start

## 🔗 Enlace de Despliegue
Puedes ver el estado del último despliegue aquí:
https://santicrak2017.github.io/mi-proyecto/

---
**Equipo:** 
Camilo Medina Sanchez
Santiago Zamora Garzón
Camilo Castillo Meneses
Nicolás Urrego Botero