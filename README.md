Autonomous Robot Navigation in a Simulated T-Maze
This repository contains two subprojects developed as part of a Robotics course: Behavior-Based Robotics (BBR) and Evolutionary Robotics (ER). Both projects aim to enable autonomous navigation of an E-Puck robot in a simulated T-maze environment using different robotics paradigms.

🧠 Project Overview
Simulator: Webots

Robot: E-Puck

Language: Python

Paradigms: Behavior-Based Robotics (BBR) & Evolutionary Robotics (ER)

Core Techniques: Modular controllers, Neural Networks, Genetic Algorithms

📁 Repository Structure
📂 BBR - Code/
Behavior-Based Robotics implementation

controllers/NEW_bbr/NEW_bbr.py: Reactive controller using subsumption architecture for modular behaviors like wall-following and turning.

controllers/Supervisor_BBR/Supervisor_BBR.py: Supervisor to monitor and evaluate robot performance across trials.

worlds/: Webots world files and resources for T-maze simulation.

README.md: Specific notes for running BBR setup (included in the folder).

Hidden files like .DS_Store and .wbproj are auto-generated and can be ignored.

📂 ER - Code/
Evolutionary Robotics implementation

controllers/epuck_python - ER/epuck_python - ER.py: Main controller with an evolved neural network for adaptive navigation.

controllers/epuck_python - ER/mlp.py: Defines the Multi-Layer Perceptron (MLP) architecture used as the controller.

__pycache__/: Python bytecode cache (not needed for execution).

README.md: Notes specific to the ER implementation.

Hidden files and metadata can be safely ignored.

🚀 Performance Highlights
BBR: Manually tuned reactive behaviors using modular design principles.

ER: Achieved 2× faster maze completion by evolving neural network controllers with multi-objective fitness functions.

Result: ER approach outperformed BBR in both adaptability and efficiency.

🛠️ How to Run
Requires: Webots installed with Python controller support.

Open Webots and load the appropriate project from the worlds/ directory.

Set the corresponding controller for the E-Puck robot in the simulation.

Run the simulation and monitor the robot’s navigation performance.

For ER: Use the MLP code with genetic evolution if rerunning training.

