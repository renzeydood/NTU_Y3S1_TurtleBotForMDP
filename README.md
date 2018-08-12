# TurtleBotForMDP

Experimental codes for TurtleBot3

Notes:

    -turtlebot3_mazerun:
        *A simple package to apply the subscriber-publisher model to automate the turtlebot

    -turtlebot3_core:
        *Modification of the original turtlebot3_core provided, but added in the IR Sensors functionality

Installation:

    -turtlebot3_mazerun [ROS Remote Computer]:
        -In your Ubuntu system, place folder in <b>home > catkin_ws > src</b>
        -In Terminal, go to catkin_ws dir and execute [<b>catkin_make</b>]
        -To run, make sure roscore is active, then execute [<b>rosrun turtlebot3_mazerun mainTurtlebot.py</b>]

    -turtlebot3_core [Arduino]:
        -First, install the SharpIR library in to the Arduino Library folder
        -Then open Arduino IDE and upload turtlebot3_core.ino to the OpenCR
