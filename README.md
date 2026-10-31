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