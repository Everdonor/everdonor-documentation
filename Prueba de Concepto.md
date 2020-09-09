# Prueba de Concepto

## Funcionalidades

Como prueba de concepto decidimos crear una aplicacion en donde se visualice una pantalla de bienvenida en donde el usuario pueda tener un pantallazo inicial de las funcionalidades de la aplicación. El foco lo ponemos en el mapa, donde vamos a poder ver los centros cercanos a la ubicación del usuario. También se podran buscar centros especificos por nombre o filtrar por tipo de donación. Al hacer click en el marcador de alguno de los centros, podemos ver más información sobre el mismo, incluyendo una imagen representativa del centro.

Para eso tomamos como caso de uso a una persona donante, la cual puede ver centros y su información en un mapa y ver la lista de los centros registrados

Siguiendo la arquitectura planteada en la página principal del repositorio, el frontend se comunica con el servidor backend que contiene la información de los centros.

## Capa de presentación en prueba de concepto

<p align="center">
  <img src="fotoApp.png" />
</p>

## Casos de uso

<p align="center">
  <img src="Casos de uso donante.png" />
</p>

El usuario con rol de donante ingresa al mapa y visualiza los marcadores en las ubicaciones de los centros registrados.

El usuario con rol de donante puede ver una lista de los centros registrados.