# PilarBus
## PilarBus es una aplicación móvil y plataforma web destinada a facilitar el uso del transporte público en el partido de Pilar, Buenos Aires. Su objetivo es permitir que los usuarios consulten recorridos, paradas y ubicación de los colectivos en tiempo real.

## Control de versiones y Pull Requests

Para organizar el desarrollo del proyecto se utilizará GitHub como plataforma de almacenamiento y control de versiones del código fuente.

Cada integrante trabajará en una rama independiente (branch), donde podrá desarrollar nuevas funcionalidades o corregir errores sin modificar directamente la rama principal (main).

Una vez finalizados los cambios, se creará un Pull Request (PR), que permitirá proponer la incorporación del código a la rama principal. Antes de aprobarlo, otro integrante podrá revisar las modificaciones y comprobar que cumplan con los requisitos establecidos.

Este procedimiento permite detectar errores, mejorar la calidad del código y evitar modificaciones incorrectas en la versión principal de PilarBus.

# Integración y Entrega Continua (CI/CD)

Se implementará un proceso de Integración y Entrega Continua (CI/CD) utilizando GitHub Actions, con el propósito de automatizar la validación del código y garantizar que los cambios realizados funcionen correctamente antes de ser publicados.

Cada vez que se cree o actualice un Pull Request, se ejecutará automáticamente un flujo de trabajo compuesto por las siguientes etapas:

1. Build (Compilación)

En esta etapa, el sistema verificará que el código pueda compilarse correctamente y que no presente errores que impidan la construcción de la aplicación. Esto permitirá detectar problemas desde las primeras etapas del desarrollo.

2. Test (Pruebas automatizadas)

Se ejecutarán pruebas automatizadas para comprobar que las funcionalidades desarrolladas funcionen según lo esperado. De esta manera, será posible identificar errores y evitar que los cambios afecten el funcionamiento de otras partes del sistema.

Si alguna de estas etapas presenta fallas, el Pull Request quedará bloqueado para su integración hasta que los problemas sean corregidos y las validaciones se ejecuten correctamente.

3. Deploy (Despliegue)

Una vez aprobado el Pull Request y superadas las etapas de Build y Test, los cambios podrán integrarse a la rama principal del proyecto.

Posteriormente, se realizará el despliegue de la aplicación en un entorno de prueba (Staging), donde se verificará su correcto funcionamiento. Finalmente, luego de completar las comprobaciones necesarias y obtener la aprobación correspondiente, se procederá a publicar la aplicación en el entorno de producción.

Objetivo del proceso

La implementación de CI/CD permitirá reducir errores, automatizar tareas repetitivas, mejorar la calidad del código y facilitar la publicación de nuevas versiones de la aplicación de manera más segura y organizada.

(FLUJO DE TRABAJO ) 



Beneficios de implementar CI/CD

La implementación de Integración y Entrega Continua (CI/CD) mediante GitHub Actions ofrece diferentes beneficios para el desarrollo de PilarBus:

- Detección temprana de errores: permite identificar problemas en el código mediante pruebas automáticas antes de integrar los cambios.
- Automatización del proceso: reduce las tareas manuales al ejecutar automáticamente las etapas de Build y Test cada vez que se actualiza un Pull Request.
- Mejora de la calidad del software: ayuda a comprobar que las nuevas funcionalidades no afecten el funcionamiento de las existentes.
- Trabajo colaborativo: facilita la integración de los cambios realizados por los distintos integrantes del equipo.
- Mayor seguridad en las actualizaciones: permite verificar los cambios antes de incorporarlos a la rama principal y realizar su despliegue.
- Entregas más rápidas y organizadas: facilita la publicación de nuevas versiones en los entornos de prueba (Staging) y producción.

En conclusión, CI/CD permite mantener un proceso de desarrollo más controlado y eficiente, reduciendo errores y facilitando la incorporación de nuevas funcionalidades a PilarBus.

## Conclusión

La utilización conjunta de Pull Requests y CI/CD permitirá mantener un proceso de desarrollo más organizado, seguro y eficiente. De esta manera, PilarBus podrá incorporar nuevas funcionalidades y correcciones con mayor confianza, asegurando que cada versión que llegue a producción haya pasado previamente por controles de calidad.
