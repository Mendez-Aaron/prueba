<div align="center">

# 📚 RevisorIA  
**Plataforma colaborativa para la revisión automática de trabajos académicos mediante IA**

Un entorno web moderno construido con el stack **MERN**, integrando análisis avanzado, automatización y herramientas de inteligencia artificial para mejorar la productividad y calidad del trabajo académico.

</div>

---

## 📖 Tabla de Contenidos
- [Descripción General](#-descripción-general)
- [Características](#-características)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Arquitectura del Proyecto](#-arquitectura-del-proyecto)
- [Metodología TDD](#-metodología-tdd)
- [Suite de Pruebas](#-suite-de-pruebas)
- [Instalación y Desarrollo](#-instalación-y-desarrollo)
- [Docker](#-docker)
- [Estado del Proyecto](#-estado-del-proyecto)
- [Roadmap](#-roadmap)
- [Contribución](#-contribución)
- [Video Explicativo](#-video-explicativo)

---

## 📘 Descripción General

**RevisorIA** es una plataforma web modular diseñada para:

- Automatizar la revisión de documentos académicos  
- Detectar plagio y analizar calidad  
- Facilitar el trabajo colaborativo  
- Proveer métricas avanzadas e informes detallados  

Construida con un enfoque profesional orientado a pruebas, CI/CD y arquitectura escalable.

---

## 🚀 Características

- ✔️ Revisión automática con IA  
- 👥 Colaboración en tiempo real  
- 📊 Detección de plagio y análisis semántico  
- 🔔 Notificaciones inteligentes  
- 📈 Informes con métricas avanzadas  
- 🛠️ Arquitectura escalable bajo el stack MERN  

---

## 🛠️ Tecnologías Utilizadas

### **Frontend**
- React 18 + Vite  
- Context API  
- CSS Modules  
- Axios  

### **Backend**
- Node.js + Express  
- MongoDB Atlas + Mongoose  
- JWT  
- Multer  

### **IA & Automatización**
- OpenAI API  
- n8n para orquestación  

### **Calidad de Código**
- Jest  
- SuperTest  
- Cobertura automatizada  

### **DevOps**
- Docker + Docker Compose  
- GitHub Actions (CI/CD)  

---

## 🧱 Arquitectura del Proyecto

```text
📂 RevisorIA/
│
├── .github/              # Workflows de CI/CD
│   └── workflows/
│
├── Documentos/           # Documentación del proyecto
│
├── backend/              # Servidor Node.js
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── tests/
│   ├── uploads/
│   ├── Dockerfile
│   ├── Dockerfile.dev
│   └── server.js
│
├── frontend/             # Aplicación React (Vite)
│   ├── public/
│   ├── src/
│   ├── Dockerfile
│   ├── Dockerfile.dev
│   └── vite.config.js
│
├── docker-compose.yml
├── docker-compose.test.yml
└── README.md



🧪 Metodología TDD

RevisorIA adopta el ciclo:

🔴 ROJO — Escribir pruebas antes del código
🟢 VERDE — Implementación mínima para cumplir la prueba
🔵 REFACTOR — Mejorar el código manteniendo pruebas verdes
Cobertura de Lógica de Negocio

Gestión de Documentos

Subida y validación de PDFs

Metadatos

Recuperación segura

Procesamiento de Contenido

Extracción de texto

Detección de plagio

Reportes de originalidad

Autenticación

Registro / Login

JWT

Control de acceso

Frontend

Formularios

Dashboard

Visualización de análisis

🧪 Suite de Pruebas

Framework: Jest
Tipos: Unitarias • Integración • E2E
Cobertura: Thresholds configurados

Ejecutar pruebas
# Todas las pruebas
npm test

# Modo watch
npm run test:watch

# Reporte de cobertura
npm run test:coverage

🚀 Instalación y Desarrollo
Prerrequisitos

Node.js 18+

MongoDB (local o Atlas)

Clave de OpenAI API

Clonar repositorio
git clone https://github.com/Mendez-Aaron/Proyectos_2
cd Proyectos-2

Instalar dependencias
Backend
cd backend
npm install

Frontend
cd ../frontend
npm install

Ejecutar en desarrollo

Backend (puerto 3001):

npm run dev


Frontend (puerto 5173):

npm run dev

🐳 Docker
Construir y ejecutar
docker-compose up --build

Servicios específicos
docker-compose up backend frontend

📊 Estado del Proyecto
🟢 Completado

Base MERN

JWT

Sistema de subida de archivos

CI/CD

Dockerización

Suite de pruebas inicial

🟡 En desarrollo

Integración con OpenAI

Panel colaborativo

Panel de administración

Mejoras en cobertura de pruebas

🗺️ Roadmap

🔍 Análisis avanzado de plagio

🔔 Notificaciones en tiempo real

📤 Exportación de informes

🔄 Integración total con n8n

🤝 Contribución

Hacer fork

Crear rama feature

Commit + push

Abrir Pull Request

Reglas:

✔️ Todas las pruebas deben pasar

✔️ Mantener o mejorar cobertura

✔️ Seguir convenciones del proyecto

🎥 Video Explicativo

https://drive.google.com/file/d/1Ugr9u4625QYEHF3ft4SPxVihrS6b0YiM/view

<div align="center">
✨ RevisorIA — Construyendo el futuro de la revisión académica
</div> ```
