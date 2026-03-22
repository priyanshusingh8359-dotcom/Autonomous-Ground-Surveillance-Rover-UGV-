# Autonomous-Ground-Surveillance-Rover-UGV-
Project Overview
This project presents a modular autonomous ground surveillance rover (UGV) designed for perimeter monitoring, reconnaissance, and target tracking applications. The system integrates vision-based detection, a dual-axis stabilized gimbal, and a rugged all-terrain mobility platform to support continuous surveillance in diverse environments.
The platform is designed with defence-grade modularity, allowing rapid adaptation for multiple mission profiles including border surveillance, forward area monitoring, and mobile observation posts.


Operational Capabilities
Vision-based human/animal/object detection
Pan–tilt gimbal for stabilized visual tracking
All-terrain six-wheel UGV mobility
Remote operation via secure wireless link
Non-lethal acoustic deterrent / alert system
Modular payload architecture for mission customization


System Architecture
The system employs a distributed control architecture:
High-level processing: Vision & decision logic
Low-level control: Real-time actuation and safety monitoring
Communication layer: Dual-channel wireless control
Mechanical layer: Ruggedized chassis and stabilized sensor mount


Mechanical Design (UGV Platform)
Chassis: Laser-cut lattice structure (high strength-to-weight)
Mobility: Six-wheel configuration with front suspension
Payload capacity: 2 kg
Gimbal accuracy: ±1.5°
Manufacturing: Indigenous materials + additive manufacturing
Designed for field deployment, rapid repair, and low logistics footprint.

Electronics & Control
Controller: Arduino-based real-time controller
Camera: ESP32-CAM vision module
Actuators: High-torque DC motors & metal-gear servos
Power: 11.1V Li-ion battery with multi-rail distribution
Communications: Bluetooth / Wi-Fi (expandable to RF/mesh)


Testing & Performance
Target detection accuracy: >85%
Max ground speed: 2.8 m/s
Surveillance range: ~60 m
Operating time: ~2 hours
Gimbal stabilization error: <2°


Defence Applications
Border & perimeter surveillance
Forward area reconnaissance
Restricted zone monitoring
Mobile observation platform
Training & simulation systems
ISR (Intelligence, Surveillance, Reconnaissance) research


Future Enhancements
Encrypted RF communication
Thermal & IR camera integration
GPS-assisted autonomous navigation
Multi-UGV coordinated patrol
AI-based threat classification


Repository Structure
/mechanical_design     → CAD & STL files
/electronics           → Power & control diagrams
/firmware              → Embedded control code
/vision_system         → Detection & tracking algorithms
/documentation         → Technical reports & diagrams
/images                → Renders & test images


License
Released under MIT License for research and academic evaluation.

Author
Priyanshu Singh Mechanical Engineering | Robotics | Autonomous Systems | Gmail Id: priyanshusingh8359@gmail.com
