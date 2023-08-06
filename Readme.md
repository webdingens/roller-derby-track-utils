# Roller Derby Track Utils

Compute skater states, pack definition, pack shapes and engagement zone shapes. Used in [Track-Viz](https://github.com/webdingens/track-viz) project.

## Frame of reference

The computed track is centered at `(0, 0)`. The coordinate system follows the SVG or screen coordinate system with x value from left to right and y values from top to bottom.

## Units

This package is using the metric system.

## Peer Dependencies

Uses lodash and three.js. Tested with three.js `^0.115.0` and with lodash `^4.17.15`. Will probably run on different versions as well. Three.js is used everywhere because of Vector2 for vector computations.

## Examples

2D and 3D rendering examples can be found in the `examples` folder.
