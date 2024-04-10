## Plant Light Monitoring Device

This project is a plant light monitoring device built using Bolt IoT. It measures the light intensity around a plant and sends the data to the cloud for analysis. This README provides an overview of the project, hardware requirements, setup instructions, and usage guide.

## Hardware Requirements

To build and use this plant light monitoring device, you will need the following hardware components:

1. **Bolt IoT Module:** The Bolt IoT module acts as the core of the monitoring device, providing connectivity to the cloud and enabling data collection.
2. **Light Sensor:** A light sensor (e.g., LDR) is used to measure the light intensity around the plant.
3. **LED Indicator (Optional):** An LED can be added as an indicator to show the current status of the device (e.g., active, inactive).
4. **Resistors and Connecting Wires:** Required for connecting the components and ensuring proper functionality.
5. **Power Source:** A power source (e.g., USB power adapter) to supply power to the Bolt IoT module and other components.

## Setup Instructions

Follow these steps to set up the plant light monitoring device:

1. **Hardware Setup:**
   - Connect the light sensor to the Bolt IoT module using connecting wires.
   - Optionally, connect an LED indicator to the Bolt IoT module for status indication.
   - Ensure all connections are secure and properly insulated.

2. **Software Setup:**
   - Clone or download the project code from the GitHub repository.
   - Configure the Bolt IoT module with your credentials and API key.

3. **Deploy Code:**
   - Upload the main code file (`main.js` or similar) to the Bolt IoT module.
   - Start the device and monitor the console or cloud dashboard for data readings.

## Usage Guide

Once the plant light monitoring device is set up and running, follow these guidelines for usage:

- **Monitoring:** Check the cloud dashboard or console output for real-time light intensity readings.
- **Data Analysis:** Use the collected data to analyze the light conditions around the plant over time.
- **Maintenance:** Periodically check and calibrate the light sensor if necessary for accurate readings.
- **Troubleshooting:** If encountering issues, refer to the troubleshooting section in the README or project documentation.
