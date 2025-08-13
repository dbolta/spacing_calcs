# spacing_calcs
Some different implementations for getting distance  between line segments
Implementations in snowflake sql

Child degradation- is simply a summing of segment lengths within a flat end-capped buffer.
No flat buffer was natively available so implemented with python bindings

Draw linestring segments- a simple exmaple of how to draw linestrings from 2 XY endpoints

Create rays- how to get perpendicular distance from a target line segment to a neighboring segment

Draw rays- similar to "draw line segments" but to actually illustrate the rays

Rectangle ex- a method for creating boxes of minimum length to nearby line segment

Draw rectangles for viewer- illustrating the actual rectangle polygon shapes for rendering in a dashboard
