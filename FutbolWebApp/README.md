# DataFlex FutbolWebApp 2025

[![DataFlex](https://img.shields.io/badge/Framework-DataFlex_2025-blue.svg)](https://www.dataaccess.com/)
[![Database](https://img.shields.io/badge/Database-MySQL_8.4-orange.svg)](https://www.mysql.com/)
[![License](https://img.shields.io/badge/Corporate-Data_Control-darkgreen.svg)](#)

## 📋 Descripción del Proyecto

Este proyecto constituye la **Tarea 17** del ciclo formativo DAM, desarrollada bajo los estándares de calidad de **Data Control**. Se trata de una aplicación web móvil robusta para la gestión integral de una liga de fútbol, implementada con **DataFlex Studio 2025** y conectada a un motor **MySQL** mediante el proceso de *Upsizing*.

## 🚀 Características Principales

- **Arquitectura Web Mobile**: Interfaz optimizada para dispositivos táctiles mediante el uso de `cWebView`.
- **Dashboard Interactivo**: Panel de control principal con enrutamiento dinámico (`NavigatePath`) hacia las entidades del sistema.
- **Gestión de Entidades (Patrón Select & Zoom)**:
  - Jugadores
  - Equipos
  - Entrenadores
  - Ligas
  - Posiciones
- **Persistencia en MySQL**: Migración completa de datos y lógica de integridad referencial gestionada mediante Diccionarios de Datos (`DDSrc`).

## 🛠️ Stack Tecnológico

- **IDE**: DataFlex Studio 2025.
- **Base de Datos**: MySQL 8.4 Server.
- **Conectividad**: DataFlex MySQL Connectivity Kit.
- **Metodología**: Git Flow (Estrategia de ramas `main`, `develop` y `feature`).

## 📂 Estructura del Repositorio

- `AppSrc/`: Contiene los archivos de las vistas web (`.wo`) y el Dashboard.
- `DDSrc/`: Diccionarios de Datos que encapsulan las reglas de negocio y validaciones.
- `AppHtml/`: Recursos web estáticos e interfaz de entrada.
- `mockups/`: Evidencias visuales y prototipos utilizados en la fase de diseño.

## ⚙️ Instalación y Despliegue

1. Clonar el repositorio: `git clone https://github.com/gabrielCesur/DataFlex.git`
2. Configurar el espacio de trabajo en **DataFlex Studio 2025**.
3. Importar el esquema `futbolBD.sql` en una instancia de MySQL.
4. Ajustar la cadena de conexión en el archivo `Database.ini` (no incluido por seguridad).
5. Compilar y desplegar en IIS (Internet Information Services).

---
**Desarrollado por**: Gabriel Trujillo Vallejo  
**Supervisión**: Santiago David - Departamento de Sistemas, Data Control.
