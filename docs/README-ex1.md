<p align="center">
  <img src="/img/logo-epigijon.png" alt="EPI Gijón logo" width="200"/>
</p>

# Práctica 1: Tecnologías de Servidor

## Alumnos

- Cristian Augusto - UO237600@uniovi.es @augustocristian
- Enol García - UOXXXX@uniovi.es @enolgargon

## Navigation Map
A continuación se presenta el mapa de navegación de la aplicación.

````mermaid
---
title: Navigation Diagram
---
stateDiagram-v2
    index --> AltaForm : alta
    AltaForm --> listado : exito
    index --> listado : exito
    listado --> listado : exit
    listado --> EditForm : editar
    EditForm --> listado : exito
    
    * --> error : error
````
