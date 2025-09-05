# Propuesta TP DSW

## Grupo
### Integrantes
* Leg 53084 - Moretti Yrure, Pedro
* Leg 52222 - Bernard, Bruno

### Repositorios
* [frontend app](https://github.com/bernardbruno/front-tp-dsw)
* [backend app](https://github.com/bernardbruno/back-tp-dsw)

## Tema
### Descripción
El Sistema es una plataforma de predicciónes de Fórmula 1, en donde cada usuario ingresa sus predicciones y compite con otros para intentar adivinar la mayor cantidad de resultados antes de que se corran las carreras. 


### Modelo
![DCD](https://github.com/user-attachments/assets/1ba79ca9-c4af-4888-a9da-b904194bda43)





## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Escuderia <br>2. CRUD Circuito|
|CRUD dependiente|1. CRUD Piloto {depende de} CRUD Escuderia <br>|
|Listado<br>+<br>detalle| 1. Listado de Pilotos => detalle CRUD Piloto y CRUD Escuderia<br>2. Listado Carreras próximas => detalle Carrera |
|CUU/Epic|1. Gestionar la carrera (definir carrera y cargar escudería-piloto y circuito) |


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD | - |
|Listado<br>+<br>detalle| 1. Listado de Usuarios con mejores Predicciones => detalle Usuario |
|CUU/Epic|1. Gestionar Torneo (definir un torneo con sus carreras y sus participantes)<br>2.  Registrar predicciones y resultados de una carrera|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|| |
|CUU/Epic|1. Ingresar los resultados automáticamente mediante una API <br>2.  Crear Torneo privado <br>3. Realizar un post|
|Otros| - |
