# Definición de Arquitectura Inicial
Versión 1.1


[]() | []()  
--|--
Objetivo| Definir la arquitectura inicial de un proyecto
Métricas utilizadas | Horas por día invertidas en la instalación e iniciación de cada tecnología seleccionada
Repositorio de Métricas | Documento [Arquitectura Inicial](https://github.com/CaveLabs-1/Wiki/tree/master/Arquitectura/Formatos/Formato%20Herson%20(Definición%20de%20Arquitectura%20Inicial).docx)
Entrada de Proceso | Forma en que se realizará el sistema
Criterios de Entrada | Lista de Requerimientos
Definir políticas y estándares |UML, Usar la guía del [Technology Stack Diagram](https://github.com/dwyl/technology-stack), Usar el [Proceso de Flujo de Vistas](https://github.com/CaveLabs-1/Wiki/blob/master/Arquitectura/Procesos/Definici%C3%B3n%20de%20Flujo%20de%20Vistas.md)
Salidas del proceso | [Arquitectura Inicial](https://github.com/CaveLabs-1/Wiki/tree/master/Arquitectura/Formatos/Formato%20Herson%20(Definición%20de%20Arquitectura%20Inicial).docx), [Technology Stack Diagram](https://github.com/dwyl/technology-stack) dentro de la Arquitectura Inicial , MER/Modelo lógico dentro del documento de la Arquitectura Inicial
Criterios de salida | <ul><li>[CheckList](https://docs.google.com/spreadsheets/d/1tsFZIO0N1t2lS3TvRM4B6UeH0GQi5VNAFdxPQ4Icq6k/edit?usp=sharing)</li><li>Los Modelos deben de seguir el estándar de UML</li></ul>


## Definición de Fases
No. de Fase | Fase | Actividades | Encargado | Áreas
------------|------|-------------|-----------|-------
1 | Definición |<ul><li>Establecer criterios para crear la arquitectura ([guía de criterios](https://github.com/CaveLabs-1/Wiki/blob/master/Arquitectura/Guias/Gu%C3%ADa%20de%20Criterios.md))</li><li>Ejecutar el [Proceso de Componentes de Sistema](https://github.com/CaveLabs-1/Wiki/blob/master/Arquitectura/Procesos/Definici%C3%B3n%20de%20Componentes%20del%20Sistema.md)</li><li>Ejecutar el [Proceso de Flujo de Vistas](https://github.com/CaveLabs-1/Wiki/blob/master/Arquitectura/Procesos/Definici%C3%B3n%20de%20Flujo%20de%20Vistas.md) y llenar el [Documento de Flujo de Vistas](https://github.com/CaveLabs-1/Wiki/tree/master/Arquitectura/Formatos/Formato%20Ernie%20(Flujo%20de%20Vistas%20y%20Arquitectura%20Inicial).docx)</li></ul>| Encargado de Arquitectura | PPQA y TS
2 | Validación |<ul><li>Validar la arquitectura con los requerimientos necesitados</li></ul>| Encargado de Arquitectura | VER
3 | Desarrollo |<ul><li>Desarrollar MER de la base de datos según el flujo </li><li>Escoger Tecnología a usarse ya sean Back end framework, front end framework, base de datos, middleware, etc.)</li><li>Desarrollar [Technology Stack Diagram](https://github.com/dwyl/technology-stack) </li></ul> | Encargado de Arquitectura | PPQA y TS
4 | Implementación | <ul><li>Preparar la tecnología a usarse *(ejemplo: framework con middleware y base de datos inicializada)*</li></ul> | Encargado de Arquitectura | TS
5 | Documentación |<ul><li>Llenar [Arquitectura Inicial](https://github.com/CaveLabs-1/Wiki/tree/master/Arquitectura/Formatos/Formato%20Herson%20(Definición%20de%20Arquitectura%20Inicial).docx) y mantener los diagramas con el estándar UML o de las guías</li></ul>| Team Member | TS
6 | Análisis de Métricas | <ul><li>Medir las horas invertidas en la preparación de cada tecnología a usarse y en caso de cambios o crecimiento actualizarla</li></ul> | Architecture Owner | MA

## Plan de implementación

1. Publicar los documentos en su respectiva sección de la wiki y avisar a los miembros del equipo que está publicado por Slack
2. Presentar a los encargados de Arquitectura en flujo de los procesos correspondientes a esta área

## Bitácora


No. de Versión | Cambio | Autor | Aprobado | Fecha de cambio
---------------|--------|-------|----------|----------------
1.0 | Creación y Llenado de Documento | David Ramírez y Marco Luna | Valter Núñez | 2/2/2018
1.1 | Entrada del Proceso, Checklist, Áreas del CMMI, Cambio de Nombres a Documentos | Marco Luna | Valter Núnez | 07/05/2018
