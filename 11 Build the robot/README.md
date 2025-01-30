145. [Mechanics and Electronics](#145)
146. [What you are going to need](#146)
147. [ROS 2 Drivers](#147)
148. [<HWLAB>Laser Scanner ROS 2 Driver</HWLAB>](#148)
149. [<HWLAB>Assemble the Laser Sensor</HWLAB>](#149)
150. [<HWLAB>Linux udev rules</HWLAB>](#150)
151. [<HWLAB>Configure Rplidar Driver</HWLAB>](#151)
152. [<HWLAB>ROS DOMAIN ID</HWLAB>](#152)
153. [<LAB>Launch the Real Robot</LAB>](#153)

---

### 145. Mechanics and Electronics<a id='145'></a>

<img src="assets/images/145/1.png" width="700">

<br>

### 146. What you are going to need<a id='146'></a>

<img src="assets/images/146/1.png" width="700">

<br>

### 147. ROS 2 Drivers<a id='147'></a>

1.  RPlidar setup

#### 1 Terminal
```sh
# install rplidar driver
sudo apt install ros-humble-rplidar-ros


```

#### 2 Terminal
```sh
# 1 Way: press TAB to know the usb port
ls /dev/ttyUSB
# ls /dev/ttyUSB0

# 2 Way: to find out where rplidar is connected
ls /dev | grep ttyUSB
```

#### 1 Terminal
```sh
ros2 launch rplidar_ros rplidar_a1_launch.py serial_port:=/dev/ttyUSB0

```

#### 2 Terminal
```sh
ros2 topic list
ros2 topic echo /scan

ctrl + c
rviz
```

#### rviz
1. In "Rviz" click on add-->by display type--> rviz_default_plugin-->LaserScan--> ok
2. Under "Display" -->laser scan-->Topic:/scan
3. Under "Display" -->Global Options-->Fixed frame:laser
4. (OPTIONAL) Under "Display"-->LaserScan-->Size(m):0.03

<br>

### 148. <HWLAB>Laser Scanner ROS 2 Driver</HWLAB><a id='148'></a>

<br>

### 149. <HWLAB>Assemble the Laser Sensor</HWLAB><a id='149'></a>

<br>

### 150. <HWLAB>Linux udev rules</HWLAB><a id='150'></a>

<br>

### 151. <HWLAB>Configure Rplidar Driver</HWLAB><a id='151'></a>

<br>

### 152. <HWLAB>ROS DOMAIN ID</HWLAB><a id='152'></a>

<br>

### 153. <LAB>Launch the Real Robot</LAB><a id='153'></a>

<br>
