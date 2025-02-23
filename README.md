# YOLO and OpenCV for Energy Saving via Object Detection.

## Overview
The Energy Saving IoT Automation System is an innovative project designed to reduce energy wastage by automating the control of home appliances. The system utilizes sensor data and real-time image processing to detect room occupancy and adjust appliance settings (such as fan speed and lighting) accordingly. This project not only improves energy efficiency but also enhances safety and convenience for users.

## Motivation:
With rising energy consumption and increasing electricity bills, there is a growing need to use energy more efficiently. Traditional manual switching of appliances can lead to unnecessary energy waste, especially when rooms are unoccupied.

## Objectives:
1. Automatically detect human presence using image processing.
2. Adjust fan speed based on real-time temperature readings.
3. Reduce energy wastage by ensuring appliances operate only when needed.
4. Provide remote monitoring and control of home appliances using IoT connectivity.

## Key Features
**1. Automatic Appliance Control:**
The system turns appliances (such as fans and lights) on or off based on occupancy detection and environmental conditions.

**2. Temperature-Based Fan Speed Control:**
A temperature sensor (e.g., LM35) monitors the room temperature and adjusts the fan speed accordingly to maintain a comfortable environment.

**3. Real-Time Object Detection:**
Utilizes the YOLO (You Only Look Once) algorithm to detect people in video streams, ensuring accurate occupancy detection.

**4. Image Processing with OpenCV:**
OpenCV is used to capture video, process frames, and highlight detected objects with bounding boxes, making it easy to visualize system performance.

**5. IoT Connectivity:**
Integrates Arduino UNO, NodeMCU, and MQTT messaging to create a seamless interface between hardware sensors, controllers, and the software application.

## Technologies Used
**1. YOLO (You Only Look Once):**
Employed for real-time object detection in video streams.
Loads pre-trained YOLOv3 weights and configuration files to accurately detect humans.

**2. OpenCV:**
Handles video capture and image processing tasks.
Provides functions to process frames, draw bounding boxes around detected objects, and display real-time information.

**3. Python:** For scripting and handling the image processing and IoT control logic.

**4. Arduino UNO & NodeMCU:** For interfacing with sensors (temperature, PIR) and controlling appliances.

**5. MQTT:** Facilitates messaging between IoT devices.

**6. Sensors:** These include temperature sensors (e.g., LM35) and PIR sensors for human detection.  
