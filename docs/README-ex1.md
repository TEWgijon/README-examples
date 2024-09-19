<p align="center">
  <img src="/img/logo-epigijon.png" alt="EPI Gijón logo" width="200"/>
</p>

# Práctica 1/2: Tecnologías de Servidor/Tecnologías de cliente -

## Equipo TEWx- xx

- [Cristian Augusto](https://github.com/augustocristian) - UO237600@uniovi.es
- [Enol García](https://github.com/enolgargon) - UOXXXX@uniovi.es 


## Contenido

- [Mapa de Navegación](#mapa-de-navegación1)
- [Descripción de las acciones asociadas a las transiciones de pantalla](#descripción-de-las-acciones-asociadas-a-las-transiciones-de-pantalla-2)
- [Decisiones de implementación](#decisiones-de-implementación3)


## Mapa de Navegación[^1]

A continuación se presenta el mapa de navegación de la aplicación:

````mermaid
---
title: Navigation Diagram
---
stateDiagram-v2
    #42; --> error.xhtml: error
    index.xhtml --> AltaForm.xhtml: alta
    AltaForm.xhtml --> listado.xhtml: éxito
    index.xhtml --> listado.xhtml: éxito
    listado.xhtml --> listado.xhtml: éxito
    listado.xhtml --> EditForm.xhtml: editar
    EditForm.xhtml --> listado.xhtml: éxito
````

## Descripción de las acciones asociadas a las transiciones de pantalla [^2]

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum congue eu purus sed mollis. Nunc fermentum
pellentesque nibh, id laoreet massa pharetra ac. Nullam tempus orci id quam venenatis, nec euismod nisl consequat. Morbi
nec ligula rutrum, mollis tellus nec, aliquam dui. Sed et nunc non sapien congue volutpat. Proin pellentesque dictum
felis ut semper. Aenean commodo libero vel interdum porttitor. Nullam sodales ipsum et massa faucibus semper. Quisque
sit amet fringilla ligula, ut sagittis nisl. Maecenas condimentum semper laoreet. Integer ac diam nulla. Pellentesque
habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Fusce ultricies orci dui, vitae
sagittis dolor mollis sit amet. Donec venenatis molestie imperdiet. Duis non blandit sem.

## Decisiones de implementación[^3]

Integer pellentesque sagittis gravida. Nullam vel massa augue. Aliquam in justo sit amet quam lacinia fringilla. Aenean
fermentum nulla id metus scelerisque, vel placerat nisi tempor. Mauris congue neque et porta pellentesque. Quisque
imperdiet ligula et fringilla sagittis. Integer quis enim metus. Maecenas gravida consequat egestas. In sit amet
eleifend mauris, sed bibendum nunc. Interdum et malesuada fames ac ante ipsum primis in faucibus. Curabitur fringilla
tincidunt orci id pretium. Aenean vitae semper mi, ac blandit lectus. Integer dolor diam, feugiat ut ligula nec,
accumsan interdum nisi. Nulla blandit quam id tortor commodo, sit amet porta turpis mattis. Fusce ac dignissim erat,
eget porttitor massa.

[^1]: Mapa de navegación de la aplicación.

[^2]: Descripción textual de cada una de las acciones asociadas a transiciones en el mapa de pantallas

[^3]: Descripción de las decisiones de implementación tomadas en cada una de las funcionalidades.