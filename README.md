# Group 10 Project

## Team Members
- **Nicola Calzone**  
  Email: [nicola.calzone@studenti.unipd.it](mailto:nicola.calzone@studenti.unipd.it)
  
- **Leonardo Da Re**  
  Email: [leonardo.dare@studenti.unipd.it](mailto:leonardo.dare@studenti.unipd.it)
  
- **Nicolò Tesser**  
  Email: [nicolo.tesser@studenti.unipd.it](mailto:nicolo.tesser@studenti.unipd.it)

## Instructions

To set up and run the project, please follow these steps:

1. **Start TIAGo**:
   ```bash
   start_tiago
   ```

2. **Source ROS Noetic**:
   ```bash
   source /opt/ros/noetic/setup.bash
   ```

3. **Source TIAGo Public Workspace**:
   ```bash
   source /tiago_public_ws/devel/setup.bash
   ```

4. **Source Your Catkin Workspace**:
   ```bash
   source ~/catkin_ws/devel/setup.bash
   ```

5. **Launch the Simulation**:
   ```bash
   roslaunch tiago_iaslab_simulation start_simulation.launch world_name:=robotics_library
   ```

6. **Launch Navigation**:
   ```bash
   roslaunch tiago_iaslab_simulation navigation.launch
   ```

7. **Run the Server**:
   ```bash
   rosrun ir2324_group_10 poseServer
   ```

8. **Run the Client**:
   ```bash
   rosrun ir2324_group_10 poseClient
   ```

## Additional Resources

- **Video Demonstration**: [Google Drive Video](https://drive.google.com/drive/folders/1ZDX1ySTXKN7QxGVAr1h5RXjHNFYQaIgr)

---
Thank you for your interest in our project!
```

