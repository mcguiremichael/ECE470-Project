# ECE470-Project

  The motivation behind my project idea is automated filtering of trash for recyclables. What if we could have robots that detect things like plastic bottles and aluminum cans in a conveyor belt of garbage and can sort them out to be recycled? The goal of this project is to simulate a robot that can detect and pick up certain types of objects off of a moving conveyor belt.

  These are my goals for setup and implementation.
Implement a 6-jointed robot that can pick up objects of a few discrete varying shapes and sizes and move them to certain bins, with an input that gives the robot the location and orientation of the essential objects. A scripted algorithm will be used to orient all but the appendage joint and do the grabbing.
Use computer vision model to distinguish desired objects from background
Detect orientation of said desired objects
Use reinforcement learning to decide the angle of the appendage joint for grabbing
Track statistics of successful desired object placement

  The following are stretch goals to further improve the 
Vary conveyor belt speed; do not explicitly give robot the speed value
Continuously vary the sizes of the desired objects
Adjust the lighting and colors to stress test the vision algorithm
Alter coefficient of friction and mass of desired objects

  I will use the V-REP simulator, because of its broad capacities such as being able to place a camera somewhere in a scene.
