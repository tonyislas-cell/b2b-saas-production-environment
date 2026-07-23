# B2B SaaS Production Environment Architecture

Este repositorio documenta la estructura de despliegue y los flujos de autenticación utilizados para entornos de producción en aplicaciones B2B (como plataformas de automatización con IA y agendamiento).

## Infraestructura Core
* **Hosting / Despliegue:** Vercel.
* **Gestión de Entorno:** Configuración estricta de variables de entorno para producción y desarrollo.

## Flujos de Autenticación (OAuth & APIs)
La arquitectura integra los siguientes protocolos de seguridad para la conexión con servicios de terceros:
1. **Google Calendar OAuth:** Generación y gestión de tokens de producción para el acceso y automatización de agendas.
2. **Meta Business Suite:** Verificación y validación de protocolos de la API para la automatización de comunicaciones.

*Nota: El código fuente, los tokens de acceso y las claves API de los entornos de producción están estrictamente excluidos de este repositorio público.*
