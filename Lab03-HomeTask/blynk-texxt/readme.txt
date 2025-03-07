RGB Control Using Blynk Cloud (Text Input)
This script connects an ESP32 to WiFi and Blynk Cloud, allowing RGB LED control using text input. It also integrates an OLED display to visualize received data.

Workflow:
WiFi Connection: Connects to a specified WiFi network and prints the assigned IP.
Blynk Initialization: Authenticates with the Blynk cloud for remote control.
I2C Setup: Initializes the OLED display using I2C communication.
Blynk Handlers:
V0 Handler: Reads input from Blynk, parses text, and displays it on the OLED.
Connection Events: Logs when Blynk connects or disconnects.
Main Loop: Continuously runs Blynk to handle real-time interactions.