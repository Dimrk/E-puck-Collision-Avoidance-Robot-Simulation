# E-puck Collision Avoidance Robot Simulation

This project demonstrates a collision avoidance behavior using the E-puck robot in a Webots simulation environment. The robot uses proximity sensors and reactive control to navigate around obstacles in a structured space.

## 🎯 Project Objectives
- Implement real-time obstacle avoidance using E-puck.
- Simulate autonomous navigation in a 2D arena.
- Demonstrate basic robotic behaviors using Webots.

## 🛠️ Technologies Used
- [Webots R2025a](https://cyberbotics.com)
- E-puck robot model
- Custom C controller (`epuck_avoid_collision`)
- Sensor-based motion logic

## 📦 Files Included
- `collision_avoidance.wbt`: Webots simulation world
- `epuck_avoid_collision.c`: Main robot controller
- `collision_avoidance.mp4`: Demo video
- `README.md`: Project overview

## 📹 Project Demo
Watch a short video demonstration of the robot navigating the arena:
➡️ [YouTube Demo](https://youtu.be/-4nRHELobM8) 

## 📚 How to Run
1. Open Webots R2025a or later.
2. Load the `collision_avoidance.wbt` world file.
3. Ensure `epuck_avoid_collision` is assigned as the robot controller.
4. Press **Run** and observe obstacle avoidance behavior.

## 🧠 Algorithm Overview
- The robot continuously reads data from its infrared sensors.
- If obstacles are detected in front or to the side, wheel speeds are adjusted to turn.
- A simple state machine decides turning direction based on sensor patterns.

## 📬 Contact
Have questions or feedback?  
📧 mangalsanark1@gmail.com

