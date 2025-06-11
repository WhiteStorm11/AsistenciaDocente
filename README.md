# Sistema de Gestión de Asistencia Docente

Este proyecto tiene como objetivo desarrollar un **Sistema de Gestión de Asistencia Docente** para la **Secretaría de Educación de Sincelejo**, basado en **microservicios**. Utiliza tecnologías como **Node.js**, **MongoDB**, **JWT** para autenticación y **React** para el frontend.

## Descripción

Este sistema gestiona la **asistencia docente** mediante un lector de **código QR**. Cada docente o estudiante tiene un código QR único que se escanea para registrar su entrada. El sistema incluye múltiples microservicios encargados de gestionar la autenticación, el registro de asistencia, la generación de reportes y las notificaciones.

### Microservicios

- **auth-service**: Gestiona la autenticación de los usuarios.
- **attendance-service**: Registra la asistencia de los docentes y estudiantes mediante un código QR.
- **permission-service**: Gestiona las solicitudes de permisos de los docentes.
- **reporting-service**: Genera reportes relacionados con la asistencia y permisos.
- **notification-service**: Envía notificaciones a los usuarios cuando se registra asistencia o se aprueban permisos.
- **statistics-service**: Proporciona estadísticas sobre la asistencia y el rendimiento.

### Frontend

El **frontend** está construido con **React** y proporciona una interfaz de usuario donde los usuarios pueden:
- Iniciar sesión.
- Escanear códigos QR para registrar asistencia.
- Visualizar reportes y estadísticas.
- Ver la gestión de asistencia en tiempo real.

---

## Requisitos Previos

Asegúrate de tener lo siguiente antes de ejecutar el proyecto:

- **MongoDB** (Mongo DB Compass) para la base de datos.
- **Node.js** instalado.
- **npm** .


