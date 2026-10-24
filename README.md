# Abelian Sandpile Model Toppling Simulation

Click anywhere on the canvas to drop grains of sand. When a cell accumulates 4 or more grains it topples, distributing one grain to each of its four neighbors, which can trigger chain reactions. As millions of grains accumulate, beautiful fractal-like patterns emerge through self-organized criticality.

## Features

- 125×125 grid rendered via raw ImageData for maximum performance
- Click anywhere to drop a configurable number of grains (100–50,000)
- Speed slider controls steps per animation frame (1–500)
- Color-coded grain counts: black=0, blue=1, green=2, yellow=3, red=toppling
- Continuous-drop mode that automatically adds grains to the center every few frames
