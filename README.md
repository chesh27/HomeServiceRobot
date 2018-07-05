# Home-Service-Robots
Welcome to the Home Service Robot project! For this project, your goal is to program a home service robot that will autonomously map an environment and navigate to pickup and deliver objects.

Let’s summarize what should be done in this project to simulate a home service robot

Design a simple environment with the Building Editor in Gazebo.
Teleoperate your robot and manually test SLAM.
Create a wall_follower node that autonomously drives your robot to map your environment.
Use the ROS navigation stack and manually commands your robot using the 2D Nav Goal arrow in rviz to move to 2 different desired positions and orientations.
Write a pick_objects node that commands your robot to move to the desired pickup and drop off zones.
Write an add_markers node that subscribes to your robot odometry, keeps track of your robot pose, and publishes markers to rviz.
