# Inverse-kinematic-modeling-using-robo-analyzer-
## SUJITH
## 212221220052

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:
```
open the roboanalyzer software.
select the robot and its degrees of freedom.
change the values of X and Y wherever necessary.
simulate the model for inverse kinematics.
plot the graph between the joints.
update the DH parameters of the link configuration and end effector configuration.
```





### SIMULATION 
 
 
 RPR ROBOT:
 
 
 
 ![image](https://github.com/SUJITH04/Inverse-kinematic-modeling-using-robo-analyzer-/assets/130206202/61a7eb3b-a1f4-40e0-ac83-c9f9e4363e67)


![image](https://github.com/SUJITH04/Inverse-kinematic-modeling-using-robo-analyzer-/assets/130206202/fd6a4ef4-d081-481b-b21c-9ec38be5b3ce)

 
 
 
 
 
 3R ROBOT:
 
 
 
 
 
 
 ![image](https://github.com/SUJITH04/Inverse-kinematic-modeling-using-robo-analyzer-/assets/130206202/c12350ee-2dc5-4fc0-a806-7911ee01299e)

 

 
 
### PLOT



RPR ROBOT:



![image](https://github.com/SUJITH04/Inverse-kinematic-modeling-using-robo-analyzer-/assets/130206202/1478f9c6-765f-477a-b7e3-b239d3fb8eaf)



![image](https://github.com/SUJITH04/Inverse-kinematic-modeling-using-robo-analyzer-/assets/130206202/b74a11c1-7f99-449d-ad37-62eae838d13c)



3R ROBOT:



![image](https://github.com/SUJITH04/Inverse-kinematic-modeling-using-robo-analyzer-/assets/130206202/64878869-50b4-4245-9896-a2b8fc288805)



![image](https://github.com/SUJITH04/Inverse-kinematic-modeling-using-robo-analyzer-/assets/130206202/5cfe6aec-49f6-4933-b3e1-3f11ff019716)

### RESULTS :  

Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted
