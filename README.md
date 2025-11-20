📦 Autonomous-Delivery-Drone 
 ┣ 📁 Project Documentation
 │ ┣ Project Introduction.pdf
 │ ┣ Project Methodology.pdf
 │ ┣ Hardware and Software Components.pdf
 │ ┣ Result.pdf
 │
 ┣ 📁 Source Code
 │ ┣ delivery_mission.py
 │ ┣ AI_ML Algorithm
 │
 ┣ 📁 Images
 │
 ┣ README.md
 ┣ LICENSE
 ┗ .gitignore
 
⸻

AUTONOMOUS AI/ML - BASED DELIVERY DRONE (Hexacopter) 
A contactless delivery system developed during the COVID-19 pandemic

🚑 Project Background & Motivation: 
During the COVID-19 pandemic, physical contact became a major risk due to the highly spreadable nature of the virus. Essential items—medicine, groceries, small parcels—were difficult to deliver safely without exposing individuals to infection. This project was developed as a contactless delivery solution, using drones to transport packages autonomously and reduce human involvement. The drone’s automated navigation, waypoint planning, and robotic arm delivery mechanism aimed to minimize face-to-face interactions during emergencies.

⸻

🚀 Project Overview: 
The system uses a combination of Artificial Intelligence (AI) and Machine Learning (ML) concepts to enable autonomous drone navigation, parcel delivery, and return-to-home operations. 
Key Capabilities
• Fully autonomous flight using Pixhawk flight controller 
• Waypoint-based GPS Navigation 
• Real-time telemetry via ground control station (Mission Planner)
• Robotic arm mechanism for contactless parcel release
• Fail-safe and return-to-launch (RTL) functionality 
• Battery & charging management strategies inspired by modern delivery drone systems

⸻

🎯 Objectives: 
• Develop a pilotless autonomous UAV capable of parcel delivery 
• Reduce human effort, time, and fuel consumption 
• Enable safe, contactless delivery during critical situations 
• Incorporate charging/replacement stations for extended operation

⸻

🧠 System Architecture: 
Hardware Components-
• Pixhawk Flight Controller (PX4/ArduPilot ecosystem)
• GPS with Compass (SAM-M8Q + QMC5883L) • 433MHz Telemetry Module for real-time mission tracking 
• Brushless DC Motors + ESCs 
• Hexacopter Frame (DJI F450-based 450mm frame) 
• Robotic Arm for autonomous package drop 
• LiPo Battery with protection systems

Software Components-
• Mission Planner for configuration & flight operations 
• Autonomous mission planning via GPS waypoints 
• Firmware flashing & tuning via ArduPilot stack

⸻

🛠️ Working Principle (Simplified):
• User inputs a delivery location in the mission planner/mobile app
• Drone sets home location automatically
• Drone verifies package is loaded
• Autonomous take-off → navigates via GPS waypoints
• Lands at target location
• User accepts package → robotic arm releases parcel
• Drone auto-returns to home
Note: In case of signal loss, enters Return-to-Launch fail-safe mode
⸻

🌍 Real-World Relevance: 
Similar drone delivery systems are used globally by:
• Amazon Prime Air 
• Google Wing • UPS Flight Forward 
• DHL Parcelcopter Our project was inspired by these advancements, especially during times when safe delivery mechanisms were essential for public health.

⸻

💡 Future Improvements: 
• Adding computer vision for obstacle detection 
• Integrating ML-based route optimization 
• Improved battery prediction models 
• End-to-end mobile application for delivery requests

⸻

📜 License: MIT License





