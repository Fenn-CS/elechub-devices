---
services: iot-hub 
platforms: python
author: azure-iot-sdks
---

# Azure IoT Samples for Python

azure-iot-samples-python provides a set of easy-to-understand, continuously-tested samples for connecting to Azure IoT Hub via Azure/azure-iot-sdk-python.

## Prerequisites

- Python 2.7.x or 3.5.x on your development machine.  You can download Python for multiple platforms from [Python.org](https://www.python.org/downloads/).  You can verify the current version of Python on your development machine using 'python --version' or 'python3 --version'

- Create a virual and enviroment and install `azure-iothub-device-client`

```
pip install azure-iothub-device-client
```

- Run simulated device (in activated virtual enviroment)

```
python MeterOne.py
python LineMonitorOne.py
```
## Resources

- [azure-iot-sdk-python](https://github.com/Azure/azure-iot-sdk-python): contains the source code for Azure IoT Python SDK.
- [Azure IoT Hub Documentation](https://docs.microsoft.com/azure/iot-hub/)
