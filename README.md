# 4.11.1: LAB: Remove gray from RGB

Given integer values for red, green, and blue, subtract the gray from each value.

Computers represent color by combining the sub-colors red, green, and blue (rgb). Each sub-color's value can range from 0 to 255. Thus (255, 0, 0) is bright red, (130, 0, 130) is a medium purple, (0, 0, 0) is black, (255, 255, 255) is white, and (40, 40, 40) is a dark gray. (130, 50, 130) is a faded purple, due to the (50, 50, 50) gray part. (In other words, equal amounts of red, green, blue yield gray).

Given values for red, green, and blue, remove the gray part.

## Getting Started

These instructions will install pycharm on your local machine.
### Prerequisites

Python requires pycharm to run, with no other additional packages. The commands below will install pycharm on to your local system. 


Link: [Pycharm]https://www.jetbrains.com/pycharm/download/#section=windows)


## Running
Once installed you can run the program with the following command

**Remove gray from RGB**
```
red = int(input())
green = int(input())
blue = int(input())

num1 = (red, green, blue)
a = min(num1) 
gray_colors_red = (red - a) 
gray_color_green = (green - a)
gray_color_blue = (blue - a)
print(gray_colors_red, gray_color_green, gray_color_blue)
```

**input**
```
130
50
130
```

**output**
```
80 0 80
```
## Thanks
