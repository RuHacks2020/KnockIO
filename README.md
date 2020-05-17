# KnockIO

## Video Showcase

[![](http://img.youtube.com/vi/06vP1Mp9uDY/0.jpg)](http://www.youtube.com/watch?v=06vP1Mp9uDY "")


## Inspiration
KnockIO came from the need of a simple and cheap solution for a IOT doorbell. Allowing anyone to build a small, cheap, and open source video doorbell, without spending hundreds of dollars. While also maintaining top notch privacy and security, without any compromises.


## What it does
KnockIO's open source technology allows the consumer to build a video camera and allows for the data to be self hosted, therefore not collected by any party other than the user. It features push notification to alert the user if anyone is outside, a buzzer, and a speaker. 


## How we built it
KnockIO was build on a ESP32 micro-controller, programmed in C++. The ESP32 sends the image frames directly to the NodeJs backend server for processing, such as face recognition, and motion detection. Which is displayed using our frontend build in Vue. 


## Links

ESP Code: This repo

FrontEnd: https://github.com/RuHacks2020/KnockIO-Frontend

Backend: https://github.com/RuHacks2020/KnockIO-Node-Server

Devpost: https://devpost.com/software/knockio


Circuit Schematic:

![](https://i.imgur.com/4pN8AFMl.png)

3D Render:

![](https://i.imgur.com/7AOqwdX.png)

Final 3D Printed Prototype:

![](https://i.imgur.com/aFjwors.jpg)

Inside View:

![](https://i.imgur.com/WMIREXs.jpg)

