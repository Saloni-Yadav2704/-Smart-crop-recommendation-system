<h1>INTRODUCTION</h1>

The Smart Crop Recommendation System is an IoT-based project that helps in analyzing environmental conditions such as soil moisture, gas levels, temperature, and humidity to assist in recommending suitable crops.
This system uses sensors and a microcontroller to collect real-time data and display it on an LCD screen.

<h1>OBJECTIVES</h1>


1.Monitor soil moisture levels

2.Detect harmful gases in the environment

3.Display real-time data on LCD

4.Help farmers choose suitable crops based on conditions


<h1>COMPONENTS USED</h1>


| Component | Description |
|----------|------------|
| Arduino Uno | Microcontroller board |
| MQ-2 Gas Sensor | Detects gas levels |
| Soil Moisture Sensor | Measures soil moisture |
| 16x2 LCD Display | Displays output |
| Breadboard | Circuit building platform |
| Jumper Wires | Connections |
| LED | Status indicator |


<h1>MACHINE LEARNING MODEL</h1>

**Algorithm Used:** Random Forest  

###  Input Features
- Soil Moisture  
- Gas Levels  
- Temperature & Humidity

###  Output
- Recommended Crop

###  Model Description
The Random Forest algorithm is used to analyze sensor data and predict the most suitable crop.  
It works by combining multiple decision trees to improve accuracy and reduce overfitting.
Algorithm Used: Random Forest



<h1> CIRCUIT CONNECTIONS</h1>


| Component              | Arduino Pin |
|-----------------------|------------|
| MQ-2 Analog Output    | A0         |
| Soil Moisture Sensor  | A1         |
| LCD RS                | D12        |
| LCD Enable            | D11        |
| LCD Data Pins         | D3, D4, D5, D6 |
| LED                   | D7         |

All components share a common GND and power supply

<h1>WORKING PRINCIPLE</h1>


1. The Soil Moisture Sensor measures the water content in the soil.  

2. The MQ-2 Gas Sensor detects the presence of gases in the environment.  

3. The collected data is sent to the Arduino Uno microcontroller.  

4. The Arduino processes the sensor data and displays it on the 16x2 LCD.  

5. The sensor readings are used as input for the Machine Learning model.  

6. The Random Forest algorithm analyzes the data and predicts the most suitable crop.  

7. The final crop recommendation is generated.  

8. LED acts as an indicator for system status.

<h1>FEATURES</h1>


 1.Real-time data monitoring

 2.IoT + Machine Learning integration

 3.Accurate crop recommendation

 4.Low-cost and efficient system

 <h1>APPLICATIONS</h1>


1.Smart agriculture

2.Precision farming

3.Decision support system for farmers

<h1>AUTHOR</h1>
** SALONI YADAV**
