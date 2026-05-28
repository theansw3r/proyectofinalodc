# Organización de Computadores - Proyecto Final MAZEMAN

Este repositorio contiene la implementación del proyecto final **MAZEMAN**, un videojuego desarrollado en lenguaje **Jack** sobre la plataforma **Hack / Nand2Tetris**, inspirado en la lógica arcade de Pac-Man y adaptado a los requerimientos del curso.

El proyecto integra diseño de mapa en grid, control de estados, renderizado gráfico, movimiento del jugador, lógica de persecución del enemigo, spawn variable y manejo optimizado de memoria.

**Institución:** Universidad EAFIT  
**Asignatura:** Organización de Computadores  
**Periodo:** 2026-1

---

## Integrantes del Equipo

| Nombre | Rol Principal |
|--------|---------------|
| Pedro Santiago Mafla Jaramillo | Desarrollo y apoyo en lógica del proyecto |
| Lucas Saldarriaga Quintero | Diseño e implementación principal del videojuego en Jack |

---

## Estructura del Repositorio

El proyecto está organizado en archivos fuente en **Jack**, cada uno con una responsabilidad específica dentro de la arquitectura del juego:

```text
MAZEMAN/
├── Main.jack
├── MazeGame.jack
├── MazeMap.jack
├── Player.jack
├── Enemy.jack
├── AIHelper.jack
├── Random.jack
├── README.md
├── CHANGELOG.md
├── CONTRIBUTORS.md
└── LICENSE
