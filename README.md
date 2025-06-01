# 🚀 Prueba Técnica Full-Stack Developer - Agricapital

Este repositorio contiene los entregables documentales y de diseño para la Prueba Técnica de Desarrollador Full-Stack de Agricapital. Aquí se presenta una visión integral de la arquitectura propuesta, los flujos de interacción y las estrategias clave para la gestión y evolución del sistema.

## 📦 Contenido del Repositorio

El contenido se organiza de la siguiente manera para facilitar su revisión:

### 📄 1. Documentación Técnica

Todos los documentos detallados que complementan la solución se encuentran en formato PDF para una fácil lectura y distribución.

* **Informe de Mejora Continua.pdf**: Documento que detalla los riesgos identificados durante el desarrollo, estrategias de mitigación, propuestas para la escalabilidad futura de la plataforma y optimizaciones de costos/rendimiento. 📈
* **Estrategia de Versionado de API y Migraciones de BD.pdf**: Explica la metodología propuesta para el versionado de la API (vía path) y la gestión de cambios en el esquema de la base de datos (con herramientas como Alembic), asegurando la compatibilidad y la consistencia en el tiempo. 🔄
* **Flujo de Usuario y Empleado.pdf**: Una descripción narrativa de las interacciones principales dentro de la plataforma, detallando los caminos que siguen los clientes para solicitar microcréditos y los empleados para gestionar dichas solicitudes. 🚶‍♂️➡️👩‍💼

### 📊 2. Diagramas de Arquitectura y Flujo de Datos

Se incluyen dos diagramas clave para ofrecer una comprensión visual de la estructura del sistema y el manejo de la información.

* **Diagrama de Arquitectura (Esquemático). agricapipal-pt-back.drawio**:
    * Este diagrama proporciona una visión general de alto nivel de la arquitectura de microservicios implementada. Muestra los componentes principales del sistema (Front-end, Microservicio de Solicitudes, Servicio de Usuarios & Autenticación, Servicio de Notificaciones) y sus interacciones. 🏗️

* **Diagrama de Flujo de Datos e Información. dfd.drawio**:
    * Este diagrama ilustra el movimiento y la transformación de la información a través de los diferentes componentes del sistema. Detalla cómo los datos ingresan, son procesados, almacenados (Base de Datos), y cómo fluyen entre los microservicios (Input/Output). Cubre aspectos como el cálculo de riesgo, la persistencia de solicitudes y el envío de notificaciones. 🌊
