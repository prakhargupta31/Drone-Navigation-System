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

├── drone_navigation.py          # Main integration script
├── drone_movement.py            # Handles movement controls
├── drone_obstacle_detection.py  # Processes LiDAR sensor data
├── battery_simulation.py        # Simulates battery usage
├── data_logging.py              # Logs navigation and system data
├── config.py                    # Configuration settings
├── README.md                    # Project documentation
