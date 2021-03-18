# Smarthouses
### Calhoun Discovery Program - Work Cell 3A (IoT systems)
Developing an algorithm to optimize warehouse truck to dock selection based on machine learning and image classification. In order to provide warehouse managers with the information they need to make effective dock assignment decisions, our solution will take advantage of IoT systems integrated with edge computing nodes to send real-time data that will drive an algorithm enabling warehouse managers to connect trucks to docks efficiently, effectively reducing delays, driving down costs and improving worker safety.
![alogirthm](https://user-images.githubusercontent.com/45275407/111561030-290e0580-876a-11eb-93ef-235e08915b94.gif)
<br>
## Wristband Technology
Part of our prototype consists of a feasible locating system. Each worker is given a wearable device that can accurately pinpoint their position in real time using ultra wide-band technology. This position data is then converted into a density plot that illustrates where and when worker activity is at a peak. A warehouse manager could use this information to determine when certain docks are busy. <br>
![heatmapgif](https://user-images.githubusercontent.com/45275407/111561078-40e58980-876a-11eb-821f-c983e7a548bd.gif) <br>
## Image Classification
To identify which dock has the least clutter or hazards, an image classification algorithm such as YOLOv3 will be applied to security camera footage in the warehouse. This security camera footage is also responsible for determining whether or not each dock is already occupied. The image analyses and worker density maps are then processed to determine dock safety and worker availability respectively. Information from these sensors is communicated to the algorithm via an ultra-wideband network and processed using edge computing. <br>
![warehouseclassify](https://user-images.githubusercontent.com/45275407/111561116-5195ff80-876a-11eb-9ded-bfac73be7b83.JPG)<br>
The algorithm will use these and other characteristics in order to map each incoming truck to the safest, most available dock in the warehouse. This multivariate Gaussian process algorithm uses reinforcement learning to ensure higher accuracy every iteration. The results of this calculation will be clearly displayed to a warehouse manager who can then direct the incoming truck safely and efficiently.<br>
The Mathematica file provided in this repository provides greater detail about the inner mechanisms of our prototype.
