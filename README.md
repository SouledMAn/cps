# cps

**experiment 3.1,3.2,3.3
**
https://www.tinkercad.com/things/6XbuuNlrTbH-31cps?sharecode=-gvMjN4u8lwBqxwP2dP_jX-lTkCsfZs7t8_Jlt6HE-I

https://www.tinkercad.com/things/esmYISy5NZF-32cps?sharecode=GjrYNGzUz_VHLP89a7AF7SbR57rNGAz1sIYQPc3sgwM

https://www.tinkercad.com/things/hK6Ys2zp13N-33cps?sharecode=gg11nsI7FNMMAzRUADQbpiHGRYic8imY8bIh7VQQSmk

**experiment 4.1,4.2
**
https://www.tinkercad.com/things/0Wi4yFHCFpk-41?sharecode=VrjBEU6n4Lcv3mokr0f0ti9hOWImuMK2aHi8MdMVC3Y

https://www.tinkercad.com/things/kr8vCLKCpey-42cps?sharecode=DYMmlsVPCPVe3AFwdDei9201c0uPRegTZyFZZ4391ZI

**experiment 5
**
https://www.tinkercad.com/things/kWIJQPKTBRQ-51?sharecode=rG_OBx1sc7kAyb1TnQphoLq2D-MPElYcKvRMykQ_418

**experiment 6
**

https://www.tinkercad.com/things/0xpgltZJsaE-6?sharecode=13PL-Vc4OXwgyb2Qom2EvzoBgq9JOR3CPdo-vet0UFA

**experiment 7
**

https://www.tinkercad.com/things/7MDdIm7MBUo-7?sharecode=ASgwRNlaWQmzNcHgS_VylkLeSurHSHxNNypuIS6dAD0




CPS Laboratory Experiments - TinkerCAD Projects

This repository contains a comprehensive collection of Cyber Physical Systems (CPS) laboratory experiments implemented using TinkerCAD. The experiments cover fundamental concepts of embedded systems, IoT protocols, sensor interfacing, and cloud connectivity.
📋 Table of Contents

    Experiment 3: LED Control Systems
    Experiment 4: Sensor Data Reading
    Experiment 5: PIR Sensor with Alert System
    Experiment 6: Basic Weather Station
    Experiment 7: Virtual IoT Device
    Experiment 8: MQTT Protocol Study
    Experiment 9: MQTT Communication
    Experiment 10: LabVIEW Database Integration
    Experiment 11: LabVIEW Cloud Connectivity

Experiment 3: LED Control Systems
3.1 Basic LED Blinking

Objective: Blink an LED using Arduino UNO by controlling GPIO pin output levels

Components:

    Arduino UNO
    LED (any color)
    220Ω Resistor
    Breadboard
    Jumper Wires

TinkerCAD Link: LED Blinking Circuit

Key Features:

    GPIO pin control (HIGH/LOW)
    1-second delay intervals
    Current limiting with 220Ω resistor

3.2 LED Control with Push Button

Objective: Toggle LED state using a push button with state management

Components:

    Arduino UNO
    LED
    Push Button
    220Ω Resistor
    Breadboard

TinkerCAD Link: Push Button LED Control

Key Features:

    Digital input reading
    State toggle logic
    Debounce handling

3.3 LED Digital Counter

Objective: Create a 4-bit binary counter display using 4 LEDs

Components:

    Arduino UNO
    4x LEDs
    4x 220Ω Resistors
    Breadboard

TinkerCAD Link: Digital Counter Circuit

Key Features:

    Binary counting (0-15)
    Sequential LED patterns
    500ms timing intervals

Experiment 4: Sensor Data Reading
4.1 Potentiometer Reading

Objective: Read analog input from potentiometer and display values on Serial Monitor

Components:

    Arduino UNO
    Potentiometer
    Breadboard
    Jumper Wires

TinkerCAD Link: Potentiometer Reading

Key Features:

    Analog input reading (A0)
    Serial communication
    Real-time data monitoring

4.2 LDR Sensor with LED Control

Objective: Use Light Dependent Resistor to control LED based on light intensity

Components:

    Arduino UNO
    LDR (Light Dependent Resistor)
    LED
    220Ω Resistor
    10kΩ Resistor

TinkerCAD Link: LDR Sensor Circuit

Key Features:

    Light intensity measurement
    Threshold-based LED control
    Automatic lighting system

Experiment 5: PIR Sensor with Alert System

Objective: Create a motion detection system with visual and audio alerts

Components:

    Arduino UNO
    PIR Motion Sensor
    LED
    Piezo Buzzer
    Resistors

TinkerCAD Link: PIR Alert System

Key Features:

    Motion detection
    Dual alert system (LED + Buzzer)
    Real-time monitoring
    Compact data display format

Experiment 6: Basic Weather Station

Objective: Design a comprehensive weather monitoring system with multiple sensors and display

Components:

    Arduino UNO
    LDR (Light Sensor)
    Temperature Sensor (TMP36/LM35)
    16x2 LCD Display
    Piezo Buzzer
    Multiple LEDs
    Potentiometers
    Resistors

TinkerCAD Link: Weather Station

Key Features:

    Multi-parameter monitoring (Temperature, Light)
    LCD data display
    Threshold-based alerts
    Weather condition classification
    Visual and audio notifications

Experiment 7: Virtual IoT Device

Objective: Create a virtual IoT device integrating sensors and actuators with cloud connectivity simulation

Components:

    Arduino UNO
    Servo Motor
    Temperature Sensor
    Potentiometer
    Switch/Button
    Breadboard

TinkerCAD Link: Virtual IoT Device

Key Features:

    Sensor-actuator integration
    Servo motor control based on sensor input
    Dual input modes (manual/automatic)
    IoT device simulation

Experiment 8: MQTT Protocol Study

Objective: Study and understand MQTT protocol components and characteristics

Key Components Studied:

    Publisher: Sends messages to topics
    Subscriber: Receives messages from subscribed topics
    Broker: Central message distribution server
    Topics: Message categorization system
    QoS Levels: Message delivery guarantees (0, 1, 2)
    Client ID: Unique device identification
    Last Will Testament: Disconnect notification system

MQTT Characteristics:

    Lightweight and efficient
    Publish/Subscribe model
    Quality of Service levels
    Retained messages
    Low bandwidth requirements

Experiment 9: MQTT Communication

Objective: Implement practical MQTT communication using MQTT Explorer and cloud broker

Tools Used:

    MQTT Explorer: GUI tool for MQTT communication
    Test Broker: testclient-cloud.mqtt.cool
    Protocol: MQTT over TCP (Port 1883)

Implementation:

    Broker connection establishment
    Topic subscription and publishing
    Real-time message exchange
    Cross-platform communication testing

Experiment 10: LabVIEW Database Integration

Objective: Configure LabVIEW for local database connectivity and data visualization

Components:

    Database Tools: Connection, Query, Data manipulation VIs
    SQL Integration: Custom query execution
    Data Visualization: Waveform graphs
    Error Handling: Comprehensive error management

Key Features:

    Local database connectivity
    SQL query filtering (WHERE randomvalue < 0.5)
    Real-time data visualization
    Anomaly detection and analysis

Experiment 11: LabVIEW Cloud Connectivity

Objective: Upload sensor data to ThingSpeak cloud platform using LabVIEW

Components:

    LabVIEW HTTP VIs: Web communication tools
    ThingSpeak API: Cloud data platform
    Data Fields: Multi-parameter data logging
    Real-time Updates: Continuous data streaming

Implementation:

    ThingSpeak channel creation
    API key authentication
    HTTP request formatting
    Cloud data visualization

🛠️ Getting Started
Prerequisites

    TinkerCAD Account: For circuit simulation
    Arduino IDE: For code compilation (optional)
    MQTT Explorer: For MQTT experiments
    LabVIEW: For database and cloud experiments
    ThingSpeak Account: For cloud connectivity

Usage Instructions

    Click on the TinkerCAD links for each experiment
    Study the circuit connections and component placement
    Analyze the provided Arduino code
    Run simulations to observe circuit behavior
    Modify parameters to understand system responses

📊 Learning Outcomes

    Embedded Programming: Arduino C++ programming skills
    Circuit Design: Electronic circuit analysis and design
    Sensor Integration: Various sensor interfacing techniques
    IoT Protocols: MQTT communication implementation
    Data Visualization: LabVIEW graphical programming
    Cloud Connectivity: IoT data transmission to cloud platforms
    System Integration: Complete CPS system development

🔧 Technical Skills Developed

    GPIO control and manipulation
    Analog and digital signal processing
    Serial communication protocols
    Database integration and SQL queries
    HTTP API implementation
    Real-time data monitoring
    System debugging and troubleshooting

📈 Applications

    Home Automation: Smart lighting and climate control
    Industrial Monitoring: Temperature and environmental sensing
    IoT Systems: Device connectivity and data logging
    Weather Stations: Multi-parameter environmental monitoring
    Security Systems: Motion detection and alert mechanisms

📞 Support

For questions or issues with these experiments:

    Review the TinkerCAD circuit documentation
    Check component connections and wiring
    Verify code syntax and logic
    Test individual components before integration

🏆 Acknowledgments

These experiments demonstrate practical implementation of Cyber Physical Systems concepts, bridging the gap between theoretical knowledge and hands-on application in embedded systems and IoT development.
