# Simulation Gemini 2.5

A beautiful and interactive particle simulation that demonstrates gravitational effects around a controllable singularity. This project creates a mesmerizing visualization of particles orbiting and interacting with a central gravitational point.

## Features

- Interactive particle system with realistic gravitational physics
- Adjustable parameters:
  - Number of particles
  - Gravitational force
  - Initial tangential velocity
  - Damping factor
  - Absorption radius
- Beautiful visual effects:
  - Particle trails
  - Absorption flashes
  - Dynamic color gradients
  - Smooth particle motion

## Live Demo

You can view the live simulation by opening `index.html` in a modern web browser.

## Technical Details

The simulation uses:
- HTML5 Canvas for rendering
- JavaScript for physics calculations
- CSS for styling and layout

The physics model is based on a simplified version of universal gravitation (F ~ 1/r²) with:
- Softening constant to prevent infinite forces
- Damping factor for energy loss
- Collision detection with boundaries
- Particle absorption mechanics

## Controls

- **Number of Particles**: Adjust the total number of particles in the simulation (50-500)
- **Attraction Force**: Modify the strength of the gravitational pull (500-20000)
- **Initial Tangential Speed**: Set the starting orbital velocity (0.1-3.0)
- **Damping Factor**: Control energy loss in the system (0.900-0.999)
- **Absorption Radius**: Define the size of the central singularity (2-20)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to fork this repository and submit pull requests for any improvements or bug fixes.

## Author

Created by Dean988 