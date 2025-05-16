# Propuesta

## Modelo de Datos

![Modelo de Datos](../../assets/data-model/data-model.jpg)

## Alcance Funcional

### Regularidad:

| Req                     | Detalle                                                                                                                                                                                              |
| :---------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CRUD simple             | 1. CRUD Persona<br>2. CRUD Club<br>3. CRUD Asociación                                                                                                        |
| CRUD dependiente        | 1. CRUD Torneo<br>2. CRUD Participación|
| Listados | 1. Listado de Jugadores con sus respectivos Clubes actuales (permitiendo filtrar por Club) |
| CUU/Epic                | 1. Contrato de Jugadores y Director Técnico por parte de un Club<br>2. Rescisión de Contrato por parte del Jugador o Director Técnico |

### Adicionales para Aprobación

| Req      | Detalle                                                                                                                                                                                                                                             |
| :------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CRUD     | 1. CRUD Persona<br>2. CRUD Club<br>3. CRUD Asociación<br>4. CRUD Torneo<br>5. CRUD Participación<br>6. CRUD Estadio<br>7. CRUD Nacionalidad<br>8. CRUD Tipo de Asociación<br>9. CRUD Posición<br>10. CRUD Usuario<br>11. CRUD Posiciones de Jugadores                                                                                                 |
| Listados | 1. Listado de clubes por los que pasó un jugador en su carrera deportiva (histórico), permitiendo filtrar por un rango de fechas<br>2. Listado de partidos disputados por un club junto a sus resultados, permitiendo filtrar por torneo |
| CUU/Epic | 1. Armado de jornadas de torneos, junto a los partidos que se van a disputar con su fecha y hora, y la posterior asignación de los equipos que se enfrentarán en cada uno de ellos<br>2. Gestión completa de partidos de un torneo, incluyendo registro de resultados, puntos, y actualización automática de estadísticas de participación (partidos ganados, empatados, perdidos, goles a favor y en contra) |
|Niveles de Acceso|1. Administrador<br>2. Presidente<br>3. Jugador<br>4. Director Técnico<br>5. Invitado (sin login)
|Requerimiento Extra | 1. Envío de emails
