# **Real-Time Water Flow Measurement Using YF-S201 Sensor and Arduino**

## **Overview**
This project demonstrates a **Water Flow Measurement System** using an Arduino Uno and the YF-S201 water flow sensor. The system calculates the flow rate of water and the total volume of water that passes through a pipe. The measurements are displayed on a 16x2 LCD for easy monitoring.


## **Features**
- Real-time measurement of water flow rate in liters per hour (L/hr).
- Total water volume tracking.
- User-friendly interface with a 16x2 LCD display.
- Low-cost, efficient, and easy-to-build solution.
- Utilizes the Hall effect principle for accurate flow rate detection.


## **Components Used**

- **Arduino Uno**: The microcontroller for processing sensor data.
- **YF-S201 Water Flow Sensor**: Measures the flow of water using the Hall effect.
- **16x2 LCD Display**: Displays flow rate and volume.
- **Potentiometer**: Adjusts LCD brightness.
- **Breadboard**: Prototyping the circuit.
- **Jumper Wires**: Connects components.


## **System Overview**

### **Working Principle**
The YF-S201 water flow sensor uses the **Hall effect** to measure water flow. It contains a turbine wheel with a magnet. As water flows through the sensor:

![App Screenshot](https://github.com/itsharshschoice/Real-Time-Water-Flow-Measurement-Using-YF-S201-Sensor-and-Arduino/blob/main/Images/YFS201.jpg?raw=true)

1. The turbine rotates, generating pulses proportional to the flow rate.
2. Arduino reads these pulses to calculate:
   - Flow rate (in L/hr).
   - Total water volume.

### **Workflow**

1. **Input Data:** The water flow sensor generates pulses based on the flow.
2. **Processing:** Arduino processes the pulse data and calculates the flow rate and volume.
3. **Output:** The calculated values are displayed on the 16x2 LCD.


## **Hardware Design**

### Circuit Diagram

![App Screenshot](https://github.com/itsharshschoice/Real-Time-Water-Flow-Measurement-Using-YF-S201-Sensor-and-Arduino/blob/main/Images/Circuit%20Diagram.png?raw=true)

### Flow Chart
1. Initialize LCD and flow sensor.
2. Read pulse data from the YF-S201 sensor.
3. Calculate flow rate and volume.
4. Display results on the LCD.

![App Screenshot](https://github.com/itsharshschoice/Real-Time-Water-Flow-Measurement-Using-YF-S201-Sensor-and-Arduino/blob/main/Images/Flowchart.png?raw=true)

## **Software Implementation**

### Arduino Code
The Arduino code handles:
- Initialization of components (LCD, sensor).
- Reading pulses from the YF-S201 sensor.
- Calculating flow rate and volume.
- Displaying results on the LCD.

## **Results**
- Flow rate accuracy within ±5%.
- Stable real-time updates on the LCD.
- Scalable design for multiple applications.

![App Screenshot](https://github.com/itsharshschoice/Real-Time-Water-Flow-Measurement-Using-YF-S201-Sensor-and-Arduino/blob/main/Images/Results.jpg?raw=true)


## **Applications**
This project has diverse applications:

- **Industrial Processes**: Optimizing water usage and monitoring in manufacturing, cooling, and chemical processes.
- **Environmental Monitoring**: Studying water dynamics in rivers and managing water resources.
- **Home Automation**: Monitoring water usage and detecting leaks in smart homes.
- **Agriculture**: Efficient irrigation and water conservation.
Aquaculture and Hydroponics: Maintaining proper water flow for aquatic life or plants.

## **Future Enhancements**

- **Data Logging**: Store flow data for analysis and trends.
- **IoT Integration**: Enable remote monitoring and control.
- **Support for Multiple Sensors**: Expand to monitor multiple water lines simultaneously.
- **Advanced Displays**: Use TFT or OLED screens for enhanced visual representation.
- **Mobile App Integration**: Display real-time data on smartphones.


## **Installation and Usage**

### Prerequisites
- Arduino IDE installed on your computer.
- Basic knowledge of Arduino programming.

### Steps to Use

Clone this repository:

```git clone https://github.com/itsharshschoice/Real-Time-Water-Flow-Measurement-Using-YF-S201-Sensor-and-Arduino.git```

- Connect the hardware as per the circuit diagram.
- Upload the Arduino code to your board.
- Power the setup and monitor the flow rate and volume on the LCD.


