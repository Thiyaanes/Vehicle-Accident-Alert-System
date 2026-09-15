# Vehicle Accident Alert System 

An automated vehicle accident detection system that detects major impacts, identifies the accident location using GPS, and sends emergency alerts to relatives and ambulance services.

## Features

- Detects accidents using an ADXL335 accelerometer.
- Gets the accident location using a GPS module.
- Sends emergency alerts through GSM 800L.
- Notifies registered emergency contacts.
- Supports ambulance dispatch based on accident location.
- Includes testing modules for GSM, LCD, I2C, and the ambulance dispatch algorithm.

## Built With

- Embedded C
- ESP8266
- ADXL335 Accelerometer
- GPS Module
- GSM 800L
- Python
- MySQL
- Google Maps API

## How to Run

### Hardware Setup

1. Connect the ADXL335 accelerometer to the ESP8266.
2. Connect the GPS module for location tracking.
3. Connect the GSM 800L module for SMS alerts.
4. Connect the required power supply.
5. Upload the accident-alert code to the ESP8266.
6. Test the system by simulating an accident/impact.

<img width="1280" height="720" alt="accident-alert-wiring" src="https://github.com/user-attachments/assets/c47c0450-a37a-4572-8562-5bbced8b164c" />

### Libraries

-ESP8266WiFi
-SoftwareSerial
-TinyGPS++
-Wire
-LiquidCrystal_I2C

### Software

1. Open the required project folder in your development environment.
2. Upload/run the corresponding code.
3. Ensure the GPS and GSM modules are connected correctly.
4. Test accident detection and verify that the emergency alert and location are sent successfully.
