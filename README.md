# motor-control-interface
roboteq and joystick ROS interface

this section handles the interface 
The roboteq_driver interfaces with the roboteq MDC2230 and publishes feedback and status messages from the motor controller. There is a translation node that subscribes to the twist message and publishes the message in the correct format for the roboteq_driver node.

