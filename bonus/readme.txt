DHT11 Sensor Monitoring with Blynk and OLED
This script connects an ESP32 to WiFi and Blynk Cloud, allowing real-time monitoring of temperature and humidity from a DHT11 sensor. The data is displayed on an OLED screen and sent to the Blynk app.

Workflow:
WiFi Connection: Connects the ESP32 to a specified WiFi network.
DHT11 Sensor Setup: Configures the sensor to read temperature and humidity.
OLED Initialization: Sets up an I2C OLED display for real-time data visualization.
Blynk Integration:
Sends temperature data to Virtual Pin V0.
Sends humidity data to Virtual Pin V1.
Sensor Update Function:
Reads temperature and humidity from DHT11.
Sends values to Blynk.
Displays readings on the OLED.
Main Loop: Continuously updates sensor data and syncs it with Blynk every 2 seconds.