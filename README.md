# 🛠️ Guía DevOps para Systems Logic

Este repositorio contiene la estructura de referencia para implementar prácticas DevOps en pequeñas empresas que operan en entornos cloud, específicamente diseñado para equipos con recursos limitados. Forma parte del Trabajo Final de Máster "Implementación Incremental de DevOps: Estrategias Adaptadas para Equipos pequeños en Entornos de Nube".

> 📌 Proyecto teórico desarrollado en colaboración con Systems Logic (Costa Rica) como caso de estudio real.

---

## 🚀 Objetivo

Diseñar un entorno de trabajo DevOps teórico-práctico, accesible y escalable, orientado a empresas que estén en proceso de modernización hacia servicios cloud. Se incluyen buenas prácticas, herramientas gratuitas, estructuras modulares y flujos automatizados.

---

## 📁 Estructura del Proyecto

```
devops-guia/
│
├── README.md                      → Este archivo
├── .gitignore                     → Exclusiones comunes por stack
├── src/                           → Código fuente principal
├── tests/                         → Pruebas unitarias y de integración
├── scripts/                       → Scripts de despliegue o utilitarios
└── .github/
    └── workflows/                 → Archivos de CI/CD (GitHub Actions)
```

---

## 🧩 Funcionalidades contempladas

- 🔸 Repositorio con control de versiones mediante Git y GitHub.
- 🔸 Automatización del proceso de integración continua (CI).
- 🔸 Plantillas de workflows para testing, análisis de código y despliegue.
- 🔸 Flujo completo de CI/CD documentado y adaptable.
- 🔸 Uso de herramientas gratuitas: GitHub Actions, SonarCloud, Grafana, etc.

---

## 🛠️ Stack de herramientas

| Fase            | Herramientas principales                  |
|------------------|-------------------------------------------|
| Control de versiones | Git + GitHub                           |
| CI/CD               | GitHub Actions                          |
| Testing             | Jest / NUnit / xUnit / Cypress          |
| Análisis de código  | SonarCloud                              |
| Despliegue          | PowerShell + WebDeploy / Azure CLI      |
| Monitoreo           | Grafana + Loki                          |
| Planificación       | GitHub Projects                         |

---

## 📦 Primeros pasos

1. Clona el repositorio:
   ```bash
   git clone https://github.com/systems-logic/devops-guia.git
   cd devops-guia
   ```

2. Instala las dependencias (según el stack de tu proyecto: Node.js, .NET, etc.)

3. Ejecuta los workflows configurados o crea tus propios flujos en `.github/workflows/`.

---

## 🔄 Workflows CI/CD

Este repositorio incluye plantillas para flujos de automatización con GitHub Actions:

- `ci.yml`: ejecución de pruebas y análisis al hacer push en ramas `feature/*`.
- `cd.yml`: despliegue automático al fusionar a `main`.

Puedes encontrarlos en:

```
.github/workflows/
```

---

## 👨‍💻 Contribuciones

Este entorno fue diseñado como base académica, pero puede ser adaptado y extendido para fines profesionales. Las pull requests son bienvenidas si estás colaborando dentro de Systems Logic o en el máster.

---

## 📚 Documentación asociada

- Trabajo Final de Máster – Máster en DevOps & Cloud Computing, INESDI Business Techschool.
- Guía metodológica incluida en los documentos del TFM.

---

## 🧠 Autoría

Grupo 01 – Máster DevOps & Cloud Computing  
- David Andrés Gutiérrez Mora  
- John Jeisson Mayorga Ramos
- Carlos Roldan Rodriguez
<<<<<<< HEAD
=======
- Carlos Roldan Rodriguez
>>>>>>> 800b8d7e4485ab96471b3a92f3bc86c8e5f13fd6

---

## 📝 Licencia

Este proyecto es de uso educativo. Si deseas usarlo profesionalmente, contáctanos para adaptarlo según tu organización.

<<<<<<< HEAD
#
#
=======
##
##
>>>>>>> 800b8d7e4485ab96471b3a92f3bc86c8e5f13fd6
>>>>>>> 
###
