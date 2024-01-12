# 🏝️Paradi
A simple engineering diagram description language that compiles to SVG.

## Motivation
It's quite time consuming to draw engineering diagrams that are to scale and accurate. Paradi aims to fix this by providing a simple way to draw or programatically generate diagrams that can then be directly embedded into documents in Scalable Vector Graphics (SVG) format.

## Example

## Commands

### Line
`l (x1,y1)-(x2,y2) line-width colour`

Generates a line with end coordinates `(x1,y1)` and `(x2,y2)` with width `line-width` and colour `colour`.

### Rectangle
`r (x,y) width height line-width line-colour fill-colour`

Generates a rectangle with top left coordinate `(x,y)`.

## Reference

### Line widths
`line-width` parameter can be any decimal number.

### Colour
`colour` has the following accepted colours:

- `black`
- `red`
- `green`
- `blue`
- `cyan`
- `magenta`
- `yellow`
