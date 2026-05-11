# Tarea 17: Desarrollo Web con DataFlex y MySQL

Este repositorio contiene la entrega final para la Tarea 17 del módulo de Sistemas de Gestión Empresarial. El proyecto consiste en una aplicación web completa desarrollada con **DataFlex 2025** y un motor de base de datos **MySQL 8.4**.

## Contenido del Proyecto

*   **Informe Técnico**: [Tarea17_Informe_TrujilloVallejoGabriel.pdf](./Tarea17_Informe_TrujilloVallejoGabriel.pdf) - Documentación detallada de la arquitectura, troubleshooting y manual de usuario.
*   **Código Fuente**: Carpeta `FutbolWebApp` con todos los componentes del sistema (Views, Data Dictionaries y CSS personalizado).
*   **Base de Datos**: [futbolBD.sql](./futbolBD.sql) - Script para la recreación del esquema y los datos iniciales.

## Características Principales

*   **Arquitectura RAD**: Implementación de diccionarios de datos para la validación de reglas de negocio en el servidor.
*   **Patrón Select & Zoom**: Interfaz optimizada para dispositivos móviles y navegación táctil.
*   **Relación Many-to-Many**: Gestión avanzada de las posiciones de los jugadores mediante tablas de unión.
*   **Diseño Corporativo**: Estética profesional alineada con los estándares de Data Control.

## Requisitos de Ejecución

1.  Importar el script `futbolBD.sql` en un servidor MySQL 8.x.
2.  Configurar la conexión ODBC de 64 bits hacia la base de datos `futbol`.
3.  Abrir el Workspace `FutbolWebApp.sws` en DataFlex Studio 2025.
4.  Compilar y desplegar en el servidor IIS local.

---
**Autor:** Gabriel Trujillo Vallejo  
**Centro:** CESUR  
**Proyecto:** FutbolWebApp - Gestión Deportiva
