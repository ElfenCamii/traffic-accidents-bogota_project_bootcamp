# Contribuir al Proyecto

Este documento explica el flujo de trabajo y las reglas que seguimos en este repositorio.

---

## 🚀 Flujo de ramas

Usamos la siguiente estrategia de ramas:

- **`main`** → contiene la versión estable y lista para producción.  
- **`develop`** → contiene la versión en desarrollo, donde se integran nuevas funciones antes de pasar a `main`.  
- **`feature/[nombre]`** → ramas personales o de nuevas funciones. Ejemplo: `feature/login` o `feature-juan`.

---

## 📥 Cómo empezar

1. **Clona el repositorio:**
   
   git clone https://github.com/ElfenCamii/traffic-accidents-bogota_project_bootcamp.git
   cd traffic-accidents-bogota_project_bootcamp

2. **Crea tu rama personal o de funcionalidad desde `develop`:**
   
   git checkout develop
   git pull origin develop
   git checkout -b feature/tu-nombre

3. **Haz tus cambios y confirma commits claros:**
   
   git add .
   git commit -m "feat: agrega validación de formularios"

4. **Sincroniza tu rama con `develop` antes de subir:**
   
   git pull origin develop

5. **Sube tu rama al repositorio remoto:**
   
   git push origin feature/tu-nombre

---

## 🔄 Pull Requests (PR)

1. Asegúrate de que tu rama esté actualizada con `develop`.  
2. Abre un **Pull Request** desde tu rama `feature/...` hacia `develop`.  
3. Espera revisión de tus compañeros antes de hacer *merge*.  

---

## ✅ Buenas prácticas

- Usa **mensajes de commit descriptivos**:
  - `feat:` para nuevas funciones.
  - `fix:` para corregir errores.
  - `docs:` para cambios en documentación.
  - `refactor:` para mejoras de código sin cambiar funcionalidad.
- Evita subir archivos innecesarios (usa `.gitignore`).
- Mantén ramas pequeñas y enfocadas en una sola tarea.

---

## 💬 Dudas

Si tienes dudas, abre un **Issue** en GitHub o pregunta en el canal del equipo.



# Contributing to the Project

Thank you for your interest in contributing!  
This document explains the workflow and rules we follow in this repository.

---

## 🚀 Branch Workflow

We use the following branch strategy:

- **`main`** → contains the stable, production-ready version.  
- **`develop`** → contains the development version, where new features are integrated before merging into `main`.  
- **`feature/[name]`** → personal or feature branches. Example: `feature/login` or `feature-john`.

---

## 📥 Getting Started

1. **Clone the repository:**
   
   git clone https://github.com/ElfenCamii/traffic-accidents-bogota_project_bootcamp.git
   cd traffic-accidents-bogota_project_bootcamp

2. **Create your personal or feature branch from `develop`:**
   
   git checkout develop
   git pull origin develop
   git checkout -b feature/your-name

3. **Make your changes and commit with clear messages:**
   
   git add .
   git commit -m "feat: add form validation"

4. **Sync your branch with `develop` before pushing:**
   
   git pull origin develop

5. **Push your branch to the remote repository:**
   
   git push origin feature/your-name

---

## 🔄 Pull Requests (PR)

1. Make sure your branch is up-to-date with `develop`.  
2. Open a **Pull Request** from your `feature/...` branch to `develop`.  
3. Wait for teammates' review before merging.  

---

## ✅ Best Practices

- Use **descriptive commit messages**:
  - `feat:` for new features.
  - `fix:` for bug fixes.
  - `docs:` for documentation updates.
  - `refactor:` for code improvements without changing functionality.
- Avoid pushing unnecessary files (use `.gitignore`).
- Keep branches small and focused on a single task.

---

## 💬 Questions

If you have questions, open an **Issue** on GitHub or ask in the team channel.