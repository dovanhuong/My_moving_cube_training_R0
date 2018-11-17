# My_moving_cube_training_R0
This project was used Q-Learning algorithm to training robot how to rotate and move to the desired position. 
<br>Thanks to ROS and Gazeo7 and OpenAI Gym library were provided great environment to complete this simulation.
<br> Requirement software: ROS, OpenAI gym, Gazebo 7, openai_ros package.
<br> Build and run this code follows steps as below:<br>
   1. Launch 3D model of robot. <br>
      $ roslaunch my_moving_cube_description spawn_moving_cube.launch
      <br>
   2. Launch control for robot.<br>
      $ roslaunch my_moving_cube_description moving_cube_control.launch
   3. Launch Q-Learning algorithm for robot. <br>
      $ roslaunch my_moving_cube_training_pkg start_training.launch
<br><br>
If you have any futher advice or develop from this, kindly send me via email: vanhuong.robotics@gmail.com

