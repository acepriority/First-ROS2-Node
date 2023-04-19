# First-ROS2-Node

This is a Python script for a ROS2 node that demonstrates the use of the rclpy package. It defines a class MyNode that inherits from rclpy.node.Node, and overrides its __init__ and timer_callback methods.
Requirements

This script requires rclpy package to be installed. rclpy is a Python client library for ROS2 that enables Python developers to write ROS2 nodes in Python.
How to use

To run the node, make sure you have sourced your ROS2 installation by running source /opt/ros/$ROS_DISTRO/setup.bash, and then execute the following command:

ros2 run <package_name> <script_name>.py

## Explanation of the code

    The __init__ method initializes the node, sets up the timer, and initializes a counter variable.

    The timer_callback method is called every time the timer fires, increments the counter variable and logs a message that includes the current value of the counter variable.

    The main function initializes the ROS2 system, creates an instance of the MyNode class, starts the main event loop, and finally shuts down the ROS2 system.

## License

This code is licensed under the MIT License. Feel free to use it as you see fit.
