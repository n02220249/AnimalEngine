# AnimalEngine

A long-running personal exploration of top-down, tile-based world engines and procedural world generation.

## World generation preview

The image below is a generated world preview from the v2.8.25 project archive (seed 12345, world-generation preview v0.25). It illustrates the project's tile-based terrain composition; it is not a screenshot of the full running application.

![AnimalEngine world generation preview](docs/images/worldgen-v0.25-preview.png)

## Overview

AnimalEngine is a C++ top-down tile engine that uses JSON-driven definitions and a world-generation function to create a dynamic tile world.

The project began during my university years. Across multiple iterations and different game engines, I explored different ideas built around a common interest in tile-based worlds and procedural generation. Inspirations included Minecraft's world composition and techniques such as Perlin noise for generating natural variation.

The current version is the latest iteration of that exploration. It brings together a C++ engine, configurable JSON data, and systems for composing and simulating a tile-based world.

## Technical direction

The current iteration explores:

- **Top-down tile-world architecture** — representing the world as a composition of tiles and layers.
- **Procedural world generation** — using a world-generation function to create a dynamic world.
- **JSON-driven definitions** — describing tile types and system data outside the core C++ implementation.
- **Reusable simulation systems** — experimenting with systems for buildings, natural elements, resources, research, and area effects.

These are areas explored by the current codebase; the project is an ongoing experiment rather than a finished commercial game.

## Development history and AI collaboration

I began building tile-based engines independently while studying computer science, and continued revisiting the idea through different technologies and project iterations.

For this latest iteration, I worked with ChatGPT as an AI development partner. I supplied the project direction and accumulated design context, guided the architecture and feature development, reviewed results, and steered the implementation. ChatGPT assisted with code generation, debugging, and technical problem-solving.

I identify this explicitly as an AI-assisted development process: the current implementation was produced collaboratively, building on a project concept I had explored and programmed across earlier iterations.

## Project status

AnimalEngine is a continuing personal software project. This repository is intended to document the current iteration, its technical approach, and its development process.

More documentation, screenshots, and implementation notes can be added as the project is prepared for public presentation.
