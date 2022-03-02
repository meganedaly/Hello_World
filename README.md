# Hello_World
I am currently a junior at the Tippie College of Business. I am studying Marketing and Business Analytics and Information Systems.

## TABLE OF CONTENTS
- ### Project Name: 
- ### Description: 
- ### How does it run?
- ### What files did I use?
- ### More Documentation? 
- ### Versions: 

## PROJECT NAME:
*Military Time*

## DESCRIPTION:
In the first part of the project, the user is prompted to enter the diameter of a circle as input. The program then finds the area.

In the second part of the project, the user is prompted to enter the total number of seconds that already passed in a day.
The program then finds the current time and outputs it as military time.

## HOW DOES IT RUN?
import math
diameter=float(input("Please enter the diameter of the circle:"))
area=(math.pi/4)*(diameter*diameter)
radius=diameter/2
area2=math.pi*radius*radius

print("Area is:",area2)


seconds=float(input("Enter the number of seconds that have passed today:"))
hourss=seconds/3600
y=hours-int(hours)
z=round(y*60,0)
mintues=int(z)
hour=int(y)
hours=int(hourss)
print("The time is:"+str(hours)+":"+str(minutes))

## WHAT FILES DID I USE?
**I did not use any files.**

## MORE DOCUMENTATION?
**There is no more documentation**

## VERSIONS:
*This was the one and only version of this project.*
