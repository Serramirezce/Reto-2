# Reto-2
Repositorio para el Reto 2 del curso de Programación Orientada a Objetos.

```mermaid
classDiagram
    Pieza <|-- Torre
    Pieza <|-- Alfil
    Pieza <|-- Rey
    Pieza <|-- Caballo
    Pieza <|-- Peón
    Pieza <|-- Reina
    class Pieza{
      +JuegoAjedrez juego_ajedrez
      +color
    }
    class Torre{
      +forma
      +mover(tablero)
    }
    class Alfil{
      +forma
      +mover(tablero)
    }
    class Rey{
      +forma
      +mover(tablero)
    }
    class Caballo{
      +forma
      +mover(tablero)
    }
    class Peon{
      +forma
      +mover(tablero)
    }
    class Reina{
      +forma
      +mover(tablero)
    }
```
