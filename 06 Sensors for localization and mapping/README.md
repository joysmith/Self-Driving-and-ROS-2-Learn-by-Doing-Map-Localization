59. [What is a Map](#59)
60. [How Robots Perceive the World](#60)
61. [Sensors for Self-Driving Robots](#61)
62. [1D Sensors - Sonar](#62)
63. [2D Sensors - LiDAR](#63)
64. [<LAB>Add a 2D LiDAR to the Robot</LAB>](#64)
65. [<LAB>Simulate a 2D LiDAR</LAB>](#65)
66. [3D Sensors - RGBD Cameras and 3D LiDAR](#66)
67. [Speed and Separation Monitoring](#67)
68. [twist_mux](#68)
69. [<PY>Twist Relay</PY>](#69)
70. [<C++>Twist Relay</C++>](#70)
71. [<LAB>Configure twist_mux</LAB>](#71)
72. [<LAB>Use twist_mux</LAB>](#72)
73. [<PY>Safety Stop</PY>](#73)
74. [<C++>Safety Stop</C++>](#74)
75. [<LAB>Safety Stop</LAB>](#75)
76. [ROS 2 Actions](#76)
77. [<PY>Create an Action Server</PY>](#77)
78. [<C++>Create an Action Server</C++>](#78)
79. [<LAB>Create an Action Server</LAB>](#79)
80. [<PY>Create an Action Client</PY>](#80)
81. [<C++>Create an Action Client</C++>](#81)
82. [<LAB>Create an Action Client</LAB>](#82)
83. [<PY>Speed and Separation Monitoring</PY>](#83)
84. [<C++>Speed and Separation Monitoring</C++>](#84)
85. [<LAB>Speed and Separation Monitoring</LAB>](#85)
86. [<PY>Display Markers in RViz</PY>](#86)
87. [<C++>Display Markers in RViz</C++>](#87)
88. [<LAB>Display Markers in RViz</LAB>](#88)

---

### 59. What is a Map<a id='59'></a>

<img src="assets/images/059/1.png" width="700">

<img src="assets/images/059/2.png" width="700">

<img src="assets/images/059/3.png" width="700">

<img src="assets/images/059/4.png" width="700">

- refer [slides](https://github.com/joysmith/Self-Driving-and-ROS-2-Learn-by-Doing-Map-Localization/blob/main/06%20Sensors%20for%20localization%20and%20mapping/resources/Section6-Sensors_for_Localization_and_Mapping.pdf)

<br>

### 60. How Robots Perceive the World<a id='60'></a>

<img src="assets/images/060/1.png" width="700">

<img src="assets/images/060/2.png" width="700">

- refer [slides](https://github.com/joysmith/Self-Driving-and-ROS-2-Learn-by-Doing-Map-Localization/blob/main/06%20Sensors%20for%20localization%20and%20mapping/resources/Section6-Sensors_for_Localization_and_Mapping.pdf)

Note:

- accuracy of map depend upon accuracy of sensor

<br>

### 61. Sensors for Self-Driving Robots<a id='61'></a>

<img src="assets/images/061/1.png" width="700">

- refer [slides](https://github.com/joysmith/Self-Driving-and-ROS-2-Learn-by-Doing-Map-Localization/blob/main/06%20Sensors%20for%20localization%20and%20mapping/resources/Section6-Sensors_for_Localization_and_Mapping.pdf)

<br>

### 62. 1D Sensors - Sonar<a id='62'></a>

Ultrasonic wave propagation
<img src="assets/images/062/1.png" width="700">

How to measure distance between robot and obstacle
<img src="assets/images/062/2.png" width="700">

<br>

#### measurement error

Ultrasonic wave propagation speed changes in diff. medium
<img src="assets/images/062/3.png" width="700">

<br>

Ultrasonic wave deflected to another angle due shape of obstacle
<img src="assets/images/062/4.png" width="700">

<br>

Some materials absorb sound waves
<img src="assets/images/062/5.png" width="700">

- refer [slides](https://github.com/joysmith/Self-Driving-and-ROS-2-Learn-by-Doing-Map-Localization/blob/main/06%20Sensors%20for%20localization%20and%20mapping/resources/Section6-Sensors_for_Localization_and_Mapping.pdf)

<br>

### 63. 2D Sensors - LiDAR<a id='63'></a>

<img src="assets/images/063/1.png" width="700">

<img src="assets/images/063/2.png" width="700">

<br>

#### measurement error

<img src="assets/images/063/3.png" width="700">

<img src="assets/images/063/4.png" width="700">

- refer [slides](https://github.com/joysmith/Self-Driving-and-ROS-2-Learn-by-Doing-Map-Localization/blob/main/06%20Sensors%20for%20localization%20and%20mapping/resources/Section6-Sensors_for_Localization_and_Mapping.pdf)

<br>

### 64. <LAB>Add a 2D LiDAR to the Robot</LAB><a id='64'></a>

- refer [slides](https://github.com/joysmith/Self-Driving-and-ROS-2-Learn-by-Doing-Map-Localization/blob/main/06%20Sensors%20for%20localization%20and%20mapping/resources/Section6-Sensors_for_Localization_and_Mapping.pdf)

<br>

### 65. <LAB>Simulate a 2D LiDAR</LAB><a id='65'></a>

- refer [slides](https://github.com/joysmith/Self-Driving-and-ROS-2-Learn-by-Doing-Map-Localization/blob/main/06%20Sensors%20for%20localization%20and%20mapping/resources/Section6-Sensors_for_Localization_and_Mapping.pdf)

<br>

### 66. 3D Sensors - RGBD Cameras and 3D LiDAR<a id='66'></a>

<img src="assets/images/066/1.png" width="700">

<img src="assets/images/066/2.png" width="700">

- refer [slides](https://github.com/joysmith/Self-Driving-and-ROS-2-Learn-by-Doing-Map-Localization/blob/main/06%20Sensors%20for%20localization%20and%20mapping/resources/Section6-Sensors_for_Localization_and_Mapping.pdf)

<br>

### 67. Speed and Separation Monitoring<a id='67'></a>

- refer [slides](https://github.com/joysmith/Self-Driving-and-ROS-2-Learn-by-Doing-Map-Localization/blob/main/06%20Sensors%20for%20localization%20and%20mapping/resources/Section6-Sensors_for_Localization_and_Mapping.pdf)

<br>

### 68. twist_mux<a id='68'></a>

<br>

### 69. <PY>Twist Relay</PY><a id='69'></a>

<br>

### 70. <C++>Twist Relay</C++><a id='70'></a>

<br>

### 71. <LAB>Configure twist_mux</LAB><a id='71'></a>

<br>

### 72. <LAB>Use twist_mux</LAB><a id='72'></a>

<br>

### 73. <PY>Safety Stop</PY><a id='73'></a>

<br>

### 74. <C++>Safety Stop</C++><a id='74'></a>

<br>

### 75. <LAB>Safety Stop</LAB><a id='75'></a>

<br>

### 76. ROS 2 Actions<a id='76'></a>

<br>

### 77. <PY>Create an Action Server</PY><a id='77'></a>

<br>

### 78. <C++>Create an Action Server</C++><a id='78'></a>

<br>

### 79. <LAB>Create an Action Server</LAB><a id='79'></a>

<br>

### 80. <PY>Create an Action Client</PY><a id='80'></a>

<br>

### 81. <C++>Create an Action Client</C++><a id='81'></a>

<br>

### 82. <LAB>Create an Action Client</LAB><a id='82'></a>

<br>

### 83. <PY>Speed and Separation Monitoring</PY><a id='83'></a>

<br>

### 84. <C++>Speed and Separation Monitoring</C++><a id='84'></a>

<br>

### 85. <LAB>Speed and Separation Monitoring</LAB><a id='85'></a>

<br>

### 86. <PY>Display Markers in RViz</PY><a id='86'></a>

<br>

### 87. <C++>Display Markers in RViz</C++><a id='87'></a>

<br>

### 88. <LAB>Display Markers in RViz</LAB><a id='88'></a>

<br>
