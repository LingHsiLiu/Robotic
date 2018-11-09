# Robotic team 
Situation:
We join the FIRA Cup and ROBOT cup completition.
In the FIRA Cup, our robot is humanoid robot. And, In the FIRA cup, the robot is home robot, it is the first generation robot in our team.
In the FIRA cup, the robot play the soccor, Obstacle Run, penalty kick and weight Lifting.

Result:
we got reward.

Action:
In the FIRA Cup, we use 26 motors, like human, it could wake, talk somethiing, when they fall down, they could automatically to stand up. the robot high is 46 cm. 
In this system we use Altera FPGA kit, we could build CPU and assign pin for each function. It also have system which is NIOS II, so we write the C++ in NIOS II.

Created RS232 Transfer module, data analysis module, sensor receiver module, flash access, action execution module and servomotor execution module for Robots.
RS232 Transfer module: transfer data from human command to NIOS II (Robot system)
Data analysis module: determine command packet or flash data access packet
Sensor receiver module: sensors detect environment and transfer data to human computer, or get information from data analysis module. 
Flash access module: write, read and erase (chip erase or sector erase) function to control action execution module
Action execution module: give instructions to servomotor execution module
Servomotor execution module: transfer signal to servomotor
