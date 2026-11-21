# Milk Quality and Adulteration Detection at Collection Centres

## 1. Project Description

Milk adulteration and spoilage are major concerns at village milk collection centres, where laboratory testing facilities may not be readily available.

Our project aims to develop a low-cost, real-time milk quality monitoring system using IoT sensors, cloud computing and machine learning.

The system measures milk properties such as pH, electrical conductivity, temperature and colour. An ESP32 or Raspberry Pi collects the sensor readings and securely sends them to AWS IoT Core using MQTT and X.509 authentication.

AWS Lambda processes the incoming data and stores it in Amazon DynamoDB. Amazon SageMaker AI is used to classify milk samples as **Pure, Adulterated or Spoiled**. Amazon SNS sends alerts when a sample is flagged.

The system aims to improve milk safety, quality monitoring and traceability.

## 2. Objectives

- Monitor milk quality in real time.
- Detect possible adulteration and spoilage.
- Use machine learning to classify milk samples.
- Store sensor readings securely in AWS.
- Send alerts when unsafe milk is detected.
- Provide an affordable solution for milk collection centres.

## 3. Hardware Components

1. ESP32 / Raspberry Pi
2. pH Sensor
3. Electrical Conductivity Sensor
4. DS18B20 Temperature Sensor
5. Colour Sensor

## 4. AWS Services Used

1. AWS IoT Core – Device connectivity using MQTT and X.509 authentication.
2. AWS IoT Rules Engine – Routes incoming sensor data.
3. AWS Lambda – Processes and validates sensor readings.
4. Amazon DynamoDB – Stores processed readings.
5. Amazon S3 – Archives raw data.
6. Amazon SNS – Sends alerts.
7. Amazon EventBridge – Schedules periodic reports and retraining.
8. Amazon SageMaker AI – Performs milk quality classification.
9. Amazon CloudWatch – Monitors system performance.

## 5. Team Details

| Name | Student ID |
|---|---|
| Neha Deepika | 2520030068 |
| K. Siri Chandana | 2520030453 |
| G. Sahithi | 2520030499 |
| Sk. Sabiya Thabassum | 2520030502 |

**Team Number:** 7  
**Section:** 1

## 6. Project Guide

**Guide Name:** Harika Devi  
**Designation and Department:** To be filled in.

## 7. Project Documents

- Abstract: `docs/Abstract.pdf`
- Presentation: `docs/Presentation.pdf`

## 8. Expected Outcome

The proposed system aims to provide a scalable and affordable milk quality screening solution. It can help collection centre operators identify potentially adulterated or spoiled milk, improve traceability and support safer dairy supply chains.
