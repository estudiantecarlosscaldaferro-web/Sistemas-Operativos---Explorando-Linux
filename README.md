# 🐧 Ubuntu 24.04 LTS (Noble Numbat) - Guía de Instalación

![Ubuntu Banner](https://img.shields.io/badge/OS-Ubuntu%2024.04%20LTS-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Status](https://img.shields.io/badge/Status-Stable-brightgreen?style=for-the-badge)

Este repositorio contiene la documentación detallada, scripts de post-instalación y configuraciones recomendadas para desplegar **Ubuntu 24.04 LTS**. Ideal para desarrolladores y entusiastas que buscan un entorno de trabajo sólido y optimizado.

---

## 🚀 Requisitos del Sistema

Antes de empezar, asegúrate de que tu hardware cumple con los mínimos para una experiencia fluida:

| Componente | Requisito Mínimo | Recomendado |
| :--- | :--- | :--- |
| **Procesador** | Dual-core 2 GHz | Quad-core o superior |
| **RAM** | 4 GB | 8 GB o más |
| **Almacenamiento** | 25 GB | 100 GB (SSD preferible) |
| **Gráficos** | VGA 1024x768 | Aceleración hardware |

---

## 🛠️ Proceso de Instalación Paso a Paso

### 1. Preparación del Medio
1. Descarga la ISO oficial desde [ubuntu.com](https://ubuntu.com/download/desktop).
2. Flashea la imagen en un USB (mínimo 8GB) usando herramientas como **Etcher**, **Rufus** o `dd` en terminal.


Una vez dentro del escritorio, abre la terminal (**Ctrl + Alt + T**) y ejecuta estos comandos para optimizar el sistema:

### 1. Actualización General
```bash
sudo apt update && sudo apt upgrade -y
