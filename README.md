# 🎬 CineMate

CineMate es una aplicación diseñada para mejorar la experiencia de los amantes del cine y las series, permitiéndoles descubrir contenido, recibir recomendaciones personalizadas, guardar su catálogo personal y hasta conversar con personajes mediante IA.  
El objetivo del proyecto fue crear una plataforma útil, dinámica y divertida, integrando módulos de recomendación, chatbot, cuestionarios inteligentes y funcionalidades sociales.

> Proyecto desarrollado como parte del trabajo final de la asignatura de **LIS**.  
> Trabajo completo disponible en la memoria del proyecto.

---

## 🚀 Funcionalidades principales

✔️ **Cartelera:**  
- Ver películas y series disponibles  
- Filtrar por género e intereses  
- Acceso a fichas técnicas y detalles  

✔️ **Biblioteca personal:**  
- Valorar, comentar y guardar contenido visto  
- Editar y organizar listas propias  

✔️ **Recomendaciones personalizadas:**  
- Algoritmos basados en historial, gustos y comportamiento  
- Recomendaciones híbridas usando embeddings y filtrado colaborativo  

✔️ **Chat con personajes utilizando IA:**  
- Chatbots que imitan personalidad y estilo de personajes reales  
- Sistema de prompts, cacheado y personalización  

✔️ **Cuestionarios inteligentes:**  
- Generación automática de trivias con Llama usando prompt engineering  
- Revisión manual para garantizar calidad  

✔️ **Funcionalidades sociales:**  
- Perfiles de usuario  
- Interacción con amigos  
- Sistema anti-spoilers  

---

## 🧠 Arquitectura del Proyecto

El proyecto se dividió en tres pilares:

| Componente | Descripción |
|-----------|-------------|
| **Frontend** | Interfaz interactiva conectada al backend mediante peticiones REST |
| **Backend (Gateway)** | Punto central de acceso, gestionando permisos, autenticación y conexión entre módulos |
| **Módulos IA** | Chatbots, generación de cuestionarios y sistema híbrido de recomendación |

Tecnologías clave:  
- Node.js (Gateway)  
- Python (IA y recomendaciones)  
- Ollama + Mistral 7B / Llama para NLP  
- APIs externas como *TheMovieDB* para obtención de datos  

---

## 🧪 Metodología de desarrollo

El proyecto se desarrolló utilizando **SCRUM** en sprints de 1–2 semanas, apoyándonos en herramientas como:

- 🗂️ **Jira** para la gestión de tareas y milestones  
- 🧩 División en equipos: Frontend, Backend e IA  
- 🗨️ Reuniones periódicas y comunicación continua mediante Discord  

---

## ⚙️ Sistema de versionado

- Repositorio gestionado con **GitHub**
- Rama `main` protegida y fusiones solo tras revisión y pruebas internas  
- Ramas por funcionalidad (`feature/chatbot`, `feature/recommender`, etc.)  

---

## 🧪 Testing

El proyecto implementó:

- ✔ Pruebas manuales con Postman  
- ✔ Pruebas de integración entre módulos  
- ✔ User Acceptance Tests al final del desarrollo  

Aunque las pruebas automatizadas no se implementaron, los métodos utilizados permitieron validar correctamente las funcionalidades y detectar errores a tiempo.  

---

## 🧩 Retos principales

Durante el desarrollo surgieron desafíos como:

- Importación, limpieza y estructura de datos desde **TheMovieDB**
- Configuración de base de datos en un servidor externo
- Integración de módulos independientes (Frontend ↔ Backend ↔ IA)
- Limitaciones técnicas de modelos de IA de acceso gratuito   

---

## 👨‍💻 Equipo

El proyecto fue desarrollado por:

- Arnau Altimira  
- Marc Checa  
- Joan Corral  
- Miquel Sánchez  
- Adrian Stoiciu  
- Álvaro Díaz  
- Jan Planas  
- José Ortín  

---

## 📌 Estado del proyecto

El proyecto está **funcional y completo en un 99%**, quedando pendiente únicamente la integración del inicio de sesión mediante Google.  

---

## 🏁 Conclusión

CineMate ha sido un proyecto ambicioso que ha permitido combinar tecnologías modernas, metodologías ágiles e inteligencia artificial para crear una aplicación práctica y entretenida.

El equipo está orgulloso del resultado final y su potencial como herramienta real para cinéfilos.    

---


