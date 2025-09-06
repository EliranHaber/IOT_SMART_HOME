# Smart Home IoT Project

A comprehensive IoT smart home monitoring system with sensor emulators, data management, and real-time GUI monitoring.

## Demo

- 🎥 [Demo Video (YouTube)](https://www.youtube.com/watch?v=3OuBLm_TCl4)
- 📄 [Project Presentation (Canva)](https://www.canva.com/design/DAGyMcfNLYw/bGa1LOjLZwyCaAUpTRBlLQ/edit?utm_content=DAGyMcfNLYw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Features

- **Sensor Emulators**: Temperature, Gas, and Smoke sensors
- **Actuator Emulators**: Alarm Cancel Button and Electric Gas Valve Relay
- **Data Manager**: Collects data from MQTT broker and stores in SQLite database
- **Main GUI**: Real-time monitoring with warning/alarm status display
- **Local Database**: SQLite database for data storage and retrieval

## Requirements

- Python 3.x
- PyQt5
- paho-mqtt
- pandas
- sqlite3

## Setup

1. Install dependencies: `pip install PyQt5 paho-mqtt pandas`
2. Run the main GUI: `python MonitorGUI.py`
3. Run sensor emulators: `python Temperature.py`, `python Gas.py`, `python Smoke.py`
4. Run actuator emulators: `python AlarmCancelButton.py`, `python ElectricGasValveRelay.py`
