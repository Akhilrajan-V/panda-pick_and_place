# panda-pick_and_place
This code is modified from the [Moveit pick and place tutorial](http://docs.ros.org/en/kinetic/api/moveit_tutorials/html/doc/pick_place/pick_place_tutorial.html).

1. Download this repository into moveit workspace. Then catkin build or catkin_make.
2. Open terminal and launch moveit demo.launch using,
> roslaunch panda_moveit_config demo.launch 
3. In the Rviz window navigate to scene objects tab. Click on **Import**.
4. Navigate to the scene sub directory within the pick_place directory and select ```pick_place.scene```.
5. Click on **Publish** to import the table and obstacles into the workspace.
6. Open a new terminal and run the tbl_pick_place executable file. 
> rosrun pick_place tbl_pick_place   
