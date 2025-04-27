# Sistema de Gestión de Torneos de eSports

## Autor

José Ignacio Ribeiro Lucas  
[Perfil de GitHub](https://github.com/Screvas)

## Descripción del Proyecto  
[Link al repositorio del proyecto](https://github.com/Screvas/torneo-esports-uml/)

Este proyecto implementa un sistema de gestión de torneos de eSports
utilizando UML para el modelado y Java para la implementación.

¿Quiénes son los actores que interactúan con el sistema?
- Con el sistema solo interactuará los administradores encargados de gestionar los torneos.

¿Cuáles son las acciones que cada actor puede realizar?  
- Consultar lista de equipos y jugadores.  
**  Todos los jugadores guardados en base de datos.  **  
**  Todos los equipos con sus respectivos jugadores.  **  
- Registrar nuevo equipo.  

-  Añadir jugador a un equipo.  
** Añadir un jugador ya existente en base de datos. **   
** Crear un nuevo jugador y añadirlo al equipo correspondiente.  **  
- Eliminar jugador de un equipo.  

¿Cómo se relacionan entre sí las entidades del sistema?



## Diagramas UML ##  

### Diagrama de Casos de Uso

![Diagrama de casos de uso](diagrams/casos-uso.png)

### Diagrama de Clases

![Diagrama de clases](diagrams/clases.png)

## Estructura del Proyecto

torneo-esports-uml/ ├── src/  
│ ├── es/empresa/torneo/  
│ │ ├── modelo/  
│ │ ├── control/  
│ │ ├── vista/  
│ │ ├── Main.java  
├── diagrams/  
│ ├── casos-uso.png  
│ ├── clases.png  
├── README.md  
├── .gitignore  

## Instalación y Ejecución  

1. Clonar el repositorio:  
`git clone https://github.com/Screvas/torneo-esports-uml.git`  
2. Compilar y ejecutar el proyecto:  
`cd src javac es/empresa/torneo/Main.java java es.empresa.torneo.Main`  

## Justificación del diseño  

Por qué se eligió esa estructura y cómo se organizan las clases.  

## Conclusiones  

Sobre el aprendizaje obtenido.  


