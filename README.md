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
| `wboy.zip` | Wonder Boy | Sega System 1 | 1986 | ~88.3 KB |
| `outrun.zip` | OutRun | Sega · Arcade | 1986 | ~0.8 MB |
| `1943.zip` | 1943: The Battle of Midway | Capcom · Arcade | 1987 | ~0.3 MB |
| `gtmrb.zip` | 1000 Miglia: Great 1000 Miles Rally | Kaneko · Arcade | 1994 | ~0.4 MB |
| `pacnpal.zip` | Pac & Pal | Namco · Arcade | 1983 | ~21.8 KB |
| `25pacmano.zip` | Pac-Man · 25th Anniversary (Rev. 2.00) | Namco / Cosmodog · Arcade | 2005 | ~68.7 KB |
| `tehkanwc.zip` | Tehkan World Cup | Tehkan · Arcade | 1985 | ~0.2 MB |
| `outrunehb.zip` | OutRun Enhanced · 2.0.2 | Sega · Arcade | 1986 | ~0.8 MB |
| `f1gpstr2.zip` | F-1 Grand Prix Star II | Jaleco · Arcade | 1993 | ~3.9 MB |
| `footchmp.zip` | Football Champ / Euro Football Champ (World) | Taito F2 · Arcade | 1990 | ~1.9 MB |
| `flipjack.zip` | Flipper Jack | Jackson · Arcade | 1983 | ~30.1 KB |
| `hangon.zip` | Hang-On (Rev A) | Sega · Arcade | 1985 | ~0.4 MB |
| `galspnbl.zip` | Gals Pinball | Comad · Arcade | 1996 | ~3.3 MB |
| `sf2ce.zip` | Street Fighter II · Champion Edition | Capcom CPS1 · Arcade | 1992 | ~3.4 MB |
| `term2.zip` | Terminator 2 · Judgment Day (LA4) | Midway Y Unit · Arcade | 1991 | ~9.5 MB |

## Estructura de Catálogo

- `manifest.json`: Índice maestro que consume la aplicación Moai. Contiene la metadata de todos los juegos disponibles (nombre, descripción, peso en bytes, sistema y enlace relativo).
- `<juego>.json`: Ficha individual de metadata para cada juego.

## Enlace Raw de Producción

Una vez subido a GitHub (ej: `https://github.com/dariomadeira/moai_roms`), el archivo de catálogo se consume en:

```
https://raw.githubusercontent.com/dariomadeira/moai_roms/main/manifest.json
```
