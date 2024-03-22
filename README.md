# STDISCM-PROBLEM-SET-2
 
# Particle Simulator: Explorer Mode

## Introduction

This Particle Simulator: Explorer Mode is a graphical application designed to simulate the behavior of particles within a confined space. It uses SFML for rendering graphics and TGUI for the user interface, providing an interactive environment where users can add particles and observe particle dynamics including collisions and reflections. This expansion removes the ability to add walls and but now allows users to enter Explorer mode where users may zoom into the sprite and traverse through the canvas. 

## Requirements

- C++17 compiler
- SFML (Simple and Fast Multimedia Library) 2.5 or newer
- TGUI (Texus' Graphical User Interface) 0.9 or newer

## Installation

To compile and run the Particle Simulator, follow these steps:

1. **Clone the Repository:** Clone this repository to your local machine using `git clone`, or download the source code as a ZIP file and extract it.

2. **Compile the Application:** Navigate to the directory containing the source code and compile the application.

3. **Run the Application:** Once compiled, you can run the application

## Usage

After launching the Particle Simulator: Explorer Mode, you will be presented with a graphical interface that allows you to interact with the simulation:

### Developer Mode: Adding Particles
- The program will initially start in Developer Mode where users may add bouncing particles into the canvas.
- To toggle back to Developer Mode from Explorer Mode, enter the "E" key.
- Individual Particle Addition: Use the input fields to specify properties for individual particles (position, velocity, angle) and click "Add Particle".
- Batch Particle Addition: The application supports adding particles in batches through several forms:
  - Form 1: Specify a start and end position, and the application will distribute particles evenly along the line connecting these points.
  - Form 2: Define an angle range and the application will distribute particles evenly across the specified angular direction from a central point.
  - Form 3: Input a range of velocities, and particles will be added with velocities distributed within this range.

### Explorer Mode: Traversing with the Sprite
- Users may toggle into Explorer Mode by entering the "E" key.
- Once in Explorer Mode, the user is able to traverse through the canvas with the use of the W,A,S,D keys or arrow keys.

### Simulation Control
- Particles move automatically and interact with boundaries. You can only dynamically add particles in Developer Mode.
- Use the checkbox found above to hide/show the input fields.
- An FPS counter will always be displayed on the upper-left corner of the screen.

## Authors
* **Go, Eldrich**
* **Pangan, John Paul**
* **Pinawin, Timothy**
* **Yu, Ethan**
