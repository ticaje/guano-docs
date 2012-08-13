Proyecto Guano
======================

Introducción
------------

El presente documento se centrará en especificar las pautas a seguir para el desarrollo del proyecto, no solo centrándose en la parte de desarrollo para la consecución de la aplicación sino en las metodologías y pasos a seguir durante el proceso de desarrollo, documentación, puesta en marcha y mantenimiento del mismo.

“Guano” es el nombre del proyecto que un grupo de amigos ha querido llevar a cabo para la venta de paquetes turísticos, en principio, a Cuba. Basándose los autores del mismo en la experiencia previa con este tipo de proyectos han decidido implementar una solución Open Source que satisfaga las necesidades del sistema a desarrollar, siempre reutilizando las lógicas de negocio ya implementadas y que se ajusten a los requerimientos del software basadas siempre en el Software Libre.

Por tanto se definirán aqui las consideraciones generales del proyecto, convenciones y aspectos que ayuden a crear una dinámica de trabajo amigable y orgánica con vistas a potenciar el desarrollo de la aplicación de forma ágil, escalable y eficiente.

Estructura del proyecto.
------------------------

El proyecto se va a estructurar de la siguiente forma:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

    * Documentación
		Recoge todo lo relativo a la documentación del 	proyecto, incluido el presente docuemnto.
    * Aplicación:
	    Directorio donde se almacena toda la aplicación, framework, bundles, asstes etc.
    * Control: 
        Directorio donde se almacenan los logs, cache 	etc...
