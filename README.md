# Trabajo Práctico: Introducción a CI/CD con GitHub Actions
## Materia: Programación de Vanguardia 

### Link: https://grupo-6-cicd.netlify.app/

Este repositorio contiene la resolución del Trabajo Práctico de introducción a la Integración y Despliegue Continuo (CI/CD) para la materia **Programación de Vanguardia**. 

El objetivo principal del proyecto es comprender de forma práctica el flujo de trabajo con Git, la automatización de tareas mediante GitHub Actions y la publicación automatizada en un entorno de producción (Netlify).

---

## 👥 Integrantes Grupo 6
* **Rodrigo Morel**
* **Adrian Guirao**
* **Braian Arguello**
* **Maia Cordeiro**
* **Pablo Maurig**
* **Luis Andaur**

---

## 🛠️ Tecnologías Utilizadas
* **Frontend:** HTML5, CSS3 y JavaScript nativo.
* **CI/CD Platform:** GitHub Actions.
* **Hosting / Despliegue:** Netlify (vía Netlify CLI oficial).

---

## 📂 Estructura del Proyecto

Tal como se observa en el espacio de trabajo, el proyecto mantiene una estructura limpia y orientada puramente a la web estática, eliminando dependencias innecesarias de Node.js en el entorno local:

```text
GRUPO_6_TP-CICD-VANGUARDIA/
│
├── .github/
│   └── workflows/
│       └── deploy.yml      # Configuración del pipeline de GitHub Actions
│
├── .gitignore              # Archivos y carpetas ignorados por Git
├── index.html              # Estructura principal de la aplicación de práctica
├── style.css               # Estilos de la aplicación
├── script.js               # Funciones de la aplicación
└── README.md               # Documentación del proyecto (este archivo)