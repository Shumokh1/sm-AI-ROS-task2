# sm-AI-ROS-task2

## Overview
Task2: Use ROS Development Studio to set up a simulation environment.
## Steps to set up a simulation environment

1. **Open The Construct**

   Go to [The Construct](https://app.theconstruct.ai) and create an account.

2. **Fork the Project**
   - Navigate to **Public ROSjects**.
   - Search for **"ROS Basic Real Robot Project"**.
   - Fork the project to your account.

4. **Run the ROSject**
   - Go to **My ROSjects**.
   - Open and run the forked ROSject.
<img width="1200" alt="Screen Shot 1446-01-14 at 11 14 26 
<img width="972" alt="Screen Shot 1446-01-18 at 9 20 56 PM" src="https://github.com/user-attachments/assets/dad6e2ae-3b49-4515-93f6-fa84446da869">
AM" src="https://github.com/user-attachments/assets/55b97c77-f353-4f85-beeb-1850703b6a10">
5. **Open Gazebo and Shell**

   - Open Gazebo for simulation.
   - Open the terminal (shell) within the ROSject environment.

6. **Execute Commands**

   Type the following commands to launch the simulation and run your Python code:

   ```bash
   roslaunch realrobotlab main.launch
   roslaunch lidardata lidardata.launch
