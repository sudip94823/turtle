# turtle
**Week-4 Task**

***_Turtlesim Installation_***

**Installation Steps**
- To make sure the system is up-to-date
```
sudo apt update 
```
- To install the turtlesim library
```
sudo apt install ros-rolling-turtlesim
```
![#1](https://user-images.githubusercontent.com/113494159/192174192-6d725697-383d-4a3c-9bef-4d5a1917136b.png)
- [#1.png] above shows the output of the installed turtlesim library.



1. **Starting the Turtlesim**
```
ros2 run turtlesim turtlesim_node
```
***This command opens up a simulator windows with a random turtle in the center.***
![#2](https://user-images.githubusercontent.com/113494159/192174251-2b255c6e-c634-4acd-9558-6f4a582fd2f1.png)

2. **Controlling the Turtle**
```
ros2 run turtlesim turtle_teleop_key
```
![Turtle](https://user-images.githubusercontent.com/113494159/192175725-eb5d828f-26ec-4c09-a78f-e56ed36dec44.png)

3. **RQT Installation**
```
sudo apt install ~nros-rolling-rqt*
```

**Running RQT**
![#3](https://user-images.githubusercontent.com/113494159/192157358-b07e4bb3-2891-4b0f-8369-ff4241ee19ac.png)

4. **Starting rqt_console**
```
ros2 run rqt_console rqt_console
```

![#4](https://user-images.githubusercontent.com/113494159/192157362-ff19aa73-21f4-4dd0-8269-9eadd3180303.png)

5. **Creating Another Turtle**


![#5](https://user-images.githubusercontent.com/113494159/192176295-2c9a0cf5-2442-4835-a402-482695e1b519.png)


![2 turtles](https://user-images.githubusercontent.com/113494159/192176320-9273e666-9863-47a7-9960-40d77490d4a2.png)
519.png)


***Node Graph***
![Node Graph](https://user-images.githubusercontent.com/113494159/192176655-2dc11b1c-879f-4c50-96c9-0edfab4fbf5c.png)

![ezgif com-gif-maker](https://user-images.githubusercontent.com/113494159/192176830-843fecaf-a623-4464-9a45-07a25a0d4d4f.gif)
