Koch Snowflake

The Koch Snowflake is a fractal constructed recursively. Starting from an equilateral triangle, each line segment is subdivided into smaller segments, forming increasingly intricate patterns at every step.

Recursive Process:

Each line segment is divided into three equal parts. The middle segment is replaced with two sides of an equilateral triangle pointing outward, forming four smaller segments.
Recursion stops after a set number of iterations, leaving segments undivided and drawn as-is.

Using translate and rotate:
Translation moves the starting point of each segment to its proper position.
Rotation adjusts the orientation of segments for creating peaks, such as ±60° for triangular edges.
Implementation:

Start with an equilateral triangle.
Recursively replace segments following the pattern.
Use a graphics library to draw the shape step by step.
