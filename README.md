# Python Planet Simulator 
This project is a simple simulation of a planetary system using the Pygame library in Python. The simulation visualizes the orbits of various celestial bodies around a central star, the Sun, and demonstrates gravitational interactions between planets.

To run the simulation, make sure you have Python and Pygame installed on your system. You can install Pygame using pip:
pip install pygame


## Usage

Upon running the script, the simulation window will open, displaying the planetary system. You can observe the orbits of different planets around the Sun. The simulation will continue until you close the window.

## Features

Simulates the orbits of celestial bodies in a planetary system.
Demonstrates gravitational interactions between planets.
Visualization of planet orbits using Pygame graphics.

### How It Works

Initialization: The Pygame library is initialized, and essential constants and variables are defined.
Planet Class: Defines a Planet class representing individual celestial bodies. Each planet has attributes like position, radius, color, mass, velocity, and methods for drawing and updating its position.
Main Function: Sets up the main simulation loop. It creates instances of planets with specific properties like position, mass, and velocity. The simulation loop updates the positions of planets based on gravitational interactions and redraws them on the screen.
Simulation Loop: The simulation runs within a while loop until the user quits the window. Inside the loop, it updates the positions of planets and redraws them on the screen. The loop also handles user events such as quitting the application.
Planetary System: Several planets are instantiated with different properties, orbiting around the Sun. These planets include Earth, Mars, Mercury, Venus, and Jupiter.
Gravitational Interactions: Planets exert gravitational forces on each other, causing them to accelerate and follow curved trajectories.
Drawing: Renders each planet as a colored circle on the Pygame window. The orbit of each planet is also visualized using lines. Text displaying the distance from each planet to the Sun is overlaid on the simulation.

