



Uploaded image
create a readme file for this project , just with tech stack and this image of stage of implementation 

Guardian 360 – Elderly Safety Wearable System
A real-time AI-powered wearable system for elderly safety monitoring using sensor-based gait analysis, fall detection, emergency alerts, and caregiver monitoring.

Project Overview
Guardian 360 is a smart wearable prototype designed to monitor elderly movement patterns and detect:

Normal activities

Abnormal gait patterns

Fall risks

Fall events in real time

The system combines:

Wearable IMU sensors

Deep Learning (CNN-GRU)

IoT communication

Real-time alerts

Caregiver dashboard integration

The project focuses on creating a lightweight and practical real-time monitoring system for elderly care and emergency response.

Tech Stack
Hardware
ESP32 DevKit V1

MPU6050 (Accelerometer + Gyroscope)

MAX30102 (Heart Rate & SpO2)

OLED Display

Buzzer

SOS Button

Camera Trigger Module

Software & AI
Python

TensorFlow

TensorFlow Lite

NumPy

Pandas

Scikit-learn

Matplotlib

AI/ML Model
CNN-GRU Hybrid Deep Learning Model

IoT & Cloud
Firebase

WiFi Communication

Push/SMS Alert Integration

Dataset & Processing
Sensor Windowing

Normalization

Activity Labeling

Train/Validation/Test Splitting

System Workflow
Sensor Data → CNN-GRU Model → Fall/Gait Prediction
                ↓
          Alert Generation
                ↓
     Caregiver Notification
Implementation Stages

Phase 2 Implementation Roadmap
Week 1 – Hardware Setup & Integration
ESP32 setup

MPU6050 integration

MAX30102 integration

OLED, buzzer, and SOS testing

Week 2 – Dataset Collection & Activity Recording
Record normal activities

Record abnormal gait patterns

Record fall activities

Label and save dataset

Week 3 – Data Preprocessing & Preparation
Data cleaning

Normalization

Windowing (2–3 seconds)

Train/Validation/Test split

Week 4 – CNN-GRU Model Development & Training
Build CNN-GRU model

Train the model

Hyperparameter tuning

Performance evaluation

Week 5 – Real-Time Integration & Fall Detection
Stream sensor data

Run real-time inference

Detect fall and high-risk conditions

Trigger local alerts

Week 6 – IoT, Alerts & Dashboard
Firebase integration

SMS/Push notifications

Camera trigger on fall

Dashboard/App development

Expected Features
Real-time fall detection

Abnormal gait analysis

Emergency SOS system

Smart alert generation

Camera trigger during fall events

Caregiver monitoring dashboard

IoT-based remote monitoring

Expected Outcome
A fully functional prototype capable of:

Real-time AI prediction

Fall detection

Emergency alerts

Camera triggering

Remote caregiver monitoring

Research Goal
“A lightweight CNN-GRU hybrid deep learning architecture for real-time elderly gait analysis and fall risk prediction using wearable IMU sensors.”

Reference
Implementation roadmap and AI workflow based on the Guardian 360 Phase 2 planning document. 



make it a reallly short read me file in md format

# Guardian 360

AI-powered elderly safety wearable for real-time gait analysis, fall detection, alerts, and caregiver monitoring.

## Tech Stack

### Hardware
- ESP32
- MPU6050
- MAX30102
- OLED Display
- Buzzer & SOS Button

### Software & AI
- Python
- TensorFlow
- CNN-GRU Model
- TensorFlow Lite

### Cloud & IoT
- Firebase
- WiFi
- Push/SMS Alerts

## Implementation Stages

![Work Plan](./work_plan.png)

## Features
- Real-time fall detection
- Abnormal gait detection
- Emergency alerts
- Camera trigger on fall
- Caregiver dashboard

