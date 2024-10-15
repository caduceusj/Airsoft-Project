# Airsoft Projectile Simulation with Magnus Effect

This project simulates Airsoft projectiles in Unity, incorporating physical mechanics such as projectile motion, adjustable **Hop-Up**, and the **Magnus Effect** to model realistic bullet trajectories. The system allows for different weapon types (e.g., **Rifles**, **Pistols**, **Shotguns**) and projectiles, and provides fine control over ballistic behavior.

## Features

- **Weapon Types**: Different weapon types (Rifle, Pistol, Shotgun) with adjustable stats such as fire rate, mass, and spring force.
- **Hop-Up System**: Adjustable Hop-Up using the mouse scroll to control the backspin applied to the projectile.
- **Magnus Effect Simulation**: Physics-based Magnus effect implementation that modifies projectile trajectory based on spin and velocity.
- **Realistic Gravity Control**: Adjustable gravity to simulate projectile drop in different environments.
- **Full-Auto and Semi-Auto Fire Modes**: Switch between full-auto and semi-auto modes with adjustable fire rate per weapon type.

---

## Project Structure

- **Weapon.cs**: Manages the firing mechanics, weapon type, magazine capacity, and bullet instantiation. It also applies the initial velocity based on RPM and adjusts the fire rate.
- **BBController.cs**: Handles projectile physics, including gravity scaling and applying the Magnus Effect to simulate lift and backspin forces.
- **Magazine.cs**: Tracks the current ammunition for the weapon, handling capacity and weight of the BBs.
- **Input System**: Uses the mouse scroll to dynamically adjust the Hop-Up while in-game.

---
