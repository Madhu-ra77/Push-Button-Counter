# Push-Button-Counter

**COMPANY** : CODTECH IT SOLUTIONS

**NAME** : MADHURA ANILKUMAR MANDLIK

**INTERN ID** : CT08FRL

**DOMAIN** : EMBEDDED SYSTEMS 

**BATCH DURATION** DECEMBER 25TH,2024 TO JANUARY 25TH,2025

**MENTOR NAME** NEELA SANTOSH KUMAR

**DISCRIPTION** 

            The project described focuses on creating a temperature sensor circuit that works with a push-button counter using the Tinkercad simulation platform. It demonstrates how an Arduino microcontroller, a temperature sensor, and a push button can be integrated into a single interactive system, where the temperature is measured and displayed, and the push button controls specific actions, like cycling through modes or incrementing a counter. The system also includes an LCD display to show the real-time temperature data and button-activated changes.Components Used:Temperature Sensor (LM35 or DHT11): The LM35 is an analog temperature sensor, providing a voltage that is directly proportional to the temperature in Celsius. Alternatively, the DHT11 is a digital sensor that outputs both temperature and humidity data. These sensors are the core components for measuring the environmental temperature.Push Button: A simple input device that registers either a HIGH or LOW state when pressed or not pressed. It’s used in this project to cycle through different readings or reset the counter value on the display.Arduino Board: The microcontroller (such as the Arduino Uno) reads the data from the temperature sensor and handles the push button input, processing the data and controlling the LCD output. It’s programmed to perform actions based on the button press and sensor readings.LCD Display: The 16x2 LCD display is used to show the temperature data and additional information, such as the counter value. It provides a clear and real-time visual output.Resistors and Jumper Wires: These components are used to manage the connections and ensure proper functioning of the push button (with a pull-down resistor) and temperature sensor.Breadboard: A breadboard serves as a prototyping tool to connect all the components together in a non-permanent, easily modifiable way.Circuit Design:The circuit in Tinkercad follows these steps:Temperature Sensor Connection: The sensor's Vcc pin is connected to the 5V supply of the Arduino, and the GND pin is connected to ground. The output pin of the LM35 is connected to an analog input pin on the Arduino, like A0. For the DHT11, the data pin is connected to a digital input pin, such as D2.Push Button Setup: One side of the push button connects to GND, while the other side connects to a digital input pin (e.g., D3) of the Arduino. A 10kΩ pull-down resistor ensures the input pin is correctly defined when the button isn’t pressed.LCD Wiring: The LCD connects to the Arduino using several digital pins (e.g., D4 to D7 for data, D12 and D11 for control), and the power connections are made to the 5V and GND pins.Programming the Arduino:The program is written in Arduino IDE and uploaded to the microcontroller. The key parts of the code are:Temperature Reading**: The analog or digital value from the temperature sensor is read. For the LM35, it’s an analog reading, which is converted into Celsius using a formula. For the DHT11, a library (DHT.h) is used to directly fetch temperature and humidity values.Push Button Logic: The push button’s state is checked using digitalRead(). Each press of the button increments a counter or cycles between different modes of displaying data (e.g., Celsius/Fahrenheit). A debounce function ensures that only one press is registered per button press.LCD Output: The LCD is used to display the temperature value and the current count, updating the display whenever the button is pressed.

**Conclusion**:
This project teaches how to integrate a temperature sensor with a push button counter and an LCD, offering a hands-on learning experience with basic electronics and programming in Tinkercad.
