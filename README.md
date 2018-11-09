# Robotic team 
Situation:
We join the FIRA Cup and ROBOT cup completition.
In the FIRA Cup, our robot is humanoid robot. And, In the FIRA cup, the robot is home robot, it is the first generation robot in our team.
In the FIRA cup, the robot play the soccor, Obstacle Run, penalty kick and weight Lifting.

1. when the robot walk, it need to balance center of gravity by themself. 
2. When robot play the soccor, firstly robot find the ball and calculate how many distance from the ball. Then, walk to near the ball. Then, Find the soccor goal and small move and make soccor goal and ball to be a line. Then, kick the ball.
3. Obtacle Run, there are some obtacle in front of robot. And, Robot need to find where could walk and out of these obtacle. 

Result:
we got reward.

Action:
In the FIRA Cup, we use 26 motors, like human, it could wake, talk somethiing, when they fall down, they could automatically to stand up. the robot high is 46 cm. 
In this system we use Altera FPGA kit, we could build CPU and assign pin for each function. It also have system which is NIOS II, so we write the C++ in NIOS II.

Created RS232 Transfer module, data analysis module, sensor receiver module, flash access, action execution module and servomotor execution module for Robots.
1. RS232 Transfer module: transfer data from human command to NIOS II (Robot system)
2. Data analysis module: determine command packet or flash data access packet
3. Sensor receiver module: sensors detect environment and transfer data to human computer, or get information from data analysis module. 
4. Flash access module: write, read and erase (chip erase or sector erase) function to control action execution module
5. Action execution module: give instructions to servomotor execution module
6. Servomotor execution module: transfer signal to servomotor
