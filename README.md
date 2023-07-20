# Overview
This repository contains the firmware and software for a comprehensive Gas Analyzer System designed to monitor gases produced by factories. The system utilizes an STM32F407 microcontroller and incorporates electrochemical sensors for measuring O2, CO2, and CO gas concentrations. Additionally, it includes a temperature sensor to provide context to the gas measurements. The data is transmitted via Modbus UDP and RS232 protocols and visualized in a real-time chart using a Qt software interface. Users can set the data averaging period and the system saves the data to an SQLite database for future reference and analysis.

### Features
Real-time monitoring of O2, CO2, CO, and temperature using electrochemical sensors.
Data transmission via Modbus UDP and RS232 protocols for efficient communication.
Qt software interface for real-time visualization of gas concentrations on a chart.
Configurable data averaging period to provide more meaningful insights.
Data logging and storage in an SQLite database for historical data analysis.

### Components
STM32F407 Microcontroller: The heart of the gas analyzer system, responsible for data processing and communication.
Electrochemical Sensors: Sensors for measuring O2, CO2, and CO concentrations.
Temperature Sensor: Measures ambient temperature for additional context.
Modbus UDP and RS232: Communication protocols used to send sensor data.
Qt Software Interface: Provides real-time chart visualization and user interaction.
SQLite Database: Stores gas concentration data for later retrieval and analysis.

## Setup and Usage
### Hardware Setup:

-	Connect the electrochemical sensors for O2, CO2, and CO to the STM32F407 microcontroller.
-	Connect the temperature sensor to the microcontroller.
-	Ensure the microcontroller is connected to the computer running the Qt software.

## Firmware Setup:
-	Flash the provided firmware onto the STM32F407 microcontroller using an appropriate tool.

## Software Setup:

-	Install the required dependencies for the Qt software interface.
-	Compile and run the Qt software on the computer.

## User Interface:
The Qt software displays real-time data from the gas analyzer system in a chart.
Users can configure the data averaging period through the user-friendly interface.

## Data Logging:
-	The system automatically saves the received data to an SQLite database.
-	Users can access historical data for analysis and comparison.

## Contribution Guidelines
Contributions to the Gas Analyzer System are welcome! If you wish to contribute, please follow these guidelines:

Fork the repository and create a new branch for your feature or bug fix.
Make your changes, test them thoroughly, and ensure the code adheres to the project's coding standards.
Commit your changes and create a detailed pull request with a clear explanation of the changes and their purpose.

## Licensing
The Gas Analyzer System is licensed under the [MIT License](https://github.com/AmirhoseinMasoumi/GasAnalyzer/blob/main/README.md#:~:text=licensed%20under%20the-,MIT%20License,-.).

## Disclaimer
This Gas Analyzer System is intended for informational purposes only. The developers and maintainers of this repository are not responsible for any direct or indirect damages caused by the use or misuse of the system.

---

![Tilted](https://github.com/AmirhoseinMasoumi/GasAnalyzer/blob/main/Assets/software.png)

---
![Tilted](https://github.com/AmirhoseinMasoumi/GasAnalyzer/blob/main/Assets/board.png)

---
