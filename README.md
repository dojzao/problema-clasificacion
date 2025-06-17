# Problema de Clasificación

### Utilizando una tabla de ejemplo se muestra como resolver un problema de clasificación.

## Contenido del Dataset

### Los datos de ejemplo utilizados contiene estadísticas de partidos de la NBA, incluyendo información sobre el lugar, fecha, equipos involucrados y estadísticas individuales para los equipos local y visitante.

### Diccionario de Datos

| Columna          | Tipo     | Descripción                                                                 |
|------------------|----------|-----------------------------------------------------------------------------|
| `fecha`          | `object` / `datetime64` | Fecha en que se jugó el partido.                                          |
| `lugar`          | `object` | Ciudad o sede donde se disputó el partido.                                  |
| `local`          | `object` | Nombre del equipo local.                                                    |
| `away`           | `object` | Nombre del equipo visitante.                                                |
| `id`             | `object` | Identificador único del partido.                                            |
| `pts`            | `int64`  | Puntuación total del partido (puede ser la suma de ambos equipos o no usada).|
| `MIN.local`      | `int64`  | Minutos totales jugados por el equipo local (sumatoria de sus jugadores).  |
| `FG.local`       | `object` | Tiros de campo del equipo local (formato: anotados/intentos).              |
| `PT3.local`      | `object` | Tiros de 3 puntos del equipo local (formato: anotados/intentos).           |
| `TL.local`       | `object` | Tiros libres del equipo local (formato: anotados/intentos).                |
| `OREB.local`     | `int64`  | Rebotes ofensivos del equipo local.                                        |
| `DREB.local`     | `int64`  | Rebotes defensivos del equipo local.                                       |
| `REB.local`      | `int64`  | Total de rebotes del equipo local.                                         |
| `AST.local`      | `int64`  | Asistencias del equipo local.                                              |
| `STL.local`      | `int64`  | Robos de balón del equipo local.                                           |
| `TOV.local`      | `int64`  | Pérdidas de balón del equipo local.                                        |
| `PF.local`       | `int64`  | Faltas personales cometidas por el equipo local.                           |
| `PM.local`       | `float64`| Puntos +/- del equipo local (puede representar diferencia de puntos).      |
| `PTS.local`      | `int64`  | Puntos totales anotados por el equipo local.                               |
| `MIN.visita`     | `int64`  | Minutos totales jugados por el equipo visitante.                           |
| `FG.visita`      | `object` | Tiros de campo del equipo visitante (formato: anotados/intentos).          |
| `PT3.visita`     | `object` | Tiros de 3 puntos del equipo visitante (formato: anotados/intentos).       |
| `TL.visita`      | `object` | Tiros libres del equipo visitante (formato: anotados/intentos).            |
| `OREB.visita`    | `int64`  | Rebotes ofensivos del equipo visitante.                                    |
| `DREB.visita`    | `int64`  | Rebotes defensivos del equipo visitante.                                   |
| `REB.visita`     | `int64`  | Total de rebotes del equipo visitante.                                     |
| `AST.visita`     | `int64`  | Asistencias del equipo visitante.                                          |
| `STL.visita`     | `int64`  | Robos de balón del equipo visitante.                                       |
| `TOV.visita`     | `int64`  | Pérdidas de balón del equipo visitante.                                    |
| `PF.visita`      | `int64`  | Faltas personales cometidas por el equipo visitante.                       |
| `PM.visita`      | `float64`| Puntos +/- del equipo visitante.                                           |
| `PTS.visita`     | `int64`  | Puntos totales anotados por el equipo visitante.                           |

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- plotly
- Scikit-learn
- Quarto

## Enlace al documento

https://dojzao.github.io/problema-clasificacion/
