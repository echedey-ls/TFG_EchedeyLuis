# Plantilla TFGs ETSIINF UPM

Esta plantilla recoge todo lo necesario para poder redactar los planes de trabajo y la memoria del Trabajo de Fin de Grado en la Escuela Técnica Superior de Ingeniería Informática de la Universidad Politécnica de Madrid.

Esta plantilla no es oficial, pero está basada en ella, habiendo cambiado y añadido información en pos de facilitar su uso y desarrollo.

También se incluye una plantilla para la realización de los dos Planes de Trabajo que se han de presentar a lo largo del desarrollo del Trabajo de Fin de Grado, incluyendo el Diagrama de Gannt correspondiente al planning de las tareas a desarrollar.

La estructura de esta plantilla es la siguiente:
- images: Directorio donde guardar las imagenes y pdfs que se usarán en la memoria.
- include: Directorio con la definición de la portada y la importación de los paquetes que se usarán.
- plan-trabajo: Directorio donde desarrollar los dos documentos básicos de Plan de Trabajo (cogen la información del alumno del fichero _DatosTFG.tex de forma automática)
- secciones: Directorio con las secciones que conforman la memoria del TFG
- bibliography.bib: Fichero que contiene las citas bibliográficas que se han usado durante el desarrollo del TFG y se incluirán en el mismo.
- tfg_etsiinf_NombreApellido: Documento principal en el que se incluyen, mediante las sentencias "input", la portada y todas las secciones definidas en "secciones", así como la información del alumno y todos los paquetes. RENOMBRAR CON EL NOMBRE Y APELLIDOS DEL ALUMNO.

Esta plantilla es solo una forma de redactar y crear el documento que se entregará como Memoria del TFG. No es obligatorio seguir esta plantilla, pero sí basarse en la plantilla oficial dada por la ETSIINF.

## Información oficial

Toda la información, normas, y plantilla original dada por la ETSIINF, se encuentra en la pagina de "Recomendaciones sobre el contenido de la Memoria Final" (https://www.fi.upm.es/?pagina=1475)

A continuación se muestra la información más relevante a la hora de usar esta plantilla, pero se recomienda encarecidamente leer toda la información dada en la plantilla que da la ETSIINF en el enlace anterior.

### Introducción

El esquema básico de una memoria final de TFG es el siguiente:
- Resumen en español e inglés (máximo 2 páginas cada uno)
- Tabla de contenidos (Índice)
- Introducción (con los objetivos del TFG)
- Desarrollo
- Resultados y conclusiones
- Análisis de impacto
- Bibliografía (publicaciones utilizadas en el estudio y desarrollo del trabajo)
- Anexos (opcional)

En cualquier caso, es el tutor del TFG quien indicará a su estudiante la estructura de memoria final que mejor se ajuste al trabajo desarrollado.

Para elaborar la memoria final del TFG con esta plantilla, se deben seguir los siguientes pasos:

- Cambiar el nombre del documento principal para que incluya el nombre del alumno ("tfg_etsiinf_NombreApellido.tex")
- Modifica los datos de tu TFG en el fichero "_DatosTFG.tex", en el directorio "secciones".
- Observa el fichero documento principal y cómo se van incluyendo los contenidos de la memoria a partir de los ficheros en el directorio secciones.
- Por supuesto puedes modificar la estructura de secciones propuestas para adecuarla al tipo de trabajo que realices (no olvides modificar y reordenar las sentencias "input" en el documento principal).
