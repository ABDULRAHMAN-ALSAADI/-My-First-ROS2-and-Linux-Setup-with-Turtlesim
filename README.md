# 🐧🚀 My First ROS2 + Linux Setup with Turtlesim

This is the first step in my journey learning Linux and ROS2 (Robot Operating System 2) using a virtual machine. I installed everything from scratch and ran the classic Turtlesim demo 🐢 to start exploring robot control.

## 📦 What I Used:

- 💻 Ubuntu 22.04 inside VirtualBox

- 🤖 ROS2 Humble

- 🐢 Turtlesim package (to simulate a moving turtle robot)

## ⚙️ Setup Steps:

1. Installed ROS2

Followed the official ROS2 install guide for Humble:

```bash
sudo apt update
sudo apt install curl gnupg2 lsb-release
```

→ Added keys, setup repo, then:

```bash
sudo apt install ros-humble-desktop
```

2. Sourced ROS2 (So it works in every terminal)

```bash
echo "source /opt/ros/humble/setup.bash" >> ~/.bashrc
source ~/.bashrc
```

3. Installed Turtlesim 🐢

```bash
sudo apt install ros-humble-turtlesim
```

4. Ran the Simulation

In Terminal 1:

```bash
ros2 run turtlesim turtlesim_node
```

In Terminal 2:

```bash
ros2 run turtlesim turtle_teleop_key
```

And this will make me control the turtle using my keyboard arrows!

## 🧠 What I Learned:

- How to install and source ROS2 correctly

- How to manage multiple terminals in ROS2

- How to run and control simulation nodes

- How to debug .bashrc errors 

- That focus on the terminal matters for key input!

## ✨ Why This Matters:

This is the foundation for everything I'll build next — robots, AMRs, Robotic Arms, AI-controlled systems — it all begins here 🚀.

