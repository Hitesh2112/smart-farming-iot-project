# Smart Farming - IOT Project
## Description
This project aims to leverage IoT technologies to optimize farming practices. The smart farming system monitors various environmental factors and automates processes to improve crop yield and reduce resource usage.

The Smart Farming System is an innovative and automated solution designed to enhance agricultural practices by integrating modern technologies. This system utilizes NodeMCU, DHT11 temperature and humidity sensor, soil moisture sensor, and an IoT-controlled motor to create a comprehensive smart farming environment.
  - You can see the structure of this repository at : [Repository Structure](https://github.com/Hitesh2112/smart-farming-iot-project/blob/main/repo-Structure.md)

## Key Components
- **NodeMCU**:
   - Serves as the central microcontroller responsible for data processing, sensor interfacing, and communication with the IoT platform.
     ![image](https://github.com/Hitesh2112/smart-farming-iot-project/assets/97521900/6ae7ef0f-6a08-407d-9207-9747448f3e44)
   
- **DHT11 Sensor**:
   - Monitors ambient temperature and humidity levels within the farming environment. This data is crucial for assessing the overall climate conditions that affect crop growth.
     ![image](https://github.com/Hitesh2112/smart-farming-iot-project/assets/97521900/7fa93c31-e486-4c4d-b710-2f901fe660c0)

- **Soil Moisture Sensor**:
   - Measures the moisture content in the soil, providing data for optimized irrigation control.
     ![image](https://github.com/Hitesh2112/smart-farming-iot-project/assets/97521900/d7561e9e-b018-4938-b41a-b544f1de9e3b)

- **IoT Platform**:
   - Enables real-time monitoring and control over the internet, allowing farmers to remotely access and manage the farm parameters.
- **Motor Control**:
   - An IoT-controlled motor for automated irrigation. The motor can be remotely activated or deactivated based on real-time data from the soil moisture sensor, ensuring efficient water usage and crop health.


## Features
+ **Soil Moisture Monitoring**
  + Uses soil moisture sensors to monitor the moisture content in the soil, providing crucial data for irrigation management.
+ **Temperature and Humidity Monitoring**
  + Keeps track of environmental conditions using temperature and humidity sensors.
  + The DHT11 sensor continuously monitors the temperature and humidity levels in the farming environment.
+ **Automated Irrigation System**
  + Automatically waters crops based on soil moisture levels.
  + The IoT-controlled motor is activated or deactivated based on soil moisture levels. If soil moisture drops below a certain threshold, the motor is triggered to irrigate the crops.
+ **Data Logging and Visualization**
  + Logs data and provides visualization to help farmers make informed decisions.
  + NodeMCU processes sensor data and communicates with the IoT platform through a wireless connection.
+ **Remote Monitoring and Control**
  + Enables remote monitoring and control via a web dashboard / website.
  + Farmers can remotely access real-time data and receive alerts or notifications through the IoT platform.


## Benefits
- **Improved Efficiency**:
   - Automated systems reduce the need for manual labor and ensure optimal use of resources like water and fertilizers.
- **Enhanced Crop Yield**:
   - Real-time monitoring and precise control of environmental conditions lead to healthier crops and higher yields.
- **Resource Conservation**:
   - Efficient water usage and targeted fertilization minimize waste and reduce environmental impact.
- **Cost Savings**:
   - Lower labor and resource costs lead to significant savings for farmers.
- **Data-Driven Decisions**:
   - Access to detailed data allows for better planning and decision-making, leading to improved farming practices.
- **Scalability**:
   - The system can be easily scaled to accommodate farms of different sizes and types.
- **Sustainability**:
   - Promotes sustainable farming practices by reducing resource waste and environmental footprint.
 

## Getting Started 
### Prerequisites
- NodeMCU
- DHT11 Sensor
- Soil Moisture Sensor
- Relay Module for Motor Control
- Internet Connection

### Installation
  
1. #### Hardware Setup:

    - Connect the DHT11 sensor to the NodeMCU.
    - Connect the soil moisture sensor to the NodeMCU.
    - Connect the relay module to the NodeMCU for motor control.
    - Connect the motor to the relay module.
  
2. #### Software Setup:
    -  Install the Arduino IDE and necessary libraries for NodeMCU and sensors.
    -  Upload the code to NodeMCU using the Arduino IDE.

### Deployed platform (Website)
The backend of the deployed page is implemented using PHP, ensuring robust data management and communication between the hardware components and the IoT platform, and is deployed at https://mycollegeproject.xyz/SmartIrrigation/login.
 #### Tech Stack Used
 ```
.
├───Frontend
│    ├───HTML
│    ├───CSS
│    └───Javascript
|
├───Backend
│    └───PHP
└───DBMS
      └───SQL to Import in DB

 ```
        


### Usage
- Power on the NodeMCU.
- Ensure that the NodeMCU is connected to the internet.
- Access the IoT platform dashboard to monitor real-time data and control the motor.
- The system will automatically manage irrigation based on soil moisture levels.


//## Acknowledgements
//Special thanks to my team mate Abdullah Jamil and our college seniors for their guidance and support throughout the development of this project.
//And the open-source community for providing the necessary tools and libraries.

## Outro
By integrating modern IoT technologies with traditional farming practices, the Smart Farming System aims to revolutionize agriculture, making it more efficient, sustainable, and accessible.
