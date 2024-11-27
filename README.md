# cub3D

## My First RayCaster with miniLibX

### Summary
**cub3D** is a project inspired by the classic *Wolfenstein 3D* game, one of the first FPS games in history. The goal of this project is to create a simple ray-casting engine to render a dynamic 3D view from a first-person perspective inside a maze.

### Introduction
**cub3D** involves creating a 3D graphical representation of a maze using ray-casting techniques. The project aims to develop skills in window management, texture rendering, event handling, and the use of the **miniLibX** graphics library to create an interactive graphical application.

### Installation
1. Clone the repository:
   ```
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```
   cd cub3D
   ```
3. Compile the project:
   ```
   make
   ```

### Usage
Run the program with:
```
./cub3D <map_file.cub>
```
Replace `<map_file.cub>` with the path to your map file.

### Features
- **Ray-Casting Engine**: Create a first-person view to explore a maze using ray-casting techniques.
- **Textures and Colors**:
  - Different wall textures depending on their facing direction (North, South, East, West).
  - Customizable floor and ceiling colors.
- **User Controls**:
  - **W, A, S, D** keys to move around the maze.
  - **Left and Right Arrow** keys to rotate the view.
  - **ESC** key to exit the game.
- **Map Format**: The map file must have a `.cub` extension and describe the layout using characters (`0` for empty space, `1` for wall, `N, S, E, W` for player start and orientation).

