### Margasuchi - Navigation

We will use High definition(HD) maps of Habitat and Greenhouse.

Navigation process involves below modules
* Localization
* Perception
* Prediction
* Planning
* Control


* Localization 
  * Shows how the robot detects its location in the Habitat
  * Use Camera (v1), laser and radar data.
  * Compares what it sees through the sensors to a HD Map.
  * Localize with single digit centimeter level accuracy

* Perception
  * How the robot sees the Habitat and Greenhouse
  * CNN is used for classification, detection and segmentation
  * Data used from several sensors on the robot and Habitat including Cameras, radar and lidar

* Prediction
  * How other robots move and where the target location for assigned task is located. 
  * RNN : time-series data is used to predict the future

* Planning
  * combine prediction and routing to generate trajectories for robotic swarm

* Control
  * Use steering, brake and throttle to execute planned trajectory
  * 2D trajectory for Nandi UGV drone
  * 3D trajectory for Garuda UAV drone