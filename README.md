Hi I'm Max :D

I am currently a Mechatronics Engineering student at the University of Waterloo, focused on robotics, reinforcement learning, and simulation. 

Most of my recent work entails NVIDIA Isaac Sim / Isaac Lab, with ROS2 for communication and RL & PID for control.

Featured Projects:

1. Custom Quadruped Locomotion — Unitree Go2 PPO

I trained a Unitree Go2 quadruped with PPO using a custom ManagerBased RL environment in Isaac Lab. To achieve stable locomotion, I focused heavily on tuning rewards, penalties and regularization terms. For example, I created a custom height reward function to eliminate crawling gaits, used curriculum learning to gate foot-lifting rewards after the robot learned to balance to aid training progress, and much more. I also focused on regularization terms, applying a squared penalty on penalties like action_rate to smooth joint movement while also preventing model overfitting. 

In the future, I plan on developing more advanced policies like getup policies, sim-to-real and physical intelligence 

2. Autonomous Maze Navigation — Nova Carter

Built a full ROS2 Nav2 stack on a Nova Carter robot in Isaac Sim: SLAM mapping, AMCL localization, and Nav2 path planning. Constructed the entire TF tree from scratch and debugged a warped SLAM map down to a LiDAR/odometry publish-rate mismatch. ROS2, Nav2, SLAM, Isaac Sim

RICO — Voice-Controlled Robotic Arm (Eureka Hacks)

A 4-DOF arm that retrieves tools from natural-language voice commands, using a Groq LLM to parse speech into arm actions, inverse kinematics for motion, and a fine-tuned YOLOv8 model with a homography transform for tool localization. Inverse Kinematics, OpenCV, YOLOv8, LLM

FIRST Tech Challenge #18844 — Co-Captain & Lead Programmer

2025 FIRST World Championships, 1st Connect Award (Ochoa Division). Built a Point-to-Point PID movement system, 2-wheel odometry with IMU localization, and an automated pickup system using a custom-trained CNN. PID control, Odometry, Computer Vision

Tools & Technologies

Languages: Python, Java Robotics & Sim: Isaac Sim, Isaac Lab, ROS2, Rviz, Onshape ML / CV: PyTorch, rsl_rl, OpenCV, YOLOv8 Focus areas: Reinforcement Learning, PID control, Inverse Kinematics, Odometry
