# Drone Navigation System
The Drone Navigation System is a Python-based project designed for autonomous drone movement with real-time obstacle avoidance, path planning, battery simulation, and data logging. It integrates multiple processes to ensure efficient and safe navigation using LiDAR sensors and a Raspberry Pi 4B.

#Features
- Autonomous Drone Movement: Implements precise motion control for navigation.
- Obstacle Avoidance: Utilizes LiDAR sensor data to detect and avoid obstacles.
- Path Planning (A* Algorithm): Finds the most optimal path in complex environments.
- Battery Simulation: Models power consumption and optimizes energy usage.
- Data Logging: Captures flight data, including position, battery status, and obstacle encounters.

## Technologies Used
- Python: Core programming language for the project.
- Raspberry Pi 4B: Onboard computation and sensor integration.
- LiDAR Sensor: Real-time obstacle detection.
- A* Algorithm: Efficient path planning.
- Matplotlib & Pandas: Data visualization and analysis.
- PyCharm: Development and simulation environment.

# Project Structure

├── Astar_algorithm.py           # Implements A* path planning
├── batterysimulation.py         # Simulates battery usage
├── data_logging.py              # Logs navigation and system data
├── drone_movement.py            # Handles movement controls
├── drone_obstacle.py            # Processes LiDAR sensor data
├── dynamicobstacle.py           # Handles moving obstacle detection
├── wind.py                      # Simulates wind effects on navigation
├── integration.py               # Integrates drone_obstacle and drone_movement
├── final.py                     # Final execution script
├── config.py                    # Configuration settings
├── README.md                    # Project documentation
