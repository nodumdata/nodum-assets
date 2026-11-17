# Logos de Nodum

El logo es un nudo trébol (*nodum*, en latín). La bolita lima es el algoritmo, que recorre el nudo; el punto del centro es el dato, que no se mueve.

Todos los ficheros son SVG con fondo transparente. La palabra «nodum» va en trazos (Plus Jakarta Sans 800), así que no hace falta tener la fuente instalada.

| Fichero | Qué es | Fondo |
|---|---|---|
| `nodum-logo.svg` | Logo principal con la palabra «nodum.» | Claro |
| `nodum-logo-dark.svg` | Logo principal con la palabra «nodum.» | Oscuro |
| `nodum-icon.svg` | Solo el nudo, con la bolita y el dato | Claro, desde 32 px |
| `nodum-icon-dark.svg` | Solo el nudo, con la bolita y el dato | Oscuro, desde 32 px |
| `nodum-icon-small.svg` | Nudo de trazo grueso, sin el dato | Claro, por debajo de 32 px (favicon, avatar) |
| `nodum-icon-small-dark.svg` | Nudo de trazo grueso, sin el dato | Oscuro, por debajo de 32 px |

## Uso

- Elige el fichero según el fondo: un SVG cargado con `<img>` no hereda el color del texto.
- Deja alrededor un margen libre igual a la altura de la bolita.
- No cambies los colores, no separes la bolita del nudo y no añadas sombras ni degradados.

## Colores

| Uso | Oscuro | Claro |
|---|---|---|
| Trazo y dato | `#f4f5f7` | `#141619` |
| Bolita y punto | `#d8f255` | `#d8f255` con aro `#97b312` |
