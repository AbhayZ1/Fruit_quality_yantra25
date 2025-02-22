# AI-Based Real-Time Fruit Quality Check

->> Project Overview
This project focuses on automating fruit quality assessment using AI. It integrates image processing with an MQ-135 gas sensor to detect defects, assess ripeness, and classify fruit quality for better export standards.

## Features
- Image Processing: A trained AI model analyzes fruit images to check for defects and ripeness.
- Gas Sensor Integration: The MQ-135 sensor detects gas emissions that indicate fruit freshness.
- User Input: Users provide details like fruit quantity, days required before rotting, and location.
- Data Processing: Sensor data is sent to a laptop via Raspberry Pi using serial communication for final processing.
- Export Suitability: The system considers storage duration based on location .

## Accessories used
- Hardware: Raspberry Pi, MQ-135 Gas Sensor, Webcam
- Software: Python, TensorFlow Lite 
