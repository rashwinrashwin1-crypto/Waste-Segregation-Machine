# Waste Segregation Machine using Arduino UNO

## About the Project

The Waste Segregation Machine is a simple Arduino UNO based project developed to separate wet and dry waste. The main purpose of this project is to reduce manual effort in waste segregation and make the process easier using sensors and a small automatic mechanism.

The system uses a soil moisture sensor to detect the moisture present in the waste. The Arduino UNO receives the sensor reading and controls a servo motor based on the detected condition. The servo motor moves the waste towards the required container. An ultrasonic sensor is also included to monitor the waste level in the bin.

## Components Used

The main components used in this project are Arduino UNO, soil moisture sensor, servo motor, ultrasonic sensor, jumper wires, waste containers and power supply.

## Working

When the waste is placed into the input section, the soil moisture sensor checks whether the waste contains moisture. The sensor value is given to the Arduino UNO, which processes the input and controls the servo motor.

The servo motor changes its position according to the detected waste condition and directs the waste into the respective container. The ultrasonic sensor is used to check the level of waste collected in the container.

## Software Used

The project was developed using the Arduino IDE and Arduino programming with Embedded C.

## Project Flow

```text
Waste Input
     ↓
Soil Moisture Sensor
     ↓
Arduino UNO
     ↓
Servo Motor
     ↓
Wet / Dry Waste Container
     ↓
Ultrasonic Sensor
```

## Project Structure

```text
Waste-Segregation-Machine/
│
├── Arduino_Code/
├── Circuit_Diagram/
├── Block_Diagram/
├── Images/
├── Report/
└── README.md
```

## Future Improvements

The project can be improved in the future by adding IoT connectivity, mobile notifications and additional sensors for identifying different types of waste. The system can also be developed further for larger-scale waste management applications.

## Project Details

**Project Title:** Waste Segregation Machine using Arduino UNO
**Domain:** Embedded Systems
**Controller:** Arduino UNO
**Programming:** Embedded C / Arduino

## Conclusion

This project helped us understand the practical use of Arduino, sensors and servo motors in automation. The Waste Segregation Machine provides a simple method for separating wet and dry waste and can be further developed with additional features for real-world applications.
