# Introduction

This is a package to define the message types which are used by ROS topics for communications between controller and robots.

It has two main message types: AmbotAction and AmbotState for loading actions from controller and states from robot.

The controller publishs a topic which send AmbotAction message subscribed by robot node, while the robot node publishs a topic which send AmbotState message subscirbed by controller node.

