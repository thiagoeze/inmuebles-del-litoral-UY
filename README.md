# 🏡 Inmuebles del Litoral

![GitHub](https://img.shields.io/badge/Git-GitHub-F05032?logo=git&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-En%20Desarrollo-yellow)
![Licencia](https://img.shields.io/badge/Licencia-Educativa-blue)

## 📖 Descripción

**Inmuebles del Litoral** es un proyecto desarrollado como parte de una práctica de **Gestión de Configuración de Software**, aplicando buenas prácticas de control de versiones mediante **Git** y **GitHub**.

El objetivo principal es implementar un flujo de trabajo basado en ramas que permita desarrollar nuevas funcionalidades de forma organizada, realizar pruebas antes de publicar cambios y mantener una versión estable del proyecto.

---

## 🎯 Objetivos

- Aplicar control de versiones utilizando Git.
- Gestionar un repositorio remoto mediante GitHub.
- Trabajar con una estrategia de ramificación (Branching Strategy).
- Simular un flujo de desarrollo profesional.

---

## 🌿 Estructura de Ramas

| Rama | Descripción |
|------|-------------|
| **produccion** | Contiene la versión estable y lista para su despliegue. |
| **Desarrollo** | Rama destinada al desarrollo de nuevas funcionalidades. |
| **pruebas** | Rama utilizada para validar cambios antes de integrarlos a producción. |

---

## 🔄 Flujo de Trabajo

```text
Desarrollo
      │
      ▼
   pruebas
      │
      ▼
 produccion
```

1. Se desarrolla una funcionalidad en la rama **Desarrollo**.
2. Los cambios son enviados a la rama **pruebas** para su validación.
3. Una vez aprobados, se integran a la rama **produccion**.

---

## 🛠 Tecnologías

- Git
- GitHub

---

## 📂 Estructura Inicial

```
inmuebles-del-litoral-xxxx/
│
├── README.md
└── (Archivos del proyecto)
```

---

## 🚀 Inicio Rápido

Clonar el repositorio:

```bash
git clone https://github.com/TU_USUARIO/inmuebles-del-litoral-xxxx.git
```

Ingresar al proyecto:

```bash
cd inmuebles-del-litoral-xxxx
```

Ver las ramas disponibles:

```bash
git branch -a
```

---

## 👨‍💻 Autor

**Thiago Peñaloza**

Estudiante de Informática – UTU  
Proyecto desarrollado con fines académicos.

---

## 📄 Licencia

Este proyecto tiene fines exclusivamente **educativos** y forma parte de una práctica académica sobre el uso de Git y GitHub.
