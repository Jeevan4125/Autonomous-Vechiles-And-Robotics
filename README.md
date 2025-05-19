# Autonomous-Vechiles-And-Robotics

This project demonstrates an AI-powered autonomous navigation system combining robotics, sensor fusion, and real-time path planning. The system enables smart robotic vehicles to scan environments, detect obstacles, plan efficient paths, and navigate safely using intelligent decision-making algorithms.

Key Features:-


Autonomous Navigation:Real-time decision-making for autonomous vehicles and robots.

Sensor Fusion: Integration of LIDAR and camera data for enhanced obstacle detection.

Graph-Based Path Planning: Dynamic shortest path calculation using Dijkstra and A* algorithms.

Live Environment Mapping: Graph construction from real-world sensor input.

Safety & Fault Tolerance: Emergency stop mechanisms, fail-safe operations, and sensor redundancy.

Scalability: Modular architecture that supports multi-robot coordination and future upgrades.

Technologies Used
Artificial Intelligence (AI):-


Machine Learning (ML)
Robotics Systems
Sensor Fusion (LIDAR + Camera)
Path Planning Algorithms (Graph-based)
Real-Time Embedded Systems

Tools & Languages:-


Programming Languages: Python

Libraries & Tools:

OpenCV (for vision)

NetworkX / Graph libraries (for path planning)

Matplotlib (for visualization)

Hardware Interfaces (LIDAR, Camera, Motor Controllers)

How It Works:-


Environment Scanning: Robot uses LIDAR and camera sensors to scan surroundings.

Graph Mapping: Sensor data is converted into a graph-based environment.

Path Planning: Dijkstra or A* algorithm computes the shortest route.

Navigation Execution: The system sends motor commands based on planned path.

Real-time Monitoring: Includes obstacle avoidance, performance metrics like latency, and efficiency.

User Interaction: Graphical interface to initiate autonomous runs and monitor path updates.