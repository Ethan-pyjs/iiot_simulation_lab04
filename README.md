# IIoT Simulations using MQTT, CoAP, and OPC UA

## Overview

This project provides a simulation environment for Industrial Internet of Things (IIoT) communication protocols, including **MQTT**, **CoAP**, and **OPC UA**. The simulations demonstrate how these protocols can be used for efficient and secure machine-to-machine (M2M) communication in industrial settings.

## Features

- **MQTT Simulation**: Publish-subscribe messaging for lightweight and efficient communication.
- **CoAP Simulation**: RESTful resource-based communication optimized for constrained devices.
- **OPC UA Simulation**: Secure and interoperable data exchange for industrial automation.
- **Protocol Comparisons**: Analyze the differences in latency, security, and scalability.
- **Visualization & Logging**: Monitor message exchange and analyze protocol performance.

## Requirements

- Python 3.8+



## Installation

```sh
# Clone the repository
git clone https://github.com/iiot_simulation_lab04/iiot-simulations.git
cd iiot-simulations

# Install dependencies
pip install -r requirements.txt
```

## Usage

Run individual protocol simulations:

### MQTT Simulation

```sh
python mqtt_sensor_simulation.py
```

### CoAP Simulation

```sh
python coap_sensor_simulation.py
```

### OPC UA Simulation

```sh
python opcua_sensor_simulation.py
```

