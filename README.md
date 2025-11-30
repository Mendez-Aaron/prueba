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
