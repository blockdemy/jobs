---
description: >-
  Reto de frontend para los aspirantes a pertenecer al equipo de desarrollo de
  Blockdemy
---

# Front end

## Rick and Morty Random Character Generator

### [Demo](https://ernestognw.github.io/rick-and-morty-random/)

![](../.gitbook/assets/assets_-ljdamtha0wqne5cyncw_-ljmcc7einpqsiuyusli_-ljmcfsm4v0jwcq6yzba_ss-1%20%281%29.png)

## Descripción

El reto consiste en crear una aplicación SPA \(Singe Page Application\) con React.js, Apollo GraphQL y Styled Components. El objetivo es hacer el setup del cliente de apollo, y diseñar una aplicación utilizando las herramientas y estándares de Styled Components.

## Objetivo

La aplicación debe traer datos de un personaje al azar utilizando la [API GraphQL de rick and morty](https://rickandmortyapi.com/graphql). El usuario debe ser capaz de generar tantos personajes como desee, y, además, mantener un historial de los personajes que aparecieron previamente, con la posibilidad de ver de nuevo los datos de un personaje que ya ha aparecido.

## Requerimientos funcionales

| Requerimiento | Descripción | Notas |
| :--- | :--- | :--- |
| Botón generador | Cuando el usuario haga click en el botón de la pantalla principal, la aplicación debe llamar al API GraphQL y traer un personaje aleatorio. | El usuario debe ser capaz de generar todos los personajes que desee. |
| Vista de Personaje | Una vez que la aplicación recibe una respuesta con los datos del personaje, debe existir una vista que muestre la información del personaje. | El uso de routing o modales es permitido, y será considerado como puntos extra |
| Historial | Es necesario guardar un historial con el nombre de los personajes que ha generado la aplicación en un menú. | Puntos extras si el menú es implementado como un modal lateral que pueda ser cerrado y abierto con un botón. |

## Requerimientos no funcionales

| Requirement | Description |
| :--- | :--- |
| Setup del cliente de Apollo | La aplicación debe funcionar con la implementación de [Apollo Graphql React](https://www.apollographql.com/docs/react/essentials/get-started/), y preferentemente utilizando el [withApollo HOC](https://www.apollographql.com/docs/react/api/react-apollo/#withapollocomponent) para manejar el acceso al cliente en toda la apl |
| Utilizar Styled Components | Los estilos de la aplicación deben ser completamente desarrollados con [Styled Components](https://www.styled-components.com/),  y habrá puntos extra si se utilizan conceptos de [theming](https://www.styled-components.com/docs/advanced#theming) en la aplicación. [Adaptación basado en props](https://www.styled-components.com/docs/basics#adapting-based-on-props) no es obligatorio, pero será fuertemente considerado para la evaluación. |
| Publicar la SPA en Github Pages | El candidato debe publicar la versión `build` de la aplicación en [Github Pages](https://pages.github.com/), junto con su repositorio contenedor, con el objetivo de ser revisado correctamente. |

## Limitaciones

* Para estilos, sólo está permitido usar Styled Components
* For styling you can only use Styled Components

## Puntos a evaluar

* Arquitectura de archivos
* Componentes en React
* Implementación del Cliente de Apollo GraphQL y su uso
* Styled Components
* Responsividad

