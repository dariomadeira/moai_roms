# Moai Arcade ROMs Repository

Repositorio oficial de ROMs arcade para el módulo **Arcade** de **Moai TV**.

## Contenido del Repositorio

| Archivo | Juego | Sistema | Año | Tamaño |
|---|---|---|---|---|
| `mvsc.zip` | Marvel vs. Capcom: Clash of Super Heroes | CPS-2 | 1998 | ~21.6 MB |
| `sfiii3.zip` | Street Fighter III: 3rd Strike | CPS-3 | 1999 | ~67.3 MB |
| `mshvsf.zip` | Marvel Super Heroes Vs. Street Fighter | CPS-2 | 1997 | ~22.1 MB |
| `ffight.zip` | Final Fight | CPS-1 | 1989 | ~1.4 MB |
| `robocop2.zip` | RoboCop 2 | Data East | 1991 | ~2.6 MB |
| `wboy.zip` | Wonder Boy | Sega System 1 | 1986 | ~0.1 MB |

## Estructura de Catálogo

- `manifest.json`: Índice maestro que consume la aplicación Moai. Contiene la metadata de todos los juegos disponibles (nombre, descripción, peso en bytes, sistema y enlace relativo).
- `<juego>.json`: Ficha individual de metadata para cada juego.

## Enlace Raw de Producción

Una vez subido a GitHub (ej: `https://github.com/dariomadeira/moai_roms`), el archivo de catálogo se consume en:

```
https://raw.githubusercontent.com/dariomadeira/moai_roms/main/manifest.json
```
